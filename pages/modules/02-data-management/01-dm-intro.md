---
title: Why a Node data management strategy
description: Build a shared understanding of why a Node data management strategy matters and what it offers to your Node.
page_id: mod_dm_1
page_img: /icons/icon-module-data-management.svg
type: Data Management
audience: [Node Coordinators, Data Stewards]
time: 60 minutes 
status: ready
sidebar: module-data-management
summary: Data management activities already exist across roles and services. The question is whether they form a coherent strategy. This section explores why a coordinated approach matters, how it supports sustainable and FAIR practices, and how to reflect on alignment, priorities and responsibilities.
related_pages:
  Real_world_example: 
  - examples-01-dm
  - funders-dm
learning_outcomes:
    - Explain why a Node data management strategy is needed to support coordination, clarity and planning 
    - Describe what a Node data management strategy includes and how it connects existing work 
    - Identify how to start developing a strategy and which roles to involve
---
{% include module-metadata.html %}

Developing a shared approach to data management is not always straightforward in a distributed environment like ELIXIR. Responsibilities are spread across roles, services and institutions. A strategy helps bring these elements together.

## Why a data management strategy matters

ELIXIR Nodes bring together many institutions, services and communities. Each group works with data in different ways. Without a shared direction, coordination becomes difficult. A strategy helps create this direction and provides clarity.

- **Direction and clarity**: A strategy shows what the Node wants to achieve in data management. It shows how services fit together and where support is still needed.
- **Efficiency and shared understanding**: It reduces duplication, improves communication and helps staff understand their roles.
- **Planning and sustainability**: A strategy supports long-term planning. It helps the Node decide which services to maintain, where to invest effort and how to respond to new demands or opportunities.

Funders and national partners often expect this kind of clarity. A strategy provides it.

{% include callout.html type="note" content="Developing a strategy is not the responsibility of a single role. It requires input from coordination, data stewardship, technical teams and user-facing support to reflect the full data landscape." %}

## What a data management strategy is and does

{% include callout.html type="note" content="A strategy is not a complex policy document. It is a simple way to bring clarity to how data is managed across the Node or institution." %}

A strategy has a few key characteristics:
- **A short, practical document**: A strategy outlines the main goals of the Node, the data landscape it serves and the principles that guide its work.
- **A way to connect existing information**: It brings together content that often exists in many places. It does not replace policies, service descriptions or Data Management Plans. It connects them.
- **Services and roles**: A strategy shows how the Node supports good data management and FAIR practices. It describes the main services, roles and communities involved.
- **A shared reference point**: It gives staff a common view of the current situation and future direction.
- **A living document**: The strategy is light and easy to update. It evolves as the Node grows, new roles appear or priorities shift. It is not a fixed plan.

## Quick exercise: mapping your strategy starting point

A strategy links existing work. Nodes often have policies, maturity assessments, training plans and service descriptions. The strategy brings these together and shows how each element contributes to the wider picture.

Before moving on, write this down. It will help you make the next steps more concrete.

1. **Think about what already exists**  
   Write down 3–5 items related to data management in your Node (e.g. policies, services, tools, training, agreements).

2. **Group them**  
   Which belong together? Are there overlaps or gaps?

3. **Reflect**  
   What feels clear and well connected? What feels fragmented or missing?

{% include callout.html type="tip" content="Compare your notes with a colleague. Do you see the same picture, or are there differences in perspective?" %}

## Quick reflection: risks without a data management strategy

Consider your current situation:

- What risks could arise if your Node continues without a data management strategy?
- Where could gaps or overlaps occur in services or support?
- What might be unclear for staff or users?

## Exercise: taking the first steps towards your strategy

Using your notes, take the first steps towards developing a data management strategy.

1. **Begin with what already exists**  
   Gather documents, notes or agreements related to data or services.  
   Which of these would you include in a first overview?

2. **Form a small working group**  
   Who would you involve to get started?  
   List 2–3 roles that should be part of an initial group.

3. **Draft a short outline**  
   Sketch a one-page outline of what your strategy could include.  
   What would be in scope, and what can wait?

{% include callout.html type="tip" content="Keep this lightweight. The goal is not to create a complete strategy, but to take a first step." %}

## Who to involve

For a basic strategy, a small but diverse group is usually enough. Consider whether you have the following roles involved:

- [ ] A **Node coordinator** to set direction and ensure alignment with national and ELIXIR priorities  
- [ ] A **data steward** or **technical staff member** with knowledge of standards, tools and workflows  
- [ ] A **support** or **training staff member** to represent user needs  
- [ ] A **community representative** to reflect the needs of researchers  




{% include callout.html type="warning" content="If only one or two perspectives are represented, important aspects of the data landscape may be missed." %}

<script>
  document.addEventListener('DOMContentLoaded', function () {
    document.querySelectorAll('.task-list-item input[type="checkbox"]').forEach(function (cb, i) {
      var key = 'task-' + window.location.pathname + '-' + i;
      cb.removeAttribute('disabled');
      cb.checked = localStorage.getItem(key) === 'true';
      cb.addEventListener('change', function () {
        localStorage.setItem(key, cb.checked);
      });
    });
  });
</script>
