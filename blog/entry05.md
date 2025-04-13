# Tinker With Tool
##### 4/11/2025

### Where I am at Now 

For the past weeks, I have been pracitcing learn my tool that I will use in my Freedom Project Website. The website that I will be using for my website is known as <a href="https://bulma.io/">Bulma.io</a>, a modern CSS framework that has similar components to <a href="https://getbootstrap.com/docs/5.3/getting-started/introduction/">Bootstrap</a>. As I practiced with Bulma.io, there were many components I have tinkered with such as <strong> Columns, Menu, and Breadcrumb</strong>. In the time that I had to tinker with Bulma, I did not get to everything I wanted to practice using, but that was okay because I have already learned enough of bulma to actually make a website.


### How I Tinkered

 What really helped me in my learning was taking multiple notes in my learning log, so that I can remember what components I used and how to use those components. When tinkering with Bulma's components I had used the components that I have written in my learning log to make my own prototype website so that I can be ready for when I start to make my Freedom Project Website. Even though I did not finish it, it was good for me to learn how to use Bulma.io myself in HTML and CSS. The way I used each component was by creating a seperate file from the website, tinkering with the component and then using it in my website. Despite not finishing the prototype website, it was good for me to learn how to use Bulma.io myself in HTML and CSS. When implementing these components, I took them from the website and customized them to my liking and I even saved my customized components in my learning log so that I may know about <strong> their responsiveness, how much content I can put in them and how the component works.</strong> 
### What I Tinkered With 

 #### Columns
Each column can equally adjust itself no matter the amount of columns there are depending on how you set up each individual column. Below this, each vertically alines with each other on big screens and horizonally on smaller screens.

```
<div class="columns">
  <div class="column">First column</div>
  <div class="column">Second column</div>
  <div class="column">Third column</div>
  <div class="column">Fourth column</div>
</div>
```


* There are ways to adjust the spacing of a column, using one of the following classes
  * `is-three-quarters`
  *  `is-two-thirds`
  *   `is-half` `is-one-third`
  *   `is-one-quarter`
  *  `is-full`
 
From numbers 1-12, the grid system divids columns into 12. Size classes is `is-#1-12`. You can use this grid system to offset the position of certain columns. 


```
-----------------------------------------------------------------
<div class="columns is-mobile">
 <div class="column is-half is-offset-one-quarter"></div>
</div>
```
There are two ways to make the columns take up a certain space at a certain breakpoint.


```
Via fractions
--------------
is-three-quarters
is-two-thirds
is-half
is-one-third
is-one-quarter
is-full
 Via percentages
 ----------------
is-four-fifths
is-three-fifths
is-two-fifths
is-one-fifth
```


 #### Responsiveness
 
There are other responsiveness methods for implementing breakpoints such as:

```
mobile: up to 768px
tablet: from 769px
desktop: from 1024px
widescreen: from 1216px
fullhd: from 1408px
```

* This is most commonly used in columns
*  Here is a description of how to implement different points of responsiveness to columns:

`<div class="column is-size-2(Original size)  is-size-1-desktop(At this size at desktop px) has-text-centered">Hello World And Welcome to Website</div>`


#### Breadcrumb 


Acts as a navbar at the top of a webpage 
* Example:
```
<nav class="breadcrumb (You can put is-centered/is-right to change where navbar goes)" aria-label="breadcrumbs">
  <ul>
    <li><a href="#">Bulma</a></li>
    <li><a href="#">Documentation</a></li>
    <li><a href="#">Components</a></li>
    <li class="is-active"><a href="#" aria-current="page">Breadcrumb</a></li>
  </ul>
</nav>
```


### Skills that I have Learned

Getting to understand Bulma was not easy, there were many instances where I got stuck and learned from them, one the major times was when I was practicing using <strong>Columns</strong> in my webpage. At first I did not understand how to implement its responsiveness properly, the alignment of the content always seem off. I was so confused and wanted to give up on tinkering with the columns. That was when I found out about <strong>`is-narrow` columns</strong>. Narrow columns can allow you to change the width and height of a column to your liking, letting the next column take up the remaining space. 

```
<div class="columns">
  <div class="column is-narrow">
    <div class="box" style="width: 200px">
      <p class="title is-5">Narrow column</p>
      <p class="subtitle">This column is only 200px wide.</p>
    </div>
  </div>
```

From this, I have learned to <strong> be patient in my learning and how to comprehend new material</strong>, which has helped me learn more about Bulma.io. So whenever I got stuck during my time tinkerwing with Bulma, I have found a <a href="https://www.youtube.com/watch?v=SCSAExGFK1E&t=245s">series of videos</a> on youtube that go through the basics on how to use bulma. 

### Final Thoughts

Despite not having all the time to review all of the Bulma.io features, I am glad enough to manage to learn more about my chosen tool, so that I can use it when I start on creating my Freedom Project Website!


[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
