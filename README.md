# DocumentSearchEngineWebApplication

**Instructions to run the code**

As the data is huge it will take more than 10 hours to generate a word Tfidf and Bigram Tfidf by running preprocess.py and to collect data from api it will take more than 6 hours by running the datacollection.py. 

So, to save that time import the collections from cnndata folder into mongodb database name CNNProxy.

Cnn folder can be downloaded from the below link.

https://drive.google.com/file/d/1Prcc3ktlUdJjm_molXU6lsW3O5qIQpqj/view?usp=sharing


  

Download the program files from https://github.com/meghasravani95/DocumentSearchEngineWebApplication

Enter the following Commands: (Windows)
$ set Flask_app=hello.py
$ set Flask_env=development

This command updates the changes into the flask server directly with out typing the flask run command every time when we have made any change.

$ flask  run

After this command, the debugger, server, reloader will be started at local host server.

 

Type http://127.0.0.1:5000/ in the browser then the homepage will be displayed as below.

 

Topic Categorization results:

Click on the respective category in the navigation bar. Below are the screen shots that will show the respective page.

World:

 



Travel:

 


Politics:

 




Sports:


 


Document Search Engine results:

For a word like food:

 




For a bigram like joe biden:

 


For details of the article, Click on for Quick reference of article

![image](https://user-images.githubusercontent.com/56423729/117166705-9e727b80-ad94-11eb-898d-6bc939b097fa.png)

 
If you click on image or the headline, it will be redirected to CNN page which contains this article. Also, the visited url’s are distinguished from the unvisited ones.



