# 2018-02-14. Time writing. Open OSS Quality Evaluation Spec

## Intro

Today I gonna start from another end of the topic. What kind of specification I'm going to create?

I want to introduce the description of general concepts needed for evaluation. Those are:
- Problems we're trying to solve. Each could use only a part of the system, but on the other hand, the system should not be redundant.
- Use-case diagrams for each Problem
- Data model (database schema)
- Analytics algorithms
- Eagle eye overview of the system.

The spec should be general enough to be implemented in any DB and any language. Also, we should
agree that spec written without any implementation is sterile. So we should first create only a draft of the future spec,
then implement it and then iterate both implementation and spec.

Also, I should not make any assumptions about data I "already" know. Naturally, it will lead us to a more subjective solution.

So let's start with a brief touch over the Problems I'll attempt to solve.

## Problems

Quality evaluation (and deviations detection) is a critical feature for several open-source use cases, each of them needs a bit different approach.
Let's list them:
- Open-source as a vital part of software ecosystem (sustainability problem)
- Open-source as a shared modern toolbox for IT solutions ("choice paralysis" or applicability problem)
- Open-source as a platform to drive innovation ("hype cycle" survival guidance problem)
- Open-source as a problem-solving community initiative (efficient multi-agent system cooperation problem)
- Open-source as an a posteriori knowledge library (lack of documentation or knowledge accessibility problem)

For each problem, I have to provide several initial use cases I'll be focused on during first "validation" iterations of implementation.

### Sustainability Problem

  #### Use Case #1. Weakest members of dependencies subset
  #### Use Case #2. Sustainability warnings for the project

### Applicability Problem

  #### Use Case #3. Solutions comparison from both internal (Docs\Source) and external (Popularity index\Community behavior) perspectives
  #### Use Case #4. Guidance per project based on the Level of adoption and Warnings (absence of some data is a warning, so will focus people on the right direction!)

### "Hype Cycle" Survival Guidance Problem

  #### Use Case #4. Maturity stage detection based on the level of adoption and popularity index
  #### Use Case #5. Project driving assistance based on Risks outline and Possible optimizations in the process

### Efficient Multi-Agent System Cooperation Problem

  #### Use Case 6. Community cooperation deviations detection (overwhelmed maintainers, lack of contributor guidance, lack of user to contributor conversion)
  #### Use Case 7. Recommendations system for each Participant of community (simplification of bug/feature reports, contribution checks automation, maintenance team expansion tips)

### Knowledge Accessibility Problem

  #### Use Case 8. Different documentation types system and detection of shortage per type (based on level of adoption, as a key metric of knowledge validity)
  #### Use Case 9. Templates system for each type of document recommendations based on shortage report
