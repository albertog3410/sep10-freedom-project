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
  
