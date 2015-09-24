

- [Use](#use)
- [Style](#style)
- [States](#states)
{: class="toc"}

<div class="content-50 content-first">

Tabs can be used within a page to show alternate views of information and, though rarely used, as navigation between pages.  
{: class="lead-in"}

</div>

<div class="content-50 content-last">
  <h5 class="repo-list-header">Repository</h5>
  <ul class="repo-list">
    <li>
      <span class="cf-icon cf-icon-github"></span>
    </li>
    <li>
      <a href="https://github.com/cfpb/cf-expandables"><h4>cf-tabs</h4></a>
      <p>Tabs in the Capital Framework</p>
    </li>
  </ul>
</div> 

<h2 id="use">Use<span class="cf-code-link"><a href="http://cfpb.github.io/cf-expandables/docs/">View code <span class="cf-icon cf-icon-external-link"></span></a></span></h2>

We’ve identified two use cases for tabs: to show alternate views of information within a page and, though rarely used, as navigation between pages.  

### 1. To show alternate views of the same information 
<p>Consider using tabs when content needs to be separated into sections, but there’s limited visual space.</p>

<div class="content-33 content-first">

#### Use them if:
* Content for each tab is related and has a similar structure 
* The content in each tab does not have to be viewed or compared at the same time
* Tabs fit in a single row (ideally between 2 – 9 tabs)
* Tabs have short, categorical names (1-3 words)

#### Do not use if:
* Content in separate tabs needs to be compared 
* The content is long and requires scrolling inside the tab
* The content is very short or only text-based (an expandable may be more appropriate)
* You’re using tabs to show a decision (a more discrete interaction like a switch or radio button may be more appropriate)

</div>

<div class="content-67 content-last">
#### (Live Example of tabs use case 1)
</div>

---

### 2. To navigate through a process
<p>Tabs are generally not recommended for navigation, but can be used for leading users step by step through a task. Because they divide a complex task into individual steps, each chunk becomes easier to deal with because it provides a discrete “mental space” for the user, and effectively simplifies the task. None of the tabbed pages are as effective on their own as they are as part of a set.</p>

<div class="content-33 content-first">

#### Use tabs for navigation if:
* The task is long or complicated and usually novel for users
* You’re reasonably certain that we (designers, CFPB) will know more than the user about how best to get the task done
* The entire width of a page is needed for content and navigation. Testing should be done to confirm this before moving away from the left-hand navigation. 
* Tabs fit in a single row (ideally between 2 – 9 tabs)
* Tabs have short, categorical names (1-3 words)

#### Do not use them if:
* Your planned usage is due more to stakeholder desire rather than actual need
* Tabs are being used as a  progress indicator and aren’t actually clickable. (Users should be able to access any tab at any time)

</div>

<div class="content-67 content-last">
#### (Live Example of tabs use case 2)
</div>



<h2 id="style">Style<span class="cf-code-link"><a href="http://cfpb.github.io/cf-expandables/docs/">View code <span class="cf-icon cf-icon-external-link"></span></a></span></h2>

<div class="content-33 content-first">

#### Large screens
* Tabs should be equal width to fit page or column
* 60 px height
* 1 px, Gray 50% border on top, bottom and dividing lines
* 22px Avenir Next Regular (H3), left aligned, vertically centered, 30px padding-left

#### Medium and small screens
* Use <a href="http://cfpb.github.io/design-manual/ui-toolkit/expandables.html">expandables</a> styling

</div>

<div class="content-67 content-last">
#### (Example with measurements)
</div>


<h2 id="states">States<span class="cf-code-link"><a href="http://cfpb.github.io/cf-expandables/docs/">View code <span class="cf-icon cf-icon-external-link"></span></a></span></h2>

<div class="content-33 content-first">

#### Active
* White background color
* No bottom border
* 3px, Green midtone border-top
* Black type

</div>

<div class="content-67 content-last">
#### (Example of active tab)
</div>

---

<div class="content-33 content-first">

#### Hover

* White background color
* Black type

</div>

<div class="content-67 content-last">
#### (Example of tab on hover state)
</div>

---

<div class="content-33 content-first">

#### Inactive

* Gray 5% background color
* Gray 80% type

</div>

<div class="content-67 content-last">
#### (Example on inactive tab)
</div>
