## HW1: Introduction
Hi, my name is Joe Mezera. I am a senior here at the College of Charelston. I hit global in wingman. I like cars, and computers, and going to in person classes.

## HW2: Reflections on FOSS
The reading The Cathedral and the Bazaar compares linux to the bazaar. Cathedrals are often designed by one person, the whole idea comes from one mind and it is that one persons masterpiece. The bazaar is a collection of many different people doing their own little thing but all in the same building. Linux is like the bazaar because they are all contributing to the linux operating system but they are all contributing in their own unique way. It is a collection of other peoples ideas, not one persons masterpiece, and thats one of the things that makes linux great. 

For our open source project we decided on PokeAPI. PokeAPI is a project that interests the whole group and they hae lots of issues reported in the issues tab. It is written mostly in python which our whole group is familiar with. The goal of PokeAPI is to great a centeralized database of all of the pokemon information so that webistes that need the information don't have to use multiple different sources for their data. PokeAPI strives to have images, move lists, names, types, and gender for all pokemon. Our group also looked into doing zulip but ultimately decided against it because it seemed less interesting.

## HW3: Reflections on Open Source in Todays World
I read an article about new, open-source, 3D printing software that allows users to avoid the proprietary software and 3D printing materials that are expensive to use. This is allowing for the expansion of 3D printing and makes it more accessable to at home users and also makes it more viable to mass manufacturing. Affordable 3D printing will allow for many things to be stronger while remaining cheaper and quicker to make. One example of 3D printing being used to make stronger things while making them lighter and cheaper than before is Porsche. Porsche is using 3d printing to make pistons using topographical mapping. With this method they only need to print the alluminum alloy in areas that are load bearing,leaving the rest empty. This allows for less material to be used, making it lighter and cheaper, and it is cheaper and stronger than other methods that topographical mapping is possible. The current way strong affordable pistons are made it isn't even possible for topographical mapping for be implemented because it would actually ruin the integrity of the object. 

