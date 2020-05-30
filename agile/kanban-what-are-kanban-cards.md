---
layout: default
title: What is a Kanban Card? | Agile Library
page_title: What is a Kanban Card
breadcrumb_title: What is a Kanban Card
has_children: false
parent: Kanban - An Introduction | Agile Library
parent_page_title: Kanban
nav_order: 1
description: A kanban card represents a single item of work in a Kanban Board. A kanban card is placed in a column to represent its current status. Learn more.
permalink: kanban/kanban-cards/
author: Vidarth Jaikrishnan
Date: January 28, 2020
modified_time: "2020-03-31T10:54:26+00:00"
publisher: Zepel
---

# Kanban Cards
{: :.fs-10 .no_toc }

---

## TOPICS COVERED IN THIS GUIDE:
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## What is a Kanban Card?
{: .fs-9 }

A kanban card represents a single item of work in a Kanban system. These cards are usually placed in a column which represents the current status of the work item. Kanban cards were originally physical cards on whiteboards but these days digital kanban cards on online project management tools are preferred. 

Initially all Kanban cards are placed on the first column of the kanban board. As these items are picked up by team members, they are moved to subsequent columns to represent the change in status of the item. Once a team member has finished a particular activity (design for example), he may move it to the next column to facilitate a handoff of the work item. 

### Kanban cards help teams in two very important ways
{: .fs-7 .no_toc }

1. They improve visibility of work and processes. The visual nature of the card makes it easy to identify, categorize and conceptualize work items. 
1. They improve collaboration and make handing off work items easy.

![A digital Kanban Board with Cards in Zepel](/agile/assets/uploads/kanban-board-with-cards-in-zepel.png)
<div class="caption">
<small><a href="https://zepel.io/" target="_blank">A digital Kanban Board in Zepel</a></small>
</div>

---

## History of Kanban Cards
{: .fs-9 }

![A Kanban Cards](/agile/assets/uploads/kanban-cards-history.jpg)
<div class="caption">
<small><a rel="noreferrer noopener" href="https://www.allaboutlean.com/toyota-kanban/toyota-kanban-cropped" target="_blank">The original Toyota Kanban Card</a>
</small>
</div>

The original Kanban board was used by Toyota to streamline manufacturing in the 1940s. The idea behind implementing Kanban was actually inspired by supermarket inventories in the US that were restocked using a Kanban-like methodology. 

This idea was transitioned into the production lines at Toyota where every step in the supply chain had a column with current items. As items were moved along, so did the card. This made it easy for anyone in the factory to understand the overall state of the supply chain and if any blockages were occuring. 

These cards on the production line were the earliest version of the modern kanban card. 
In the early 2000s there was a rapid shift in software development circles where teams were starting to move away from waterfall based development frameworks to more agile approaches. This led to teams adopting the Kanban model for software development.

---

## Physical Kanban Cards
{: .fs-9 }

![A Kanban Cards](/agile/assets/uploads/post-it-note-kanban-card.png)
<div class="caption">
<small><a rel="noreferrer noopener" href="http://www.anecon.com/blog/kanban-make-the-most-of-those-post-it-notes/" target="_blank">A post-it note kanban card</a>
</small>
</div>

The simplest Kanban boards are simple sticky notes on whiteboards with columns. These cards contained information about the work items they represented. While these boards initially represented a new paradigm in visibility and collaboration for software teams, these physical kanban boards have a few limitations: 
- A post-it note can hold only limited amount of information
- Making changes to the card usually involved creating a new post-it note
- Moving the cards between columns tends to get messy
- Searching and finding information is hard
- Physical boards work for small teams but don’t scale for large kanban teams

These restrictions with the physical kanban cards led to the rise of digital kanban software tools.

---

## Digital Kanban Cards
{: .fs-9 }

The digital kanban card is used to represent a work item in a digital kanban board. Each card has two views - one that provides the overview of the task and the other expanded view, which shows the individual task in full detail. 

### Card Overview
{: .fs-7 .no_toc }

![A Kanban Cards](/agile/assets/uploads/kanban-card-in-zepel.png)
<div class="caption">
<small>Default view of a kanban card on Zepel</small>
</div>

The minimised card is the default card that you see on the columns of the kanban board. This serves to visualise the entire workflow and show the team roughly where every active item of work stands. 

The overview should have enough information to make the card useful, without having to go into the expanded view. Some of the most common parts found in this view are: 
- **Title** of the work item
- This serves as the main identifier for a person looking to find a card.
- Item **Type** which identifies if the work item is a user story, bug, task or any other custom type of item. 
- Important **Labels** (Assignee, status, Due Date) which are the most important information that communicates the status of the item. 
- **Image/Snippet** to add another visual aid to anyone looking to scan the board while looking for something. 

The Kanban card in its default, condensed form should be able to answer what an item is, who is working on it and what the item’s current status is. 

If any card needs to be edited or more details are needed, the expanded view of the Kanban card can be used.

### Expanded View
{: .fs-7 .no_toc }

![A Kanban Cards](/agile/assets/uploads/expanded-kanban-card-in-zepel.png)
<div class="caption">
<small>Expanded Kanban Card in Zepel</small>
</div>

The expanded view is ideal when you need more information about an item or you need to edit the card. In addition to the essential fields found in the kanban card, the expanded view usually has the following sections:  
- Description to offer more details about the task. This could include essential information like test cases, edge cases and other developer notes and any other links related to the task.
- Attachments that include mockups, prototypes, flowcharts or any other documents that the assignee might need to complete the item. 
- Subtasks of the work item.
- A comment section for collaboration at a task level.

Digital Kanban Cards are convenient to use and offer teams the following advantages over their physical counterparts:  
- Digital Kanban cards can hold large amounts of information.
- It is easy to edit and replace data in digital kanban cards.
- Moving cards between columns and using the board is intuitive.
- Collaboration on boards is possible, even for remote teams.
- Searching, filtering and other tasks can be performed easily.
- Cards can be updated and viewed from a mobile device.

---

<div class="highlight-row">
<div class="highlight-column">
<div class="highlight-card">
    <div class="highlight-container">
        <a href="https://zepel.io/features/boards/?utm_source=agilelibrary&utm_medium=bottom-cta&utm_campaign=kanbancards" target="_blank">
        <p class="highlight-card-title">See how you can work together effortlessly with Boards in Zepel  →</p>
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
    <a href="{{ site.url }}{{ site.baseurl }}{% link agile/kanban-what-are-kanban-boards.md %}">
    <p class="card-title">←  Read Previous: Kanban Boards</p> 
    </a>
  </div>
</div>
</div>

<div class="column">
<div class="card">
  <div class="container">
    <a href="{{ site.url }}{{ site.baseurl }}{% link agile/kanban-when-to-use.md %}">
    <p class="card-title">Read Next: When to use Kanban?  →</p>
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