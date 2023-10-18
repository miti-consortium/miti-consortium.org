---
layout: default
title: Governance
nav_order: 2
---

# Governance
## Governance Board
The MITI governance board members are expected to respond to community feedback, participate in strategic planning, and approve changes to the governance model. The board will resolve revisions/issues for which the community cannot reach a consensus in a reasonable timeframe. This board will remain for 18 months followed by a community-based voting of a new governance board (3-5 board members). New candidates can be proposed by board members, community members, or via a direct application. We welcome and encourage participation by everyone!

As of 2023-10-18, the MITI governance board comprises (i)  **Denis Schapiro**, PhD, Research Group Leader at the Heidelberg University (Chair); (ii) **Adam Taylor**, PhD, Senior Research Scientist, Sage Bionetworks; (iii) **Sarah Arena**, MS, Data Scientist, Harvard Medical School

## Community Participation  
This is a consensus-based community standard. Anyone with an interest can join the community, contribute to the schema design and implementation, and participate in the decision-making process. Community discussions should be limited to Github and `image.sc` forum in [#mcmicro](https://forum.image.sc/tag/mcmicro).

Changes to MITI require a submission via `Github Issues` with the following information:

* Scope and Field
* Summary of changes
* Example
* Implementation as a pull request

Please reach out to the governance board with questions about how to engage in community discussions or submit revisions. If the implementation needs a revision, the community can discuss and vote for the submission via Github for at least 30 days. 

## Meetings
MITI Governance Board meetings occur quarterly and are open to the public. Dates and times for scheduled meetings will be posted below.

### Next Meeting
The next MITI meeting will take place in early September via Zoom 
*reach out to sarah_arena@hms.harvard.edu for the Zoom link*

### Previous MITI Meeting Minutes
<ul>
    {% assign notes = site.meeting-notes | reverse %}
    {% for note in notes %}
    <li>
        <a href="{{ note.url }}">{{ note.title }}</a>
    </li>
    {% endfor %}
</ul>
