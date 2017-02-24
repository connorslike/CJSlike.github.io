---
layout: essay
type: essay
title: Semantic-UI The Secret To a Better Webpage
date: 2017-01-20
labels:
  - Semantic Framework
---

  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/semantic-ui/2.2.2/semantic.min.css">
  <link rel="stylesheet" href="style.css">
  <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
  <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/semantic-ui/2.2.2/semantic.min.js"></script>

<p> If you have ever tried programming a web page you are most likely among those who know how difficult it is to add simple features without 
 ruining the format of your site. Just adding something as small as an input feature could turn your beautiful web page into a horrid 
 mess of misaligned div’s. However there is a way to save time and frustration, and that is to use a UI Framework. </p>
  
<h2> Why Semantic?</h2>
  
<p> Now you may be wondering why you should waste your time using a UI Framework like Semantic when you already know CSS. 
 Why waste your time learning a framework that basically does everything you already can do. The answer is time. 
 Using a framework will allow you to do things with your website in minutes that would have normally taken you hours using pure CSS. 
 Take a look at the example below.</p>
 
<div class="ui ordered horizontal list">
  <a class="fitted item"><button class="positive ui button">Left Button</button></a>
  <a class="fitted item"><input type="button" id="myBtn" onclick="myFunction()" value="Right Button"></a>
</div>

<p> Looking at both buttons could you guess which button was harder to implement? Lets look at the code and see! </p>
<br>
```
<button class="positive ui button">Left Button</button>

<input type="button" id="myBtn" onclick="myFunction()" value="Button"
```

<p> As you can see even though the left button is much more detailed it is much easier to implement than normal html/css. Using Frameworks make implementing complex css easy and fast. The best thing about using a UI Framework is that you can implement it any place that you are able to call html/css and you do not need to download any librarys or files to make it work. You can make websites with a couple of simple commands like the one shown below.</p>

  <div class="ui fluid image">
    <image src="/images/full.jpg"></image>
  </div>
<p> As we can see a well formated site can be created with hardly any css. By implementing a UI Framework such as Semaantic-UI you will save yourself time and energy creating well made websites with a high level of functionality just by using simple commands. From my experience so far there is little to now downside to implement semantic in your code, and with little effort you can start creating high end websites in no time</p>
