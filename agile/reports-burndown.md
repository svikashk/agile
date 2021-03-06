---
layout: default
title: Understanding Burndown Charts | Agile Library
page_title: Burndown Reports
has_children: false
parent: Understand the different types of Reports | Agile Library
parent_page_title: Reports
nav_order: 1
description: Burndown charts are a great way to visualize sprint progress. In this post we look into what a burndown chart is, what it's used for and how to read it.
permalink: reports/burndown/
author: Vidarth Jaikrishnan
date: November 26, 2018
modified_time: "2020-05-21T10:54:26+00:00"
publisher: Zepel
---

# Understanding Burndown Charts
{: .fs-10 .no_toc }

## TOPICS COVERED IN THIS GUIDE:
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## What is a burndown chart?
{: .fs-9 }

A burndown chart is a line chart drawn between "work remaining" and "time". These charts are used by scrum teams to track their progress as they “burn through” tasks in a sprint.

Burndown charts are fairly simple to understand but teams often struggle to understand the full meaning behind the graph.

---

## Parts of a burndown chart
{: .fs-9 }

![Parts of Burndown Chart](/agile/assets/uploads/burndown-chart.png)
<div class="caption">
<small>The different parts of a burndown chart</small>
</div>

### X Axis
{: .fs-7 .no_toc }

The X axis of the chart always indicates time (usually in days).

### Y Axis
{: .fs-7 .no_toc }

