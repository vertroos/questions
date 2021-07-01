## Background

1. We will discuss solutions to these problems on the call.
2. It's okay to look things up or ask a friend, just like a real job.


## Developer Coding Questions

1. In any language of your choice, write a utility that will translate a
    hexadecimal string to base64. Here's a test: this string `45766964656E74`
    should be converted into this string `RXZpZGVudA==` .                      
2. Tell me the story (with some details) of what happens when I go to my
   browser and type in: "www.python.org" and press enter? What are things 
   you've seen go wrong?
3. Let's say I am working on a website. I want to know if the username is
   already in use in Django (or your favorite backend framework). I write the
   function below to tell me whether the user exists or not. What would you
   change or what would you tell me in a code review? How would you test it?:

```python
def func(testme):
    list = User.objects.all()   
    for z in list:        
        if z.user_name == testme:            
            return true
            
     
```

```javascript

func(testme) {
    data = axios.get("/users/").then(resp => resp.data);
    for z of data {
       if (z.user_name == testme):            
            return true
    }
}
```
