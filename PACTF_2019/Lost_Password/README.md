# Lost Password
This was pretty straight forward, as you just had to write a few lines of code to fetch the password:
~~~
 f=open("path","r")
 a=f.readlines()
 for elmt in a:
     elmt=elmt[:-1] #removing the newline character 
     if len(elmt)==20 and elmt.startswith("fe") and elmt.endswith("g"): 
         print(elmt)
         
~~~

By doing this you get the flag:
## fejfoslendpinwoehgng

