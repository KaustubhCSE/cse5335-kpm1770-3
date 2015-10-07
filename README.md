# CSE 5335 Web Data Project 1

Date: 6th October 2015

Name: Kaustubh Mohgaonkar

ID: 1001101770 
NetID: kpm1770

1. What server framework did you use and why?

>I used Ruby on Rails for the server framework. One of the main reasons for using Ruby on Rails was its organization. Everything is really easy to understand and we are able to make changes or add or delete configurations, controllers, views very easily. Ruby on rails also allows to install various gems, which are very helpful and save lot of work.

2. What client frame work did you use and why?

>For Client framework I chose JQuery because it is one of the most widely used JavaScript library in web programming which uses document object model. I wanted to work with Google maps, so using JQuery was advantageous as Google provides lot of support and examples. Also AJAX calls are really simple in JQuery.

3. What aspect of the implementation did you find easy, if any, and why? 
>I think the easiest part was working with Google maps API. The documentation is very well maintained and there is a lot of help online if needed. There are several examples in multiple languages and/or libraries.

4. What aspect of the implementation did you find hard, if any, and why?
> For me the toughest part was setting up Ruby on Rails in my Ubuntu machine. I had a lot of permission errors initially. I also faced some challenges in installing POSTgres DB which was technically not needed for the first project but I did not want to take risks.

5. What components OTHER than your client and server framework did you install, 
if any, and if so, what is their purpose for your solution?
> For the initial phases of my project, I had decided to work with Angular JS as my client framework. For this to work hassle free, I installed 'bower' which takes care of all dependencies needed to run Angular JS. But later I switched to JQuery.

6. What Ubuntu commands are required to deploy and run your server?

Ubuntu Commands needed to deploy locally:
1. cd app_name
2. bundle install
3. rails s (to start server)

To push code to GIT:
1. GIT add .(to add all files)
2. GIT commit -m "Your Message"
3. GIT PUSH (this requires your GIT credentials)

Application can be deployed in Heroku by connecting GIT and Heroku and using heroku/deploy web page.
