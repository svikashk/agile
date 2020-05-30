---
layout: default
title: What is the Agile Software Development?
page_title: Agile Development 
nav_order: 3
has_children: false
icon_path: /assets/uploads/agile.svg
description: See what agile is for software development. Each agile framework has its own practices, terminology, and tactics. Learn more.
permalink: agile-software-development/
author: Vidarth Jaikrishnan
date: January 28, 2020
modified_time: "2020-03-31T10:54:26+00:00"
publisher: Zepel
---

# Agile Software Development
{: .fs-10 .no_toc }

---

## TOPICS COVERED IN THIS GUIDE:
{: .no_toc .text-delta }

1. TOC
{:toc}
---

## What is Agile Software Development?
{: .fs-9 }

Agile Software Development frameworks or agile methodologies as they are otherwise known, comprise of software development frameworks that rose to prominence in the early 2000s. 

These frameworks were derived from a document known as the Agile manifesto. [The Agile Manifesto]({{ site.url }}{{ site.baseurl }}{% link agile/manifesto.md %}) has a set of values and principles that aimed to make software development more flexible and help teams incorporate change into product requirements during the development process. 

The term agile can be viewed as an umbrella term for a variety  of development methodologies that incorporate the principles of the Agile manifesto. Some of the most common Agile frameworks used by teams today include frameworks such as [scrum]({{ site.url }}{{ site.baseurl }}{% link agile/scrum.md %}), [kanban]({{ site.url }}{{ site.baseurl }}{% link agile/kanban.md %}), lean, extreme programming, and feature driven development (FDD). 

---

## Different Agile Frameworks
{: .fs-9 }

## 1. Scrum
{: .fs-9 }

Scrum is a popular agile framework that focuses on shipping usable software incrementally in short cycles. These cycles usually vary from a couple of weeks to a month.

### Overview 
{: .fs-7 .no_toc }

A scrum team is usually cross functional in nature. It consists of a development team which includes QA and design experts if needed. In addition to the developers, there are specialised roles such as the product owner and scrum master who form part of the scrum team. 

The team scopes down the product to create a sprint (which may last a few weeks). The 	aim is to develop a usable component every sprint and continue to incrementally develop components in further sprints. These components come together to form a feature-complete product. 

Scrum aims to make the product development process more dynamic and makes it easy to incorporate changes in requirements. Also, as testing happens every sprint, the quality of software being developed is much higher. 

### Some major advantages of using Scrum
{: .fs-7 .no_toc }

- Large products can be divided into sprints which are more easily manageable. 
- Scrum makes it easy to incorporate changes in the product during the development process.
- Scrum focuses on estimation which helps improve visibility and predictability of shipping features.
- Cross functional teams usually face less roadblocks due to the collaborative nature of work.
- Scrum has a wide range of metrics that can be tracked to improve performance.

### Challenges Scrum teams may face
{: .fs-7 .no_toc }

- Getting started with scrum is usually much harder as it requires time and effort to be invested in bringing teams up to speed with concepts of SCRUM.
- As it is drastically different from traditional waterfall based methods, teams may be uncomfortable working with sprints at first. 
- Scrum teams required specialised roles such as product owners, scrum masters and coaches.
- Teams usually struggle with estimation when they get started with SCRUM. This leads to missed targets and is often demoralizing for teams. 

<div class="highlight-row">
<div class="highlight-column">
<div class="highlight-card">
    <div class="highlight-container">
        <a href="{{ site.url }}{{ site.baseurl }}{% link agile/scrum.md %}">
        <p class="highlight-card-title">Learn in-depth about Scrum along with its best practices →</p>
        </a>    
    </div>
</div>
</div>
</div>


---

## 2. Kanban
{: .fs-9 }

The Kanban methodology is an agile framework that focuses on visualising a team's workflow to surface bottlenecks and deal with them. 

### Overview
{: .fs-7 .no_toc }

Kanban focuses on creating a kanban board with columns representing the status. Items are then mapped onto the board in their respective columns. As the team works on and complete their respective items, they move these items to subsequent columns.

The focus of Kanban is to focus on one item and finish it completely before starting to work on another item. This helps prevent distractions and improve the focus of the team. 

Kanban teams restrict the number of items in each column (called work in progress limiting). This prevents teams from adding new items without finishing old ones first. 

Columns that are constantly at maximum capacity prevent the team from adding new items. Teams can identify blockers and improve their process when this happens.

### Some major advantages of using Kanban
{: .fs-7 .no_toc }

- Kanban is one of the easiest agile frameworks to implement. 
- Kanban boards drastically improve visibility of work without changing any existing processes.
- Kanban requires minimal team restructuring and can work for all kinds of teams.
- Features/user stories are continuously deployed in Kanban. 

### Challenges with using Kanban
{: .fs-7 .no_toc }

- Kanban puts less emphasis on testing(as opposed to some of the frameworks like SCRUM). The onus is on the team to identify a workflow that ensures that highest quality is maintained. 
- Kanban teams sometimes suffer from large lead/cycle times.
- Kanban might not be a great fit for teams that need to completely revamp their process as it focuses on incremental improvement. 

