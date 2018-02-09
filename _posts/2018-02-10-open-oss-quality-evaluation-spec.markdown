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
