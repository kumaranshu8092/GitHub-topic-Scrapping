# GitHub-topic-Scrapping


# References and future works
Summary:
 In this project we have divided the whole project in 3 phases:

 1-We will make list of all the topic names,topic descriptions,
     topic_url and form a dataset using pandas library
 2- We will make list of all the top repo,username,repo link and stars of that repo
     and form a dataset using pandas library
 3- In the final stage we will compile all the above work and write and function 
    to travers through all the topic links and make CSV file for each topic which 
    will contain all the details of username,repo name, repo link, star count



 What we have done to achieve the 1st stage is:
 1- We got the topic page url
 
 2- get the text formate of that page using requests.get() function
 
 3- parsed the text formate to html with the help of BeautifulSoup 
 
 4- after parsing the page we will:      
 
     -start going through the page and get the tag name under which the required details are mentioned and after 
      that we extract the details from that tags using find_all function with the help of name of class under the tag
      
 5- After extracting the details we make list of all the details
 
 6- After making the list,formed a dictionary to of lists and after that
 
 7- After making the list we made the dataframe using pandas 
 

References to the link:
-https://github.com
-https://github.com/topics
-https://www.crummy.com/software/BeautifulSoup/bs4/doc/