<div class="highlight-row">
<div class="highlight-column">
<div class="highlight-card">
    <div class="highlight-container">
        <a href="{{ site.url }}{{ site.baseurl }}{% link agile/kanban.md %}">
        <p class="highlight-card-title">Learn in-depth about Kanban along with its best practices →</p>
        </a>    
    </div>
</div>
</div>
</div>


---

## 3. Lean Development
{: .fs-9 }

### Overview 
{: .fs-7 .no_toc }

Lean Software Development (LSD Framework) is an agile approach that focuses on building and market testing a product via an MVP. It is otherwise known as the MVP Framework.

Lean software teams scope down the product to remove all the nice-to-have features and focus on building the bare bones functionality. This is then sent out to the customers to be tested. The team moves on to building the next part of the software only if results and market feedback are satisfactory. 

If the MVP fails to move the needle, the teams goes back to the drawing board to build and release a new MVP.

Is the LSD framework a good fit for your team?
- Lean is one of the least scalable agile frameworks. 
- It is a great fit for teams working on products with a high risk of failure. This is why lean practices are encouraged in early stage startups with little or no traction in the market. 

### Advantages of Lean Development
{: .fs-7 .no_toc }

- Lean development is highly flexible. It doesn’t have many rules except for the overall approach towards building MVPs.
- It can be implemented quickly regardless of how small the team is.
- It eliminates unnecessary requirements and helps the team focus on building only what matters.

### Disadvantages of Lean Development
{: .fs-7 .no_toc }

- LSD framework is probably the least scalable agile methodology. It can not be used for mature products.
- The constant iteration and focus on building MVPs could sometimes slow overall product progress. 

---

## 4. Extreme Programming
{: .fs-9 }

### Overview
{: .fs-7 .no_toc }

Extreme Programming (XP) is an agile software development methodology that aims to help teams develop high quality software, as efficiently as possible. Like scrum, it also seeks to make it possible to incorporate changing customer requirements during development cycles. 

At its core, XP is focused on developing software through iterations but focusing on retrospecting with the aim to find out what works. Once a positive practice has been identified in the retrospective, XP recommends the team to take this practice to extreme levels during the next iterations. 

Some examples of best practices that XP teams have been known to focus excessively on are: 
- Design
- Simplicity
- Code Review
- Incremental Development
- Integration Testing

### Advantages of XP
{: .fs-7 .no_toc }

- Increased focus on shipping software on time is a core value of XP. Teams make decisions of best practices around the timely delivery of working software.
- XP encourages constant feedback on not only the product but also the process being used.
- Best practice review for QA processes are also encouraged at the end of every iteration. This ensures that high quality software is delivered.

### Disadvantages of XP
{: .fs-7 .no_toc }

- There is a constant focus on retrospectives and meetings which may not suit all kinds of teams.
- Extreme Programming is better suited for teams that are in the same location. Remote teams may have a tough time collaborating in an XP environment. 

---

## 5. Feature Driven Development (FDD)
{: .fs-9 }

### Overview of FDD
{: .fs-7 .no_toc }

Feature driven development (FDD) is an agile framework that recommends building software products by breaking them down into features. Features in an FDD context are similar to user stories in the scrum framework. 

An agile team following an FDD framework goes about building the product in 5 steps :
1. Develop an overall model of the product
1. Create a feature list
1. Plan the features one by one
1. Design each feature
1. Develop Each feature

### Advantages of FDD
{: .fs-7 .no_toc }

- FDD is fairly straightforward to implement. It offers an overall agile framework, built around features and expects the team to implement best practices around it.

- It breaks down the product into smaller chunks and forces the team to focus and complete each feature separately. 
Once features are specified, teams can implement best practices from other frameworks and use what suits their team the best. 

### Disadvantages of FDD
{: .fs-7 .no_toc }

- There is a heavy reliance on the team member who is developing the initial overall model of the product.
- There is not much focus on documentation. 
- It may be difficult for very small teams to fully adopt FDD. 

---

<div class="highlight-row">
<div class="highlight-column">
<div class="highlight-card">
    <div class="highlight-container">
        <a href="https://zepel.io/?utm_source=agilelibrary&utm_medium=bottom-cta&utm_campaign=agilemanifesto" target="_blank">
        <p class="highlight-card-title">Looking to implement Agile within your organization? Try Zepel for Free  →</p>
        </a>    
    </div>
</div>
</div>
</div>

---

<div class="row">
<div class="column">
<div class="card">
  <div class="container">
    <a href="{{ site.url }}{{ site.baseurl }}{% link agile/manifesto.md %}">
    <p class="card-title">← Read Previous: Agile Manifesto</p> 
    </a>
  </div>
</div>
</div>

<div class="column">
<div class="card">
  <div class="container">
    <a href="{{ site.url }}{{ site.baseurl }}{% link agile/scrum.md %}">
    <p class="card-title">Read Next: What is Scrum?  →</p>
    </a>
  </div>
</div>
</div>
</div>

---

<div class="row">
  <div class="column">
    <div class="author-card">
      <img class="author-profile-image" src="/agile/assets/uploads/vidarth.png" alt="Vidarth Jaikrishnan">
      <div class="author-card-content">
        <h4 class="author-card-name">Vidarth Jaikrishnan</h4>
        <p>Product at <a href="https://zepel.io/">Zepel.io</a></p>
      </div>
    </div>
  </div>
</div>