# Tool Learning Log
## Tool: **Bulma.io**


### 3/3/2025
* Today I have learned to active menus in my website using file links to different pages, adding more to my website. In my webpage I talked about Github, why and how it was used.
* Formed some HTML code from the <a href="https://bulma.io/documentation/components/menu/"> Bulma.io menu code</a> and formed it into my own to start the beginning page of my website.

```
<aside class="menu">
  <p class="menu-label">General</p>
  <ul class="menu-list">
    <li><a>Dashboard</a></li>
    <li><a>Customers</a></li>
  </ul>
  <p class="menu-label">Administration</p>
  <ul class="menu-list">
    <li><a>Team Settings</a></li>
    <li>
      <a class="is-active">Manage Your Team</a>
      <ul>
        <li><a>Members</a></li>
        <li><a>Plugins</a></li>
        <li><a>Add a member</a></li>
      </ul>
    </li>
    <li><a>Invitations</a></li>
    <li><a>Cloud Storage Environment Settings</a></li>
    <li><a>Authentication</a></li>
  </ul>
  <p class="menu-label">Transactions</p>
  <ul class="menu-list">
    <li><a>Payments</a></li>
    <li><a>Transfers</a></li>
    <li><a>Balance</a></li>
  </ul>
</aside>
```
* Bulma CSS Tutorial Video Series used as a reference in case I have trouble with using any Bulma CSS.
##### Questions:
* How will I use CSS in my webpage?
* How does the Dropdown Button work?

### 3/11/2025

* Today I tinkered with Bulma's grid system.
* Using <a href="https://bulma.io/documentation/grid/playground/">this bulma.io page</a>, I adjusted the cells to my liking.

* Some Grid styles I tinkered with: 

```
 <div class="grid is-gap-1">Cell 1</div>
-----------------------------------------------
<div class="grid is-col-min-9">Cell 2</div>
----------------------------------------------------------------
This grid-changes-where-the-cells-are-depending-on-start-and-end
<div class="fixed-grid has-4-cols">
  <div class="grid">
    <div class="cell">Cell 1</div>
    <div class="cell is-col-start-3">Cell 2</div>
    <div class="cell">Cell 3</div>
    <div class="cell">Cell 4</div>
    <div class="cell">Cell 5</div>
    <div class="cell">Cell 6</div>
  </div>
</div>
------------------------------------------------
```


##### To do:

* Figure out how to apply apporiate spacing.
* Include context for each cell.
  

### 3/19/2025

* Figured out how to apply background seperately into cells without them automatically stacking on top of each other.
* Apply to each cell its own background div class individually


```
   
<div class="background">
  
    <div class="cell-is-col-start-2">Cell 2</div>
</div>

```
#### Do next: 
* Try and turn columns into their own rows.
* Tinker with block element(shown to add spacing) 


### 3/24/2025

##### Practicing Using Columns

* Each column can equally adjust itself no matter the amount of columns there are depending on how you set up each individual column.
* Below this, each vertically alines with each other on big screens and horizonally on smaller screens. 

```

<div class="columns">
  <div class="column">First column</div>
  <div class="column">Second column</div>
  <div class="column">Third column</div>
  <div class="column">Fourth column</div>
</div>

```

* There are ways to adjust the spacing of a column, using one of the following classes
* `is-three-quarters` `is-two-thirds` `is-half` `is-one-third` `is-one-quarter` `is-full`.
* From numbers 1-12, the grid system divids columns into 12. Size classes is `is-#1-12`
* You can use this grid system to offset the position of certain columns.

 ```
Column is half sized and is placed at one quarter of the screen
-----------------------------------------------------------------
<div class="columns is-mobile">
  <div class="column is-half is-offset-one-quarter"></div>
</div>
```

### 3/27/2025

* Today I have took a break from making my practice website and made a seperate html file to tinker with bulma elements and components seperately.
* Columns automatically stack on top of each other on mobile. Putting a `is-mobile` will prevent that.
* There are other responsiveness methods for implementing breakpoints such as:


  - `is-desktop`
  - `is-mobile`
  - `is-tablet`
  - `is-widescreen`
  - `is-fullhd`


* There are two ways to make the columns take up a certain space at a certain breakpoint.

 
 ```
Via fractions
--------------
is-three-quarters
is-two-thirds
is-half
is-one-third
is-one-quarter
is-full
```
 
```
 Via percentages
 ----------------
is-four-fifths
is-three-fifths
is-two-fifths
is-one-fifth
```



* To put a gap between columns, put `is-(1-8)`
* `is-0` will remove any gap (similar to is-gapless).
* `is-3`is the default value, equivalent to the 0.75rem value.
* `is-8` is the maximum gap of 2rem.

* `  <p class="bd-notification is-primary">` Lets larger texts in columns be vertically alined.



  ### 4/9/2025
* Reconmended to use smaller pieces of text, less than a paragraph for columns to properly align left and right `<div class="column-is-size-5 has-text-left-desktop">`.
* <div class="column is-size-2(Original size)  is-size-1-desktop(At this size at desktop px) has-text-centered">Hello World And Welcome to Website</div>
