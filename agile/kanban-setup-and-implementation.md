---
layout: default
title: Setting Up And Implementing Kanban | Agile Library
page_title: Setting Up And Implementing Kanban
breadcrumb_title: Setting Up And Implementing Kanban
has_children: false
parent: Kanban - An Introduction | Agile Library
parent_page_title: Kanban
nav_order: 3
description: Implementing Kanban? Here is a best practice on how to set up Kanban and implement it within your team.
permalink: kanban/setup-and-implementation/
author: Vidarth Jaikrishnan
Date: September 18, 2019
modified_time: "2020-03-31T10:54:26+00:00"
publisher: Zepel
---

# Setting Up And Implementing Kanban
{: .fs-10 .no_toc }

---

## TOPICS COVERED IN THIS GUIDE:
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Setting up your Kanban Board
{: .fs-9 }

Setting up your Kanban board is a four step process that we'll look into in detail.

**Step 1:** Capture your team’s workflow.

**Step 2:** Choose your Kanban columns to reflect the workflow.

**Step 3:** Limit Work in Progress.

**Step 4:** Track progress and make incremental improvements in the process.    

---

### Capturing your team’s workflow
{: .fs-7 .no_toc }

The first step towards implementing Kanban involves spending time gaining a deep understanding of your team’s workflow. You could ideally start by  talking to your team members and understanding how work moves across different persons, how collaboration and handoffs happen.

It is also important to define done for your particular team. This is because, very often, what is done for your team may not necessarily be the final delivery of the feature to the customer. 

The last step is to map relationships and dependencies on external stakeholders to understand how cross team collaboration happens. The aim of this exercise is to be able to build a high level process out of your team’s workflow. 

You could represent this with the help of a flowchart.

![High Level Process Overview](/agile/assets/uploads/kanban-process-overview.png)
<div class="caption">
<small>High Level Process Overview</small>
</div>

---

### Choosing Columns for your Kanban Board
{: .fs-7 .no_toc }

A common mistake that people often make when setting up the Kanban board is to have more columns than required in order to capture their workflow in great detail. This may not be the best way to set up a Kanban board. For starters, multiple consecutive columns will often be owned by the same member making moving items a pain. Not to mention, setting up WIP limits for so many columns will be a problem. 

- Try to start with a To Do (or Backlog) column which contains a list of tasks that your team may have to work on in the future.

- Setup 1 or 2 columns (max) for each person who will be working on items as part of the overall workflow.

- Let the first column for each step indicate that the item has been picked up for a particular step. 

- The second column indicates that the item has completed the particular step and is ready to be moved to the next step.

- Set WIP limits for the pair of columns in each step (wherever applicable).

- Create a single done column without WIP Limits.

- If you are unable to create a kanban board that captures your workflow accurately - the basic 4 step kanban board for software development will be the ideal place to start.

![Process visualised on a Kanban board with WIP Limits](/agile/assets/uploads/kanban-with-wip-limits.png)
<div class="caption">
<small>Process visualised on a Kanban board with WIP Limits</small>
</div>

---

### Setting Work in Progress (WIP) Limits
{: .fs-7 .no_toc }

As mentioned above, WIP limits are used by kanban teams to limit chaos. By limiting the number of items in different steps of the workflow, teams are allowed to focus on a smaller number of tasks and see them through to completion. 

- Set up WIP limits for each section separately, rather than each column. This is usually more manageable and results in better flow of items through the columns.

- A general formula that works is to take the total number of people working on a particular column and multiply that by 1.5 to arrive at the WIP limit.

- Another practical approach to setting WIP limits is to actually work without any limits and observe the performance of the team. Once individual capacity of each column is observed, WIP limits can be set. These limits can be increased or decreased later to arrive at the WIP limits that result in optimal performance. 

---

## Implementing Kanban
{: .fs-9 }

Now that your Kanban columns have been set up and WIP limits have been put in place, the last step is to populate your backlog (or whichever column comes first!). 

![A Populated Kanban Board](/agile/assets/uploads/kanban-populated.png)
<div class="caption">
<small>A Populated Kanban Board</small>
</div>

With a populated first column, your team is ready to implement Kanban. No more planning meetings are required. Assign cards to each member of the team, so they can work on continuously moving the cards through the columns. 

While your team will need to meet for demos, reviews and other unstructured meetings, the only structured meeting that your team needs to conduct are daily standups.

---

### The Daily Standup
{: .fs-7 .no_toc }

The Daily Standup meeting helps the team stay on top of their work and ensure that development is progressing smoothly. Ideally, the daily standup happens with the Kanban board open (or next to the whiteboard incase a physical board is being used). 

Any team member can run the daily standup. It is however common for team leads or managers to lead the daily standup. The most important activity is for team members to provide status updates and surface any blockers that may be hampering progress. 

The team should make sure that standup meetings start on time and do not overextend. The goal is to update the team of every individual’s progress, celebrate progress together, identify blockers and set up further meetings to address these. Try not to dig deep into individual blockers during the standup meeting. The aim is to get everyone back to work as soon as possible.

---

### Blockers
{: .fs-7 .no_toc }

A blocked item can not move to the next stage of the Kanban board because issues need to be resolved. Keeping track of blockers can surface bottlenecks in the process so the team can take corrective action. 

Here are some common blockers that Kanban teams encounter:

- Person is blocked because intermediate step is completely done.

- Person is blocked because there or no items finished in the prior step.

- Person/People are constantly getting blocked.

- Blocked due to external dependency. 

- Other issues: Long Standups, Too much process slowing the team down.

The solution to most blockers can be resolved by individuals on a collaborative basis. Sometimes blockers surface problems in the underlying process. 

For example, tracking how often items are blocked in a particular column can show whether an inefficiency in a process is a one-off occurrence or if the underlying process needs correction. 

Tracking how long items stay blocked can also reveal how efficient your process is. If blockers are taking too long to get cleared, it usually indicates a problem in the process.

Blockers are a part of every process. The aim is to monitor them and ensure that efforts are made to reduce them over time. 

---

<div class="highlight-row">
<div class="highlight-column">
<div class="highlight-card">
    <div class="highlight-container">
        <a href="https://zepel.io/features/kanban-board/?utm_source=agilelibrary&utm_medium=bottom-cta&utm_campaign=implementingkanban" target="_blank">
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
    <a href="{{ site.url }}{{ site.baseurl }}{% link agile/kanban-when-to-use.md %}">
    <p class="card-title">←  Read Previous: When to use Kanban?</p> 
    </a>
  </div>
</div>
</div>

<div class="column">
<div class="card">
  <div class="container">
    <a href="{{ site.url }}{{ site.baseurl }}{% link agile/kanban-metrics-and-charts.md %}">
    <p class="card-title">Read Next: Kanban Metrics  →</p>
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