---
layout: default
title: What are story points in agile?
page_title: Story Points
has_children: false
parent: What is Scrum? Includes best practices | Agile Library
parent_page_title: Scrum
nav_order: 4
description: Story points is commonly used by agile scrum teams as a way of estimating how much work needs to be done. Learn more about story points.
permalink: scrum/story-points/
author: Vidarth Jaikrishnan
date: March 02, 2020
modified_time: "2020-03-31T10:54:26+00:00"
publisher: Zepel
---

# Estimating with Story Points: An Overview
{: .fs-10 .no_toc }

---

## **TOPICS COVERED IN THIS GUIDE:**
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## What are story points in agile?
{: .fs-9 }

Story points are a common estimation method used by [scrum]({{ site.url }}{{ site.baseurl }}{% link agile/scrum.md %}) teams to estimate work to be done in a [sprint]({{ site.url }}{{ site.baseurl }}{% link agile/scrum-sprint.md %}). Many agile teams prefer to use story points as story point estimates offer more flexibility in structuring the backlog and sprint planning. 

Story points are representative of the amount of work or effort required to complete a particular user story or task. 

An important thing to note is that the actual numerical story point value of an item is less important than the value in relativity to other items. For instance, to say that an item A in the backlog is estimated at 5 story points, means very little. But when we say that item A is estimated at 5 and item B is estimated at 10 story points allows you to contextualise the times needed to complete tasks A and B relative to each other. 

A [backlog]({{ site.url }}{{ site.baseurl }}{% link agile/scrum-backlog.md %}) with items estimated in story points can give a reader an idea of how long each task will take with respect to each other.

---

## What to take into consideration when estimating with story points?
{: .fs-9 }

### 1. Quantity of work to be done
{: .fs-7 .no_toc }

This is the most basic consideration one has to take when estimating an item in the backlog. For instance, if the developer needs to build a popup window with a few text boxes and a subscribe button, he may estimate this item to be worth 5 story points.

![Story points when planning](/agile/assets/uploads/story-points-planning.png)
<div class="caption">
<small>Estimate in story points when planning</small>
</div>

Similarly, if the same task that has an extra thank you screen which gets displayed on clicking the button, he may estimate this item to be worth 10 or 15 story points. 

![Story points when planning](/agile/assets/uploads/estimate-with-story-points-planning.png)

It is not that adding more fields or the thank you screen makes the complexity of the task higher, it is just that the quantity of work in terms of number of screens that need to be built is more. 

Using this method, anyone reading these items from the backlog can understand that the second item requires 3 times the work to get done in order to reach completion. 

### 2. Complexity
{: .fs-7 .no_toc }

Complexity of an item is the second factor that one should consider when trying to estimate an item in story points. Let us consider the previous example of the popup dialog box. Now if someone needs to add a form to accept and store credit card details, the task becomes considerably more difficult. 

![Story points when planning](/agile/assets/uploads/complexity-story-points.png)
<div class="caption">
<small>Consider the complexity of an item during estimation</small>
</div>

It may or may not be that the amount of work to be done is (in terms of code to be written) may be that much greater than earlier but the complexity has increased multiple folds. This may require the developer to spend days or weeks figuring out how exactly the exact implementation may look from a technical standpoint. 
 
In this particular case, the developer may estimate the story at 50 or 100 points. 

### 3. Risks and challenges 
{: .fs-7 .no_toc }

The last aspect that the team should consider when estimating with story points is the risk of failure and/or challenges that may arise during implementation. 

For instance, consider a developer working on a feature where technological choices are not clear at first. He could experiment with a particular technology at first only to find that it doesn’t play well with the existing stack. There is no way for him to know this without actually implementing the code. 

However, the risk of something like this arising should be surfaced upfront and accounted for in the estimation process. 

An important thing to note is that there is no one size fits all formula for accounting for these 3 factors. The key is to find a way to factor in all 3 in a manner that accurately represents the amount of work it would take to complete the [user story]({{ site.url }}{{ site.baseurl }}{% link agile/user-stories.md %}).

<div class='mailmunch-forms-widget-883975'></div>

---

## Advantage of using story points
{: .fs-7 .no_toc }

Using man hours or days to estimate items is largely dependent on which developer is working on the item and how skilled he is. For instance, someone who has implemented a payment gateway before might need less man hours to implement the credit card popup over a developer working on it for the first time. 

The ability to estimate accurately in man hours has a direct dependence on which developer is going to be working on the item.

Now imagine if the team has to estimate and plan in advance without knowledge of who is going to work on which item. It becomes very hard to estimate the man hours required to complete the item. 

![Add estimates and due dates](/agile/assets/uploads/add-estimates-and-due-dates.png)
<div class="caption">
<small>Add estimates and due dates</small>
</div>

Estimating in terms of story points is a better approach in this scenario. The managers can, for instance, work on estimating the difficulty of the stories in points. During the [sprint planning meeting]({{ site.url }}{{ site.baseurl }}{% link agile/scrum-sprint-planning-meeting.md %}), when it is clear which developer is going to be working on which items, he or she has the flexibility to add as many stories as he wants to the sprint without having to re estimate values. 

In this scenario, the planning team estimates the user stories in story points and the development team adds due dates when the sprint is being planned. This method also surfaces developer performance more accurately than man hour estimation.

---

## Challenges of using story point estimation
{: .fs-9 }

While there are some serious advantages to using story point estimation in certain scenarios, there are also many pitfalls and situations where story point estimates are not the right approach.

![Story points estimation in Sprints](/agile/assets/uploads/estimate-story-points-sprints.png)
<div class="caption">
<small>Estimating with story points in Sprints</small>
</div>

In fact, in most scenarios estimating with man hours might be the better method. 

For starters, it is contextually harder to process story points against man hours when planning. Just looking at user stories with man hours estimation is much easier to mentally process over looking at user stories with just story points. One of the workarounds for this (as mentioned above) is to use due dates in conjunction with story points for every item on the sprint backlog. This way, actual deliverables are separated from story points which is by nature an abstract number. 

It also makes no sense to estimate by story points when the team is structured in such a way that each assignee can estimate the items he is working on right before the sprint. It is more straightforward and easier to plan a sprint when you can estimate in man hours and add items right before the sprint. 

<div class='mailmunch-forms-widget-883975'></div>

---

Choosing the correct method of estimation is essential in determining the outcome of sprint planning. Story points are slightly more complex than traditional estimation but when used in the right situations, they can not just make estimation easier but also add valuable performance insights that may otherwise be missed. 

---

<div class="highlight-row">
<div class="highlight-column">
<div class="highlight-card">
    <div class="highlight-container">
        <a href="https://zepel.io/features/sprints/?utm_source=agilelibrary&utm_medium=bottom-cta&utm_campaign=storypoints" target="_blank">
        <p class="highlight-card-title">See how you can ship quality, bug-free features with Sprints in Zepel  →</p>
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
    <a href="{{ site.url }}{{ site.baseurl }}{% link agile/scrum-backlog.md %}">
    <p class="card-title">←  Read Previous: What is a Backlog?</p> 
    </a>
  </div>
</div>
</div>

<div class="column">
<div class="card">
  <div class="container">
    <a href="{{ site.url }}{{ site.baseurl }}{% link agile/scrum-meetings.md %}">
    <p class="card-title">Read Next: Scrum Meetings  →</p>
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