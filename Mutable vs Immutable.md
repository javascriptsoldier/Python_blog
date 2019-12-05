First, we need to know every part in python will be treated as an object
For example, if you created object 10 with the reference of a will be
a =10;
hear a is reference variable and 10 is the object
if you print the address of the object be like
id(a)
output : 1641007168

Now assign another object to the available a
a = 15
then again print the address of the object 
id(a)
output : 1641007248
this time will get something like 1641007248 which is different for the above

Behind the science 
when you declare a =10;
  we are creating object a with the reference of variable a
aging we declare a =15
  this time we are creating another object and removing a reference to first object(10) and linking with a newly created object (15)
  so we haven't deleted object 10. we just removed the reference with object 10 and moved that object into garbage collecter