The y axis represents the remaining work to be done in the sprint. This may be represented by either Tasks Remaining (in # of tasks) or Remaining Effort (in Story Points/Hours).

### Progress line
{: .fs-7 .no_toc }

The progress line indicates how your team is progressing with their sprint. It gets updated every day with the new remaining estimates. As the sprint progresses, this line will indicate whether your team is on track and if any corrective action is needed.

### Guideline
{: .fs-7 .no_toc }

This is a diagonal line drawn downwards, from left to right on the graph. Your sprint progress line should ideally be as close to the guideline as possible. If your team is able to complete all stories at a steady pace throughout the sprint, your progress line will end up looking exactly like the guideline.

---

## Choosing the right metric to track
{: .fs-9 }

### Y axis as number of tasks remaining
{: .fs-7 .no_toc }

This is a plot of how many tasks remain in the sprint at any given date. As tasks are completed across time, the progress line starts moving downwards. The biggest advantage with this method is that the graph is easy to understand.

![Tasks Remaining in Burndown Chart](/agile/assets/uploads/tasks-remaining.png)
<div class="caption">
<small>Items remaining in a burndown chart</small>
</div>

The drawback of using this type of burndown chart is that tasks are not estimated. Not all tasks take equal effort to complete. Very often, teams which leave the difficult tasks for the end of the sprint find that they are unable to complete all tasks despite being “on track” for most of the duration.

---

### Y axis as story points remaining
{: .fs-7 .no_toc }

This is a plot of how many story/estimate points remain as time progresses. Story points are a great way to estimate tasks by their complexity. This normalizes effort needed to complete tasks.

![Points Remaining in Burndown Chart](/agile/assets/uploads/points-remaining.png)
<div class="caption">
<small>Points remaining in a burndown chart</small>
</div>

The plot ends up similar to the previous method but estimate points remove the ambiguity that comes with tracking task completion.

---

## When is a burndown chart useful?
{: .fs-9 }

Burndown Charts are useful during both: active sprints and sprint retrospectives.

### During the sprint
{: .fs-7 .no_toc }

Looking at the burndown chart during an ongoing sprint can help a scrum master or product owner answer the following questions:

1. Is the sprint progress on target?
1. Will all stories (or tasks) be completed on time?
1. What corrective action needs to be taken to hit targets?

### After the sprint
{: .fs-7 .no_toc }

Burndown Charts are an indicator of a Sprint team’s performance. During a sprint retrospective, burndown charts serve as a reference for discussions around estimation accuracy, sprint performance, roadblocks and changes to be made during subsequent sprints.

<div class='mailmunch-forms-widget-883975'></div>

---

## Reading the burndown graph
{: .fs-9 }

The Burndown Graph is read by comparing the sprint progress line to the guideline. The closer the two lines are to each other, the better your chances are of completing all tasks by the deadline.

![Reading a Burndown Chart](/agile/assets/uploads/reading-burndown.png)
<div class="caption">
<small>How to read a burndown chart</small>
</div>

### 1. Behind schedule
{: .fs-7 .no_toc }

If the progress line is above the guideline, it means your team is behind schedule and should have ideally completed more work by this point.

### 2. On track
{: .fs-7 .no_toc }

The progress line and the guideline are close together. The team will hit targets if they maintain their current velocity.

### 3. Ahead of schedule
{: .fs-7 .no_toc } 

The progress line is below the guideline. The team is on track to hit targets even before the sprint's end date. This may be because the tasks were overestimated while planning the sprint. The team can add more tasks to the sprint to ensure everyone is occupied throughout the sprint.

---

## Burndown chart patterns
{: .fs-9 }

Here are some common patterns you are likely to observe while using burndown charts to track sprints.

### Irregular status updates (or) Improper breakdown of stories
{: .fs-7 .no_toc }

Teams that update their statuses in chunks ( at the end of every week for example) end up with a stepped graph. Regular status updates give a more accurate graph. Ideally, Sprint teams should keep their tasks updated on a daily basis.

![Irregular updates in a Burndown Chart](/agile/assets/uploads/irregular-burndown-updates.png)
<div class="caption">
<small>A burndown chart with irregular updates</small>
</div>

A stepped graph is also sometimes the result of improper breakdown of tasks. If tasks are not broken down enough, individual issues may take a long time to complete: leading to an illusion of a lack of progress over several days. The best way to avoid this is to break down large tasks into small executable chunks of work.

---

### Progress updated at the end of the sprint
{: .fs-7 .no_toc }

![End of Sprint updates in a Burndown Chart](/agile/assets/uploads/end-of-sprint-updates.png)
<div class="caption">
<small>When updates are made at the end of the Sprint</small>
</div>

This is the burndown chart of a team that updates all their statuses a day before the sprint review meeting. This chart adds very little value during a retrospective and teams should make sure their statuses are updated daily.

---

### Well ahead of schedule
{: .fs-7 .no_toc }

This graph represents a team that overestimated the time it would take to complete tasks.

![Ahead of Schedule as per Burndown Chart](/agile/assets/uploads/ahead-burndown.png)
<div class="caption">
<small>How a burndown chart looks when you are ahead of the schedule</small>
</div>

If this team maintains their current velocity, they will end up completing all tasks well before the sprint end date. The product owner needs to add more tasks to the sprint (represented by the steep rise in the estimate), in order to keep the team busy for the entire duration of the sprint.

---

### Well behind schedule
{: .fs-7 .no_toc }

This is the burndown graph of a team that is struggling to keep up with the ideal guideline.

![Behind Schedule as per Burndown Chart](/agile/assets/uploads/behind-burndown.png)
<div class="caption">
<small>A burndown chart when the team is behind schedule</small>
</div>

This is most likely because they underestimated the effort required to complete their tasks. The two ways to correct course is to:

1. Add more people to the team (or)
1. Reduce the scope of the sprint by removing stories or tasks.

<div class='mailmunch-forms-widget-883975'></div>

---

## Limitations of burndown charts and alternatives:
{: .fs-9 }

### The Burndown Chart doesn’t actually tell you how much work is being completed by the team
{: .fs-7 .no_toc }

While the burndown chart talks about how much work is remaining, it doesn’t actually talk about how much work is being done. This data can be visualized in the form of a burnup chart, which is nothing but an inverted burndown.

Burndowns can be used for sprints only: Burndown charts don’t make much sense when they are not timeboxed. Over a long duration, the backlog goes through too many changes for remaining estimates to make much sense. This is why burndown charts aren’t recommended for Agile teams practicing Kanban methodology.

### It can be difficult to capture scope changes and visualize a changing backlog
{: .fs-7 .no_toc }

As discussed above, changes in the backlog size are not captured effectively on a burndown chart. One workaround would be to add more data to the chart but this affects the readability of the graph. These limitations of the burndown chart can be overcome by using a Cumulative Flow Diagram.

### The Burndown graph doesn’t account for “in progress” status changes
{: .fs-7 .no_toc }

Burndown Charts focus on completion of issues. Status changes during the “in progress” state aren’t captured on the burnup or burndown chart. This can often lead to the illusion that no progress is being made by the team. To account for changes in status of items in progress, [cumulative flow diagrams]({{ site.url }}{{ site.baseurl }}{% link agile/reports-cumulative-flow-diagram.md %}) or control charts can be used.

![Cumulative Flow Diagram](/agile/assets/uploads/cfd.png)
<div class="caption">
<small>A cumulative flow diagram</small>
</div>

---

## Using burndown charts effectively:
{: .fs-9 }

Burndown charts are a great way to visualize a sprint’s progress. Like all tools, scrum masters and product owners should follow a few rules to ensure that they can derive full value from Burndown Charts.

1. Spend sufficient time breaking down user stories and estimating them.
1. Ensure you are tracking the right metric for sprint progress.
1. Encourage your team to update statuses for their tasks as and when they complete them.
1. Use the burndown chart for your daily standup.
1. Wait for a few days to spot patterns before taking any corrective measures.

---

<div class="cta">
    <h2 class="cta-heading">Track progress with Agile reports</h2>
    <p class="cta-para">Use burnup, burndown, and cumulative reports to track your software development and ship better software every time.</p>
    <a href="https://zepel.io/solutions/scrum/?open_modal=true&utm_source=agilelibrary&utm_medium=bottom-cta&utm_campaign=burndownreport" class="cta-button">TRY ZEPEL FOR FREE</a>
</div>

<a href="https://zepel.io/solutions/scrum/?open_modal=true&utm_source=agilelibrary&utm_medium=bottom-cta&utm_campaign=burndownreport" class="cta-image"><img src="/agile/assets/uploads/zepel-cta-reports.png" alt="zepel burndown reports sign up button"/></a>

---

<div class="row">
<div class="column">
<div class="card">
  <div class="container">
    <a href="{{ site.url }}{{ site.baseurl }}{% link agile/reports.md %}">
    <p class="card-title">←  Read Previous: Agile Reports</p> 
    </a>
  </div>
</div>
</div>

<div class="column">
<div class="card">
  <div class="container">
    <a href="{{ site.url }}{{ site.baseurl }}{% link agile/reports-cumulative-flow-diagram.md %}">
    <p class="card-title">Read Next: Cumulative Flow Diagram  →</p>
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