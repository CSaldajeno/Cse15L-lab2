# CSE 15L Lab Report 2
## by Camille Saldajeno
___

### Part A
**StringServer code**
![Image](stringServerCode.png)

**add message screenshot 1**
![Image2](message1.png)

* The handlerRequest in Handler class is called.
* The relevant arguments are the path `/add-message` and query parameter `s=i love food`, while the relavant fields are `message` and `num` of the Handler class.
* The  `message` and `nums` fields both change whenever a new string is added. The value "i love food" is added to the existing letters field and is printed after the previous update ('Hiiii') and nums is incremated by 1 after every new message.


#### add message screenshot 2
![Image3](message2.png)
* The handlerRequest in Handler class is called.
* The relevant arguments are the path `/add-message` and query parameter `s=I hope pt. 2 of "the Glory" is good`, while the relavant fields are `message` and `num` of the Handler class.
* The  `message` and `nums` fields both change whenever a new string is added. The value "I hope pt. 2 of "the Glory" is good" is added to the existing letters field and is printed after the previous update ('i love food') and nums is incremated by 1 after every new message.

### Part B
#### Private Key
`/home/linux/ieng6/cs15lfa23/cs15lfa23mi/.ssh/id_rsa.pub`
![Image4](private_key.png)

#### Public Key
`/Users/donuts/.ssh/id_rsa.pub`
![Image5](public_key.png)

#### No Password
![Image6](no_password.png)

### Part C
Something I learned about in week 3 is the .ssh command. I find it convenient how you can log in to your remote account without a password after running mkdir .ssh, logging out of remote account and running the scp command.
