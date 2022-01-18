---
layout: default
title: Governance
nav_order: 2
---

# Governance
## Governance Board
Changes to MITI require a submission via `Github Issues` with the following information:

* Scope and Field
* Summary of changes
* Example
* Implementation as a pull request

The community can discuss and vote for the submission via Github for at least 30 days.

The initial governanceboard comprises (i)  **Denis Schapiro**, PhD, Research Group Leader at the Heidelberg University (Chair); (ii) **Adam Taylor**, PhD, Senior Research Scientist, Sage Bionetworks; (iii) **Sarah Arena**, MS, Data Scientist, Harvard Medical School and (iv)  **Markus D. Herrmann**, MD, PhD, Assistant Professor of Pathology, Mass General Hospital.

This board will remain for 18 months and can be adjusted based on the community needs.

The discussions should be limited to Github and `image.sc` forum in #mcmicro.

If the implementation needs a revision, this needs to be submitted latest 30 days after acceptance.


## Meetings
MITI Governance Board meetings occur quarterly and are open to the public. Dates and times for scheduled meetings will be posted below.

### Next Meeting
*To be announced*

### Previous MITI Meeting Minutes

<ul>
    {% assign notes = site.meeting-notes | reverse %}
    {% for note in notes %}
    <li>
        <a href="{{ note.url }}">{{ note.title }}</a>
    </li>
    {% endfor %}
</ul>
