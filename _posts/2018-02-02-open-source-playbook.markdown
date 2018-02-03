---
layout: post
title:  "Open-source Enthusiast Playbook"
date:   2018-02-02 00:00:02 +0000
---

# Open-source Enthusiast Playbook

Welcome to the [Open-source Enthusiast Playbook](#playbook)!

Here you will discover some thoughts and principles that concern the open-source movement.
The goal of the paper is to guide your decisions about participation in the open-source development.
I'll try to show you how to make this process enjoyable, comfortable and beneficial for the community and yourself.

## <a name="problem"></a> The Problem

Everything starts with the Problem. Every day we solve a lot of problems and solve them naturally, until we encounter something that leaves us genuinely clueless. How do we go about it?

- _Research_ — we try to find an existing solution;

- _Comparison_ — once we found few solutions, we need to pick one that suits our case;

- _Application_ — we apply the chosen approach and gain experience;

- _Adjustment_ — a part of this experience can be negative if a solution does not fit entirely, so we can try to modify it;

- _Innovation_ — we can come up with an entirely new approach to solve a problem;

This is a general recipe, but it also applies to the open-source world.

Sometimes, the problem does not even exist yet and we get encounter something new out of sheer curiosity. The fact of studying it (e.g., reading an open-source project's README) already makes you a part of the OSS movement, even if you don't apply the solution to your particular needs right away.

Our enthusiasm towards a newly encountered open-source project can be measured. Let's call it Problem Empathy Axis which
starts with a Little Curiosity and ends up with a Problem Empathy.

![Problem Empathy Axis](/problem-empathy-axis.png){:class="img-responsive"}

---

## <a name="focus"></a> Innovation Focus

Take a look at the Hype Cycle chart. This is a path every new technology follows before it becomes mature and highly adopted. You can read about Hype Cycle chart stages relative to the open-source in our post on [Maturity Model](https://open-source-quality.github.io/2018/02/02/open-source-maturity-model.html).

![Hype Cycle Chart](/hype-cycle-chart.png){:class="img-responsive"}

Open-source participants around each stage of the Hype Cycle can be classified according to a focus of their interest:

- __Pioneers__ (Trigger/Hype Stage) are drawn in by a terra incognita and are willing to innovate, but often lack sophistication.
- __Settlers__ (Crystallization Stage) are thrilled by making things work and are interested in creating an infrastructure to support an existing solution.
- __Town Planners__ (Productivity Stage) focus on scale and performance which are critical to increase adoption.

No matter what problem you are trying to solve, you will fit in one of those groups and possibly move between them.

So, imagine you are looking into a problem and have already discovered several existing open-source solutions. Each of them is at a different maturity stage and you have to pick one, at least as a starting point. ave to choose one, at least
as a starting point.

In order to guide yourself in this decision, I suggest you identify yourself with one of the participants groups first
(Pioneers, Settlers, Town Planners) and then try to assess the maturity of
the solution using a [Maturity Model](https://open-source-quality.github.io/2018/02/02/open-source-maturity-model.html).
Then see if your interest and the solution's maturity match each other.

We can represent our own interest in innovation on another axis: from Innovation while still exploring a new field to Efficiency, a drive to make the solution optimized and scalable.

![Innovation Focus Axis](/innovation-focus-groups-axis.png){:class="img-responsive"}

OK, I have chosen the project. What can I do about it? What does it mean—"participate in the open-source"? You need to find your role.

---


## <a name="roles"></a> Roles

Here are some roles that exist in any open-source community:

- [__Spectators__](#spectator-playbook). Their drive is the thirst for knowledge and ideas. They play an important role in discussions and their interest propagates across the field.
- [__End-users__](#user-playbook). Their intention is to solve a problem using a tool. As a side-effect, they build a knowledge base and accumulate a problem-solving experience.
- [__Reporters__](#reporter-playbook). Their intention is to motivate a community to resolve a specific issue or expand a scope of the solution by adding some bells and whistles. As a side-effect, they build efficient communication and form requirements for a complex development process.
- [__Contributors__](#contributor-playbook). Their intention is to solve corner cases specific to their production environment. A side-effect is the experience accumulated from learning-by-doing and communicating with other engineers.
- [__Maintainers__](#maintainer-playbook). Their intention is to find the most optimal solution to a problem that concerns the project as a whole. Side-effect: knitting an intelligent and harmonious community, make friends while fighting a problem from the same trenches.

If you see yourself in one of those roles — you are ready for an exciting open-source adventure!

If you don't see yourself in that list, please open an [issue and help me expand this research research](https://github.com/open-source-quality/open-source-quality.github.io/issues).

Remember the Empathy Axis we have already discussed? It can be applied here too. Spectators are on the Curiosity side and Maintainers align with the Problem Empathy.

![Enpathy Axis](/problem-empathy-roles-axis.png){:class="img-responsive"}

Now let's put it all together!

## <a name="playbook"></a> Playbook

![Open-source Enthusiast Chart](/playbook-chart.png){:class="img-responsive"}

Let's recap the whole process.

Start with a [problem definition](#problem) and then crystallize your goal by finding your perfect spot on both axes:
- Assess your [_Empathy towards the problem_](#roles) and choose your _role_.
- Assess the [_Focus of innovation_](#focus) and choose your _focus group_.

On the intersection of those concepts you will find a perfect place for yourself in any open-source project.

Finally, I will suggest some actions you can take for each Role/Focus combination.

---

## <a name="spectator-playbook"></a> Spectator Actions Suggestion
Impact of this role on the community is highly underestimated, but it is an important entry point and a key to the community growth.
The experience is best gained by watching and analyzing the product, the process and the problem.
It is also the easiest way to participate and a nature of feedback given to Spectators is a marker of the _toxicity_ of
the community.

- __Pioneer__:
  - Discover innovations and share them in public;
  - Study the field of the problem and the demand for a solution;
  - Share the results of your analysis.
- __Settler__:
  - Analyze, discover and share requirements;
  - Learn about refactoring and quality evolution techniques;
  - Discuss a team's behavior and certain actions in public.
- __Town Planner__:
  - Extract and discuss best practices from team's collaboration;
  - Learn approaches to increase the quality of the solution;
  - Share and discuss your impressions about it;

## <a name="user-playbook"></a> End-User Actions Suggestion
This role is critical to the project's survival. A project can not be considered valuable without
quite enough End-Users involved in the verification of the solution.

- __Pioneer__:
  - Discover a new project and try to apply it in your environment;
  - Share your impressions (both positive and negative) and your experience in public.
- __Settler__:
  - Discover how the project's evolvement impacts the end-user's experience and share these discoveries in public;
  - You could also try to apply some techniques _from_ the solution in your own app and share that story too.
- __Town Planner__:
  - Explore and share how to scale using proven techniques from your practice;
  - Share and discuss the impact of optimizations in the project you depend upon;

## <a name="spectator-playbook"></a> Reporter Actions Suggestion
This role is critical to the project's growth. The feedback expressed directly to the Maintainers team
highlights critical parts of the solution and allows to better understand solution's boundaries.

- __Pioneer__:
  - Share your vision and experience directly with the the maintainers (e.g. in social or DM);
  - Share your ideas on how to solve the problems that you faced as a user with the project community.
- __Settler__:
  Share with the contributors:
  - pitfalls of existing requirements that you have encountered yourself,
  - how new features and refactoring affected your own development,
  - how to overcome difficulties.
- __Town Planner__:
  - Learn best practices in creating clear bug and feature reports;
  - Address communication issues within the project.

## <a name="contributor-playbook"></a> Contributor Actions Suggestion
Needless to say, Contributors are an essential part of the Open-source movement.

- __Pioneer__:
  - Gain some experience with the innovative tech and trending topics by contribution. Take an attempt to fix or add a feature you find critical from your fresh point of view.
- __Settler__:
  - Do some refactoring or debugging on an important part of the software infrastructure. Improve your ability to make safe changes;
  - Add source documentation, as it is necessary for the project's evolution. Help a project to become more explicit and open for contributions.
- __Town Planner__:
  The huge variety of small contribution opportunities. The project have become complex enough, so any support is welcome:
  - Docs typo fixes;
  - Document use-cases by adding various how-to/wiki articles;
  - Of course, you can choose an existing bug or open feature request and learn about the project by attempting to close it;
  - As a side-effect, you will learn about problem solving in a huge distributed team.

## <a name="maintainer-playbook"></a> Maintainer Actions Suggestion

The courage of the Maintainers leads us to our bright future. This role is pretty difficult to hold on to, as with time you will need
more and more resources to keep a project alive and move it forward. On the other hand, you have a real opportunity to find
the most optimal solution, become the core of a dedicated and intelligent community while also learning a lot about the problem you're trying to solve.

- __Pioneer__:
  Find some innovation. Whether it is a new field or a new approach to a problem:
  - You could make a prototype just to be sure that the problem has _a_ solution;
  - You could express some rationale behind a particular approach;
  - At least, you could make research other existing solutions and summarize their issues to make sure there is a space for another approach;
  - Of course, you could share your research or your prototype and discuss it in public to verify and clarify the problem boundaries.
- __Settler__:
  Congrats! This is an important moment for the projects future. Your efforts should lead the project to its balanced and stable version:
  - Refactor it, but learn how to make it safe;
  - Create automated testing environment that will help you grow sustainably;
  - Document your source code to share your knowledge, fight the bus factor;
  - Any other action that will improve the user experience.
- __Town Planner__:
  Wow! You got there. Whether you were a maintainer from the beginning or were just introduced to a core team, it is an exciting stage for the project. You already have a huge community of users. Now you can grow it even more. Encourage people to participate in your project:
  - Write clear process documentation and create templates for bug reports or feature requests;
  - Make sure that you meet the diversity criteria, introduce the Code of conduct and get rid of the toxicity;
  - Analyze what else you could do to make your community strong, open and friendly to anyone;
  - Of course, don't forget about the quality. Your core team could apply known QA techniques and maybe even invent your own.


## Good luck!
---

#### So take your action or [suggest another one](https://github.com/open-source-quality/open-source-quality.github.io/issues)!
And don't forget about some introspection.


## Introspection
At the end of your journey, it is worth to look back for a moment. Think about what have happened and what your next adventure could be.

Open-source development is a way to unite people around same interests and problems. Everyone in the community share
the same goal: find most optimal solution that will satisfy most people. Even more important is a desire to learn about software engineering in an empirical way. It is driven by curiosity, enthusiasm, and consciousness. Sometimes it is quite hard. No matter what, remember this: open-source should be about having fun and being _excited, not exhausted_.

Summarize your open-source experience by answering these questions and help projects you have participated in to become more accessible and open:

- Did I solve the problem you were trying to solve? If not, why did you stop?

- What have I learned from that experience?

- What did I find dissatisfying about the participation process? Who and how could make that experience better?

- What communication issues did I face?

- Do I want to have a similar experience in the future?

Compose a clear summary based on your answers. Add here notes about what could fix the issues that you faced.
You can also share it with the community in any way you prefer.
Sometimes it makes sense to create an issue or just DM some of the maintainers on social media.

And the last thing. You _DON'T HAVE TO_ share. An introspection makes sense on its own. It is an attempt to
clarify your intentions in the open-source community.
There is nothing wrong with leaving an open-source comminity too, sometimes even without a notice.

__Just remember to be nice and have fun!__

---

If you found any part of the document confusing or incomplete feel free to create an Issue on [GitHub](https://github.com/open-source-quality/open-source-quality.github.io/issues).
Contributions are welcome!