## HW4: This Bugs Me
Exercise 6.4 - Find the Oldest Bug:
[The Oldest Bug](https://github.com/darkreader/darkreader/issues/489) is a bug that says that the dynamic theme feature for darkreader does not work on youtube. The issue is marked as not resolved. I don't actaully know what the dynamic theme feature is so it may have been removed because right now users need to manually change the theme of websites so the feature may have been removed hence why it hasn't been fixed. 

Exercise 6.5 - Create Your Bug Tracker Account:
Our chosen FOSS uses github issues to track its bugs and there is no need to install other software. 

Exercise 6.6.1 - Reproduce a Bug:
I tried to reproduce a bug that caused google sheets to load forever with darkreader enabled and I could not. The user posted a link and reported that with darkreader enabled that it would load forever. There was one other response saying that they also could not reproduce the bug. 

Exercise 6.7.1 - Bug Triage:
I had difficulty finding bugs that weren't boing looked at. Everything already either had a fix pushed to it, had extensive comments and questions, or the poster suddenly stopped responding. The only bugs that seemed like they might need assistance were bugs on MacOS and I don't have access to a mac. 

## HW5: What's Happening?
7.2.2

without u flag

>    printf("Hello, World.\n");
---
>    printf("Hello, World!\n");
>    

with u flag
--- helloc.c.punct    2021-02-11 12:55:37.610201495 -0500
+++ hello.c    2021-02-11 12:55:58.562039387 -0500
@@ -5,6 +5,6 @@
 #include <stdio.h>
 int main(){
-       printf("Hello, World.\n");
+       printf("Hello, World!\n");
        return 0;
 }
 


I read an article about human values and software engineering. The article was quick to point out the difference between human values and business values and that many times the human values can be overlooked in pursuit of business values. One of the examples they used was the Volkswagen emissions scandal. Volkswagen engineers intentionally programmed the car to run more efficiently on the emissions testing machine than it did in the real world. This was an example of engineers putting asside human values, like health and safety, for business values, profit and cutting costs. This resulted in a huge loss in sales for Volkswagen for the next few years as well as a fine and the resignation of their CEO. Thats one of the problems the article was addressing though. Unfortunaltely businesses need to be regulated by hurting them financially instead of them just doing the right thing. The engineers wrote that software, and the department heads let that idea through knowing it was bad for the environment and human health. A potential solution to problems like these is discuessed with the development of the Shwartz model. It can be difficult and dangerous to create concrete definitions for human values so they came up with value portraits. Value portraits create a clear taxonimy of human values for a project. A list of things that the project should and shouldn't do. The following value portrait is from the Clasp project which the article discusses. Clasp is a project that attempts to tackle social anxiety in autistic people.

[Value Portrait Table](https://drive.google.com/drive/u/0/folders/1fccaM49tOoawLg2x9pxC_LGj83MtpGPr)
Trying to add the actual picture broke the blog for some reason

Some of the imporant goals for the project are listed in the list to make sure that the program not only acheives its goal, but that the developers actively make sure that it is respecting human values as well. This makes sure that the goals of the project are complete along with making sure that users are comfortable and more than satisfied with the product. The product doesn't just meet the company values but it addresses its users human values as well. 

## HW6: Stupid or Solid?
I have heard of the SOLID coding priciple before but i haven't heard it contrasted with STUPID. All the principles discussed in the reading make sense and they are thing that, if not directly taught, are indirectly taught in classes here at CofC. Like the article said, writing solid code is not hard its just more time consuming and you can't be lazy about it. All of the SOLID principles are basically a listed out, more specific, version or KISS, keep it simple, stupid. Make sure code is easy to understand and easy to modify. Make sure you don't have any extra classes or methods, make sure it functions as described. 

## HW7: Release Early and Often
In the readings from chapter 8 and the one page of chapter 9 the book talked about documenting code and the concept of release early and often in software engineering. Chapter 8 talked about the importance of documentation in a project, speciffically a free open source project. Good documentation is the key to smooth and efficient workflow because it allows people to understand the thinking behind methods and classes and the uses for them without doing their own outside research or waiting on an email back from the original author. That is also assuming that the original author remembers what they were doing with that code in the first place. Documenting code isn't only important for other people contributing code, but for personal projects as well. The reading points out that if the original author were to come back to code they wrote 6 months ago they likely would not remember exactly what they were doing with the code or what it does. Contributing documentation to a FOSS can also be a good way to support the project without actually writing code. You may not be familiar with the language the program is wwritten in or maybe there just isn't much coding work to be done on the project.

Chapter 9 was only one page for some reason but it talks about the concept, release early and often in programming. It appears that the chapter hasn't been finished yet but the idea is that release early release often should be used in areas besides software. The author then goes on to talk about the goals of the textbook and where to find the new releases. Release early and often isn't discuessed in depth here but it is as simple as it sounds. Get your work out there when its finished. Contribute what you have and make changes along the way. 

## HW8: Chapter 5
Chapter 5 was about domain classes, or domain class development. Domain classes are used often and they are useful because it can make programming more efficient. Domain classes are classes that are meant to be used in mulple instances to represent something similar in each. The book uses the example of the person class. Each of their projects have different requirements for the person class but because there is so much similarity it is much easier to add variables when they are needed to a preexisting class than to create a whole new one for each project. The chapter also dicusses test driven development. Domain classes can make testing easier. If the code is test driven then, thanks to the domain classes, the testing process for some classes will be similar and therefore, more streamlined. 

##HW9: Chapter 6
This chapter of the book talks about database development. The chapter first talks about some of the basics of databases and some SQL terminology. IT also talks about naming conventions in SQL. SQL databases are made up of relations and tables. To access information it must be quereied using logic that allows the specific desired information to be chosen. The book then goes on to talk about normalization. Normalization is : a stretegy for designing tables so that they support general-purpose quereying and ensure data integrity."Normalization insures that tables can be queried using a standardized language. This way, people accessing the database dont have to learn the nuances and structure of every database they work with. 

##HW10: Chapter 9
Chapter 0 discusses what needs to be done after the initial completion of a project. It discuesses how to evaluate a project, how to deal with the project changing teams or leaders, and how to plan for the release of a project. There are many thinks to keep in mind when the initial project is completed. Some of the questions that the book poses when a project is being released are, "Who are the potential new clients for this product", "which open source license should govern its distribution for reuse?", "Where and how should the first release be published?”, and " How can we assess the maturity of this product as it evolves?" These are all important questions to consider when releaseing a product. 

##HW11: Meeting Charleston
I went to a tech after five event for my meeting charleston event. Tech after 5 is a tech related networking event for anyone who wants to attend. At this tech after 5 we were blessed with the attendence of Richard Bliss. Richard Bliss is a top social selling trainer for linkedin. Although the event wasn't intended to be about him, everyone attending took the opportunity to learn from him and he ended up leading the event. Richard talked about how to set up a linkedin profile for success and talked about how to promote oneself through linkedin. 
