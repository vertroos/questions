
Platform Engineering Code Assessment

1. Rank each of the following languages and frameworks on a 4 point scale, where 1 = "I've been paid to write production quality code with it." and 4 = "I could write a Hello World web application if I had a tutorial."

* Python
* PHP
* Scala
* Clojure
* Golang
* Node.js
* Ruby
* Perl
* JQuery
* Java
* React
* Vue.js


1. In any language of your choice, write a utility that will translate a
    hexadecimal string to base64. Here's a test: this string `45766964696e74`
    should be converted into this string `RXZpZGludA==` .                      
2. Tell me the story (with some details) of what happens when I go to my
   browser and type in: "www.python.org" and press enter? What are things 
   you've seen go wrong?
3. Let's say I am working on a website. I want to know if the username is
   already in use in Django. I write the function below to tell me whether the
   user exists or not. What would you change or what would you tell me in a
   code review? How would you test it?:

def func(testme):
    list = User.objects.all()   
    for z in list:        
        if z.user_name == testme:            
            return true
