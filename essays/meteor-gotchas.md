---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-03-09
labels:
  - Software Engineering
  - Meteor
---

<p>The digits application, has been a fun hands on way to learn how to use meteor and mongodb. With this project we get to see first hand how meteor and mongodb work. However though it has been a fun experience it does have its share of problems that arise. I will share two issues that have plagued my coding process. </p>

<h2> Antivirus and Indexing</h2>
<p> The first of these problems would be the loading speed of meteor as well as the time that it takes for intellij to index the files that you are going to use for the project. Unfortunately the only way to speed this process up would be to close any processes that you are running on your computer that you do not need. One thing that I have found on Windows 10 when trying to speed up indexing is to disable your antivirus software. On windows 10 you may find that your antivirus software Windows Defender is always running in the background even when you turn in off. THe way to fix this is to go into your registry files and disable it from there. To do this you must follow the following steps.</p> 
<br>
Open cmd and run gpedit.msc <br>
Computer Configuration > Administrative Templates > Windows Components > Windows Defender.<br>
Highlight “disable windows defender”<br>
Click enable<br>
Click apply<br>
Click ok<br>


<p> And with luck you should have successfully sped up your indexing speeds!</p>

<h2> Managing Too Many Tabs</h2>
<p> Another major problem that I have run into when working on the digits problem would be how to manage all of the different HTML pages that you are working on. For some of you this may sound familiar. You would be working on a page and all of a sudden you need to work on a different one. How does one manage all of the different tabs on Intellij you are using?</p>
<p> The best answer for this I have found is to only use the side bar when navigating my pages. The reason that I recommend the sidebar is because it separates each file into different directories which gives the programmer an Idea of what each file is doing. From here you will be able to find the specific file that you wish to work on. For example if you wanted to work on your header you would simply look at the sidebar and look for the ui directory. Just click on layouts and there your header.html file is! The side bar creates a quick way for a programmer to navigate all of their files as well as helps them organize. </p>

<p> I hope these tips have helped you organize and speed up your coding while working on the digits project as well as any future projects. Happy Coding!</p>

