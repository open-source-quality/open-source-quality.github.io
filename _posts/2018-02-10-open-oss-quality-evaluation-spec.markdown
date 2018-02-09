---
layout: post
title:  "Open-source Software Quality Evaluation Specification"
date:   2018-02-10 00:00:02 +0000
---

# Open-source Software Quality Evaluation Specification

- [Intro](#intro)
- [Entities & Relations](#entities-relations)
- [Schema & Perspectives](#schema-perspectives)
- [Metrics & Patterns](#metrics-patterns)
- [Calculations](#calculations)
- [Interpretations](#interpretation)

## <a name="intro"></a> Introduction
The rationale behind this document is to specify one of the ways to evaluate _quality_ of open-source project. As we'll see, it is much broader topic then just source code quality or tests coverage.

## <a name="entities-relations"></a> Entities & Relations
There are several entities which are the vital part of the open-source community and behavior. Let's try to list them and find some relations between.

- [Problem](#problem)
- [Organization](#organization)
- [Project](#project)
- [Participant](#participant)
- [Activity](#activity)
- [Documentation](#documentation)
- [Source Code](#source-code)

### <a name="problem"></a> Problem

#### Description
The __Problem__ describes the field or broad topic where the __Organizations__ and different __Projects__ make attempts to solve at least part of issues.

#### Variables
- Definition
- Tags

#### Invariants

#### Relations
__Problem__ has many __Projects__ and through them several __Organizations__
__Problem__ could have direct link to __Documentation__ (e.g., an article or a book)
__Problem__ could NOT have link to __Source Code__, as the last only represents some partial solution for particular __Project__ or __Organization__.

### <a name="organization"></a> Organization
#### Description
#### Variables
#### Invariants
#### Relations

### <a name="project"></a> Project
#### Description
#### Variables
#### Invariants
#### Relations

### <a name="participant"></a> Participant
#### Description
#### Variables
#### Invariants
#### Relations

### <a name="activity"></a> Activity
#### Description
#### Variables
#### Invariants
#### Relations

### <a name="documentation"></a> Documentation
#### Description
#### Variables
#### Invariants
#### Relations

### <a name="source-code"></a> Source Code
#### Description
#### Variables
#### Invariants
#### Relations


---


## <a name="schema-perspectives"></a> Schema & Perspectives
### Schema Preview
### Perspectives of research within the schema
Main perspectives for the research could be revealed by the impact the problem have on particular part of the community members.

#### User
So the most obvious one is a User perspective. It's critical for some members to solve the problem or paricular problem case, so they:
- search for existing solutions (both using some search tool or bookmarks/notes they have)
- figure out which of existing tools is most relevant as the solution (the hype also adds some point here)
- the worst case scenario - none of the existing tools fit. There we have an option to create an open-source (or sometimes not) tool (frequently it's just a one-day solution).

The consequences here:
- We have a new member of project community
- We have a new member of problem community
- Possibly, we have a new project and a new maintainer within problem community (switch of perspective)

#### Maintainer
Basically, the maintainer represent 4 roles in a project:
- an inventor of the tool (focus - RnD and MVP for some problem);
- the support team leader (focus - bug reports);
- the R&D team leader (focus - feature-fullness);
- the community leader for her way of problem solution (focus - community health and growth, collaboration efficiency).

Depending on the environment and circumstances some of those roles could be skipped.
So the perspective, give us some questions we have to answer:
- How to create an invention or innovative tool? How not to reinvent the wheel?
- How to deliver the tool as a stable product? How to persue the bug-free policy with minimum resources utilization?
- How to define the perfect scope for the tool? How to make it not too narrow and not the one that tries to solve all but necessary issues?
- Do I want to collaborate with other members who share the problem? What is the best way to interact with others? How make the process efficient? What kind of "healthy" community do I wanna grow?

So as Maintainer shares several roles at a time it the most complicated perspective. There is a high chance of developer to be overwhelmed.
So it is also a moment to think into ability to Divide and Conquer. What if we could suggest different people to solve Maintainer role?
We could even think about possibility to share Community Leader between several projects within problem area.
It make sense to unite people around the problem nor the project. There is a higher chance to survive when divercity of solutions/ways take place.

The consequences here:
- We have a member of problem community
- We have a member with several roles over one person
- The future about the project community is questionable (some maintainers want to lead a community, some of them don't)

#### Student (Curiosity-driven member)
This is one of the most undervalued member of community. At the same time, there is high chance of this community to be the biggest also.
There are no strict behavior rules or obligations for them, as nobody really count or think about them.

What's the impact they could have within community?

Mostly, it's ability to utilize their curiosity. The biggest problem in the open-source nowadays - lack of documentation (both strict or more general as posts and articles).
As the post is a way to communicate we should have a will about posts/articles/books production around both project and problem.

Questions to answer for the perspective:
- Which role play different kind of documents for the community? What kind of documenation the problem/project lacks?
- How the interest could be appreciated fot the student?
- How to share both knowledge and interest outside and inside the community?

The consequences here:
- We have a member of problem community
- Curious member is has a perspective to become a contributor/maintainer
- We have a member which is focused on knowledge extraction, which could also could share both process and fruits
- Could easily share the same role in several project. May even be interested to gather knowledge from all accessible projects within problem area
- Member lacks his own orbit in the community model. So now, it will either land in Contributors or Users or even worse outside the community

#### Donator/Investor
The role is now again not established properly. Nowdays, the behavior is mostly chaotic, so the eventually leads us to some solutions in the area.
So main problem here is how to establish money flow to the open-source communities critical for software development.

Questions to answer for the perspective:
- What kind of support is available nowadays? What is my intention to share my money with the developers?
- What amount of money could I (as person or corporate) share?
- Which projects or communities to choose as a target and why?


The consequences here:
- We have a member of problem community
- The member willing to share some money with the community to stimulate it's development
- The member could not be able to participate in the community in other roles
- The member could be a person and a corporate with different intention to their donations

---


## <a name="metrics-patterns"></a> Metrics & Patterns
For each perspective of research we have several key metrics to discuss. We'll try to answer next question to get better understanding of possible evaluation.
What impact do they have on each __Perspective__? How could we measure them? What patterns of behavior should we look for?


---


## <a name="calculations"></a> Calculations


---


## <a name="interpretations"></a> Interpretations


---


# Conclusion

If you found any part of the document confusing or incomplete feel free to create an Issue on [GitHub](https://github.com/open-source-quality/open-source-quality.github.io/issues).
Contributions are welcome!
