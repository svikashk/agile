---
layout: default
seo_title: Metrics and Charts for Kanban | Agile Library
title: Metrics and Charts for Kanban
has_children: false
parent: Kanban - An Introduction
nav_order: 4
description: Want to improve processes within your agile team? Here are the metrics you should track and charts you should follow.
permalink: kanban/charts-and-metrics/
author: Vidarth Jaikrishnan
Date: September 18, 2019
---

## Metrics and Charts for Kanban
{: .fs-9 .no_toc }

---

## IN THIS PAGE
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Choosing The Right Metrics & Improving Processes Incrementally  

As a principle, Kanban focuses on incremental improvement of processes. This means that teams can opt to have a process review meeting periodically and discuss issues with the current setup and implement changes(if needed).

It is essential to track the right metrics in order to make meaningful tweaks to the setup. 

---

Here are a few metrics that teams commonly track to measure performance:

**Total Work in Progress:**

The total work in progress is the total number of items in all columns of the Kanban board outside the initial state and the completed columns. Ideally, the total work in progress remains constant. An increase in total WIP indicates that tasks are not being completed and more workload is being added. A decreasing WIP suggests a drop in performance of the team or that stories have not been broken down equally. 

Changing total WIP is a clear indicator of underlying problems in the process. The easiest way to monitor total WIP is through a cumulative flow diagram.

---

**Throughput:**

Throughput is a measure of the number of items completed by the team in any time period. It is common for teams to measure throughput on a weekly or bi-weekly basis. 

A steady, well designed process will have a steady throughput without much change.

Throughput can be measured on the cumulative flow diagram. 

---

**Lead Time and Cycle Time:**

Lead time is a measure of how long an issue takes to get resolved from when it has been created. For example, if an issue is added to the Kanban board on monday and is completed on friday, the lead time would be 5 days.  

Cycle time is the time taken by the team to resolve a ticket once someone starts working on it. 

Lead time is typically what the customer sees, while cycle time is an internal metric. 

![Lead time and cycle time](/agile/assets/uploads/lead-cycle-time.png)

---

**Task completion rate (TCR):**

TCR is a measure of the number of tasks completed on a daily basis on average. It is a rolling value that represents the work remaining for the team. 

---

**Current Task Estimate (CTE):**

The current task estimate gives you an estimate of when all the current tasks in progress will complete. This is an important metric because it represents the amount of work remaining. 

---

**Task Add Rate (TAR):**

TAR gives you the rate at which tasks are added on a daily basis. It gives you the efficiency with which the product team is able to specify items and get them ready for development.

---

## Charts for Kanban Teams

**Cumulative Flow Diagram (CFD):**
{: .no_toc }

CFD is the most popular chart used by Kanban teams. It gives you a visual overview of the entire process and shows the overall progress of the team over time. At any point in time, the CFD shows you the number of items in each column of the kanban board. 

![Cumulative Flow Diagram](/agile/assets/uploads/cfd.png)

The most common use of the CFD is to track total WIP. It can also be used to monitor other important metrics like average cycle and lead times. 

---

**Cycle Time Scatterplots**

Cycle time scatter plots show you the cycle times of individual issues as they are completed on a daily basis. This chart can be used to monitor cycle times and investigate outliers. 

Advanced versions of this chart can be used to predict completion times of issues based on historical data.

![Cycle Time Scatterplot](/agile/assets/uploads/cycle-time-scatterplot.png)

---

**Cycle Time Histogram**

The Cycle Time Histogram gives you the distribution of cycle times across issues. Ideally, you want your cycle time to be concentrated towards the left, to indicate that most tasks are completed quickly. 

A high distribution of cycle times on the histogram indicates too much unpredictability in process. 

![Cycle Distribution Chart](/agile/assets/uploads/cycle-distribution-chart.png)

---

**Ageing Chart**

The Ageing Chart shows the cycle times of different in-progress items in all the columns of the kanban board (as opposed to the cycle time of completed items). This chart gives you a view of how long each item spends in every column. 

![Ageing Chart](/agile/assets/uploads/ageing-chart.png)

---

**Throughput Chart**

The Throughput Chart shows you the amount of work being delivered by the team on a daily basis. A Throughput Histogram can be used to analyse the distribution of historical throughput rates.

![Throughput Chart](/agile/assets/uploads/throughput-chart.png)

---

<section class="author-card">
        <img class="author-profile-image" src="/agile/assets/uploads/vidarth.png" alt="Vidarth Jaikrishnan">
        <section class="author-card-content">
        <h4 class="author-card-name">Vidarth Jaikrishnan</h4>
            <p>Product at <a href="https://zepel.io/">Zepel.io</a></p>
    </section>
</section>