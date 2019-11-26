---
layout: default
title: Acceptance Criteria - What Is It? Examples and Templates Included
description: Learn what acceptance criteria is. Includes how to write it for user stories with templates and examples.
page_title: Acceptance Criteria
has_children: false
parent: User Stories | How To Write | Templates And Examples Included
parent_page_title: User Stories
nav_order: 1
permalink: user-stories/acceptance-criteria/
author: Vikash Koushik
date: May 09, 2019
publisher: Zepel
---

## Acceptance Criteria For User Stories In Agile
{: .fs-9 .no_toc }

## TOPICS COVERED IN THIS GUIDE:
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## What is an acceptance criteria?
{: .fs-7 }

Acceptance criteria let you define when your user story is complete and has all the functionality needed to meet your user’s needs.

They are a set of conditions a user story should satisfy to be considered as done. It provides a detailed scope of the user story and what is needed so your team can understand what they’re up against. That way, every time you ship a new feature, you can be sure the feature meets the standard your users deserve.

But before you enthusiastically declare a set of functional criteria that should be met for your user story, consider how other variables can impact the quality of your feature as well and include them into your acceptance criteria.

**Acceptance criteria can include details like:**

- [x] User experience

- [x] The current user story’s effect on existing feature

- [x] A key performance like speed

- [x] What the user story was intended to do

So, based on the feature you are building and its complexity, sit together with your team and figure out what minimum subset of functionality it should perform and how it should behave. 

If it’s complex or a core feature of your product you should consider writing as many and detailed acceptance criteria as possible to help your team avoid any confusion.

---

## How to write acceptance criteria for user stories?
{: .fs-7 }

**1. Acceptance criteria should be written from a user's perspective.**

Acceptance criteria is a way of looking at the problem from a customer’s standpoint. It should be written in the context of a real user’s experience. After all, you are building your product for your users, right?

**2. Criteria should be clear and concise.**

Acceptance criteria should not be confused with test cases nor with documentation. It is important to keep your criteria as simple and straightforward as possible.

**3. Everyone must understand your acceptance criteria.**

Your criteria is useless if your developers can’t understand it. If you’re unsure about whether something is clear, take the time to ask and make adjustments until things are clear.

**4. Acceptance criteria is not about how. It's about what.**

Like [user stories]({{ site.url }}{{ site.baseurl }}{% link agile/user-stories.md %}), acceptance criteria is not a task. They are a technique for communicating about the user story.

**5. Acceptance criteria are specific, but are not another level of detail.**

Consider a tax filing software. The most important requirement is that it correctly calculates the due tax when incomes and expenditure are given. Obvious, right? And you know you won't be able to test all possible combinations either. Because the possibilities are nearly endless. 
    
So your acceptance criteria for the user story will specify specific conditions, or what conditions must be satisfied.

That means being more specific and not adding another level of detail.

**6. Acceptance criteria can be a restatement of user story from a user's standpoint.**

This is applicable only if the user story isn't all too complex. Here's an example of what I mean by that.

For a user story like “*As a finance officer I want to be able to accept an invoice so that I can keep a track record of all my financial statements*”. 
    
The acceptance criteria for it is as simple as “*When I perform the accept action, the invoice is accepted (check by examining the record for the invoice)*”. 

---

## Given/When/Then acceptance criteria template
{: .fs-7 }

To make life easier, here’s a simple template you can use for writing acceptance criteria:

> Given [context] when [a specific action is performed] then [a set of consequences should occur]

---

## Sample examples of acceptance criteria
{: .fs-7 }

**For the example user story:**

"As a writer, I want to receive notifications when others add comments so that I am up-to-date."

**Here are three examples of acceptance criteria for the above user story:**

1. **Given** I don't have app open **when** my phone is locked **then** I should receive a banner notification.


2. **Given** I have the app open **when** I am writing on the doc **then** the bell icon should update to show unread notifications with count.


3. **Given** a user was mentioned in a comment using @ mention **when** the mentioned user is reading the comments **then** a flash message should show up on the same comment thread with a message notifying about the new comment.

In [Zepel](https://zepel.io/?utm_source=agilelibrary&utm_medium=text&utm_campaign=acceptance-criteria), we recommend users to add all acceptance criteria as a description to the user story, so when your team members pick it up, they have the full picture of what’s required to complete the user story and its related discussions all in one place.

![Acceptance criteria for a user story in Zepel](/agile/assets/uploads/user-story-with-acceptance-criteria-in-zepel.png)

---

## Who writes acceptance criteria?
{: .fs-7 }

Pretty much anyone on the [cross-functional team](https://zepel.io/blog/cross-functional-collaboration/?utm_source=agilelibrary&utm_medium=text&utm_campaign=acceptance-criteria) can write acceptance criteria for user stories.

Most of the times it is the product owner or the product manager who writes the acceptance criteria because it is important to write it from a customer's perspective. And who better to do that than them?

---

## When should you write acceptance criteria?
{: .fs-7 }

It isn't uncommon to write the acceptance criteria for a user story while grooming the [backlog]({{ site.url }}{{ site.baseurl }}{% link agile/scrum-backlog.md %}) just before their Sprint Planning meeting. That way, they can bring it to the team during the [Sprint Planning meeting]({{ site.url }}{{ site.baseurl }}{% link agile/scrum-meetings.md %}#sprint-planning-meeting) to discuss the priorities.

Many people, however, like to discuss priorities before writing the acceptance criteria since priorities can always change based on new learnings. And by writing acceptance criteria once it has been prioritized, teams get to reduce this uncertainity and not spend time on things that aren't a priority.

This, however, isn't the right approach. While it gives the notion that you are spending time on a prioritized list of user stories, not having the acceptance criteria before prioritizing can hinder progress. 

After all, you need all the available information at your disposal to [prioritize effectively](https://zepel.io/blog/prioritize-product-feature-backlog/?utm_source=agilelibrary&utm_medium=text&utm_campaign=acceptance-criteria).

---

<div class="highlight-row">
<div class="highlight-column">
<div class="highlight-card">
    <div class="highlight-container">
        <a href="https://zepel.io/features/plan-features/?utm_source=agilelibrary&utm_medium=bottom-cta&utm_campaign=acceptance-criteria" target="_blank">
        <p class="highlight-card-title">See how you can effortlessly plan features with Zepel  →</p>
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
    <a href="{{ site.url }}{{ site.baseurl }}{% link agile/user-stories.md %}">
    <p class="card-title">←  Read Previous: User Stories</p> 
    </a>
  </div>
</div>
</div>

<div class="column">
<div class="card">
  <div class="container">
    <a href="{{ site.url }}{{ site.baseurl }}{% link agile/reports.md %}">
    <p class="card-title">Read Next: Agile Reports  →</p>
    </a>
  </div>
</div>
</div>
</div>

---

<div class="row">
  <div class="column">
    <div class="author-card">
      <img class="author-profile-image" src="/agile/assets/uploads/vikashkoushik.jpeg" alt="Vikash Koushik">
      <div class="author-card-content">
        <h4 class="author-card-name">Vikash Koushik</h4>
            <p>Product Marketing at <a href="https://zepel.io/">Zepel.io</a></p>
      </div>
    </div>
  </div>
</div>