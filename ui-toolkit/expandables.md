---
layout: page
title: Expandables
category: UI toolkit
published: true
---


- [Use](#use)
- [Style](#style)
- [States](#states)
{: class="toc"}

<div class="content-50 content-first">

Expandable sections can be used for displaying non-essential information on a page. They are also helpful for FAQ sections, schedules, and for conserving space on smaller breakpoints by collapsing secondary information. 
{: class="lead-in"}

</div>

<div class="content-50 content-last">
  <h5 class="repo-list-header">Repository</h5>
  <ul class="repo-list">
    <li>
      <span class="cf-icon cf-icon-github"></span>
    </li>
    <li>
      <a href="https://github.com/cfpb/cf-expandables"><h4>cf-expandables</h4></a>
      <p>Expandables in the Capital Framework</p>
    </li>
  </ul>
</div> 

<h2 id="use">Use<span class="cf-code-link"><a href="https://cfpb.github.io/cf-expandables/docs/">View code <span class="cf-icon cf-icon-external-link"></span></a></span></h2>

<div class="content-33 content-first">

#### Default
In the default mode, users are able to have multiple sections expanded at the same time, which allows users to easily compare information that is available in different sections.

#### Accordion
With the “accordion” mode, users can only view the contents of one section at a time: when a user expands an additional section, the previously-expanded section will collapse automatically. 

This can be desirable for maintaining the height of a group of expandable sections, but it can be disorienting when the height of the expandable sections is greater than the height of the user’s viewport (e.g., for users of mobile phones or netbooks), which can lead to off-screen sections closing and shifting all of the content on the screen. For this reason, you should avoid the “accordion” mode if the expanded height of any of the sections is greater than 400px.  

Add the data-accordion="true" attribute to the expandable group to activate the accordion mode.
 
</div>

<div class="content-67 content-last">

{::nomarkdown}  
<div class="expandable expandable__padded">
    <button class="expandable_header expandable_target">
        <span class="expandable_header-left expandable_label">
            Standard expandable title one
        </span>
        <span class="expandable_header-right expandable_link">
            <span class="expandable_cue-open">
                Show
                <span class="cf-icon cf-icon-plus-round"></span>
            </span>
            <span class="expandable_cue-close">
                Hide
                <span class="cf-icon cf-icon-minus-round"></span>
            </span>
        </span>
    </button>
    <div class="expandable_content">
        <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing
            elit. Neque ipsa voluptatibus soluta nobis unde quisquam
            temporibus magnam debitis quidem. Ducimus ratione
            corporis nesciunt earum vel est quaerat blanditiis
            dolore ipsa?
        </p>
    </div>
</div>
{:/nomarkdown}

<div class="content-67 content-last">



<h2 id="style">Style<span class="cf-code-link"><a href="https://cfpb.github.io/cf-expandables/docs/">View code <span class="cf-icon cf-icon-external-link"></span></a></span></h2>

<div class="content-33 content-first">

Standard expandables feature a colored bar, a header, the expand/collapse minicon within a circle and a label (if space allows). Ideally, the entire bar is actionable. The header should clearly indicate what the user will see when the content is expanded. It should not be a call to action.

</div>

<div class="content-67 content-last">

{::nomarkdown}  
<div class="expandable expandable__padded">
    <button class="expandable_header expandable_target">
        <span class="expandable_header-left expandable_label">
            Expandable Header
        </span>
        <span class="expandable_header-right expandable_link">
            <span class="expandable_cue-open">
                Show
                <span class="cf-icon cf-icon-plus-round"></span>
            </span>
            <span class="expandable_cue-close">
                Hide
                <span class="cf-icon cf-icon-minus-round"></span>
            </span>
        </span>
    </button>
    <div class="expandable_content">
        <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing
            elit. Neque ipsa voluptatibus soluta nobis unde quisquam
            temporibus magnam debitis quidem. Ducimus ratione
            corporis nesciunt earum vel est quaerat blanditiis
            dolore ipsa?
        </p>
    </div>
</div>
{:/nomarkdown}

</div>


<h2 id="states">States<span class="cf-code-link"><a href="https://cfpb.github.io/cf-expandables/docs/">View code <span class="cf-icon cf-icon-external-link"></span></a></span></h2>

<div class="content-33 content-first">

#### Normal
* Gray 20% bar 
* Pacific Blue minicon

</div>

<div class="content-67 content-last">

{::nomarkdown}  
<div class="expandable expandable__padded">
    <button class="expandable_header expandable_target">
        <span class="expandable_header-left expandable_label">
            Expandable Header
        </span>
        <span class="expandable_header-right expandable_link">
            <span class="expandable_cue-open">
                Show
                <span class="cf-icon cf-icon-plus-round"></span>
            </span>
            <span class="expandable_cue-close">
                Hide
                <span class="cf-icon cf-icon-minus-round"></span>
            </span>
        </span>
    </button>
    <div class="expandable_content" style="display: none;">
        <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing
            elit. Neque ipsa voluptatibus soluta nobis unde quisquam
            temporibus magnam debitis quidem. Ducimus ratione
            corporis nesciunt earum vel est quaerat blanditiis
            dolore ipsa?
        </p>
    </div>
</div>
{:/nomarkdown}

</div>

---

<div class="content-33 content-first">

#### Hover/Focus/Expanded

* Grey 50% bar
* Pacific Blue minicon

The header should be addressable by the keyboard to ensure keyboard users can open the expandable. It should match the hover state.

</div>

<div class="content-67 content-last">

{::nomarkdown}  
<div class="expandable expandable__padded expandable__expanded">
    <button class="expandable_header expandable_target">
        <span class="expandable_header-left expandable_label">
            Expandable Header
        </span>
        <span class="expandable_header-right expandable_link">
            <span class="expandable_cue-open">
                Show
                <span class="cf-icon cf-icon-plus-round"></span>
            </span>
            <span class="expandable_cue-close">
                Hide
                <span class="cf-icon cf-icon-minus-round"></span>
            </span>
        </span>
    </button>
    <div class="expandable_content">
        <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing
            elit. Neque ipsa voluptatibus soluta nobis unde quisquam
            temporibus magnam debitis quidem. Ducimus ratione
            corporis nesciunt earum vel est quaerat blanditiis
            dolore ipsa?
        </p>
    </div>
</div>
{:/nomarkdown}

</div>
