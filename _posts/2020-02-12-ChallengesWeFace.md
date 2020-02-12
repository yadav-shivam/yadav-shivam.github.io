---
published: true
---
![0.jpg](/img/0.jpg)


## Challenges We Face When Our App Goes Into Million Hands

### 1. Bad Architecture is a life time pain.

> Good building comes up with good people & all problems are solved by good design.
  
  
The most important point is to have a good architecture of your application which starts with a good design. Spend time analysing what you are going to build and always remember that don't try to design the prototype of car if you are planing to sail. The design must be made after analysing all the aspects which can improve the performance of the application.



### 2. A good beginning makes a good ending.

Most of the uninstalls happens just because of a bad beginning. The signup process plays a very important role for a new user, if user sticks at the signup process then he/she will definitely uninstall the application. I saw several application where I wait for minutes to get the verification link on my e-mail or to get the otp on phone.

  Always remember to make the signup process as simple as it can be according to the type of application you are building.



### 3. Quality should not be an act, it should be habit.
  
> If you don’t like unit testing your product, most likely your customers won’t like to test it either.
  
We made a lot of mistakes during this phase like after testing on few devices we think that our app is ready for launch , remember > "Just because you’ve counted all the trees doesn’t mean you’ve seen the forest." , when our app goes into millions of hands then it faces the scenarios you have never think of . If we talk about Android then the biggest pain to every android developer is it's fragmentation , there are thousand's of devices available in the market with different configurations . You never know when and where your app stops working . I remember a situation when one of app was throwing error in only Huwaei device . One more example, not a single Android developer has finished an app without using SharedPreferences API. It’s so common, yet it was broken in Samsung Galaxy S with Android 2.2

  Test your app as thoroughly as possible. Spend time for writing automated test cases. **Create various stressful situations for your app and see if it can survive.** Test your app using various tools where you can run your app on multiple devices. Go with the load testing of your apis which you are using.
  If you want your app to be bug free then I believe before testing the app test your code , **each and every line of your code needs to be tested.** An untested copied code will always be a pain one day. 
  


### 4. Start optimising your code

> It's easier to optimise correct code then correct the optimise code.

An unoptimized code must be working today but it will surely show it's true colours one day. Remember you are building mobile application that means you are having very less resources so you must use them very wisely. Server communication is the important part , if you are hitting multiple apis on a single page then think of the scenario when 1 million users open up that page , your server will probably get into trouble. 

  Always keep in mind about the **performance** of your code and the **memory** your app is using and how much **secure** your application is ? You can test the performance with the help of performance monitoring tools e.g. firebase tools etc. and can check the memory management with the help of tools easily e.g. leak canary , native profiling tools, etc.
  
  **Security** is very important aspect depending on the type of application you are building. Here android developers need to be more aware as compared to iOS developers. Never ever, ever make the mistake of releasing your app on the Play Store without using ProGuard. **ProGuard not only minifies your code, but it obfuscates your code** making it harder for reverse-engineers to understand, replicate and manipulate it. It's completely free and bundled with android studio.



### 5. Think 100 times before picking up third party library

  You must choose the third party library very wisely. Never ever rely on third party with full trust because it can any time become a threat for your application, the simplest reason for the same is that you never know what code is written inside it so it can stop in some scenarios or some devices.
  
  So review the third party very well before using it, if it popular then there are less chances of failure if not then review it properly . Check if the library is having any open issues on their github profiles ,if yes then don't use it.



### 6. Don't forget to enable force update

Every application you are putting on stores must have the feature of force updates. It will be very helpful when your application is having any major error and you want your all users to update the app. It can easily be achievable by managing the version codes on your server.



### 7. Git can be your backup plan

Start using git if you are not using it till now, proper git management is very mandatory for a product to be successful. There are several benefits of using git like - Distributed model: This means your work is your own. You can let others see only what is necessary, Branching and merging are easy: Branching is a walk in the park, Workflow is flexible, Data integrity is assured: Because git uses SHA1 trees, data corruption due to external reasons can be easily detected.
 


### 8. Is your server expecting more guests ?

Is your server scalable enough if large number of users enters into the application? Your server must be prepared for the worst case , it should be ready to accept the load as per the target. In one of my application I get 50 thousands users overnight then the server started to crying at the moment. Ultimately we improved it in the morning by increasing the configurations.

So **always be ready with the quick support plan**, sever needs to be monitored continuously. It should be more secure to avoid attacks and hacks. 


Thanks for giving your time to read this article, if you like it then please share it.
