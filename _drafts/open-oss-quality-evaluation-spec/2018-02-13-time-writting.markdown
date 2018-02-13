# 2018-02-13. Time writing. Open OSS Quality Evaluation Spec

## Intro

First of all, lets discuss the way of specification. We know that Quality term is relative. There are miriads of perspectives but
we should focus on part that has biggest influence over modern technology. What is modern technology?
It's fast growing knowledge base that gives us millions of approaches to different problems. Most of the approaches are actualy tools
with some grade of validness and various scope.
So we could outline here couple moments:
- We have problem with fast growing knowledge base, so there is a high chance of stucking with outdated solutions. Just because you're
  unable to persue all the ways technology changes.
- We have problem with huge variaty of existing solutions, so called "Choice Paralysis"
- We have problem with different grades of validity for a tool. So we often not able to understand reliablilty of the tool. Therefore we have to
  stick with old known solution and create obstacles for new tech adoption
- Last but not least is the sustainability of adopted open-source. We need to find weakest parts of ecosystem and assist them to carry the maintenance burden

So those 4 perspectives covers major issues we have on our daily basis.

Lets dive a bit deeper.

## Growing knowledge base

Whether you have any troubles at the moment or not the tech is moving. Moving fast. So we should at least be able know the directions.

So what is the Quality from this perspective?

Short answer - Innovation.

We don't have time to touch every new project being created we could though follow the most innovative solutions. Hence, we need to solve here two problems:
- Distinguish somehow Innovation from One-day living projects (as both are just RnD and have low activity)
- Have a framework for effective knowledge extraction (for both sides: maintainer - follow steps to make project more open, spectator - follow steps to discover anything interesting)

## "Choice Paralysis"

Actually, it's not the biggest and very often problem to face. Anyway we have to think about a way to compare several tools and furthermore adjustable way of making comparison.
So the Quality here is the relevance to the User issue, environment, requirements.

We also don't want to spend all day long watching charts, "stars" and reading docs. Thus we have to define requirements toolbox and just compile differents set for any User intentions.
Possible requirements/metrics:
- Maintenance capacity
- Popularity/Level of adoption/Community
- Code (Smells, Lints, Warnings...)
- Documentation

## Grades of validity

This is another side of coin when you delegate some of your load to dependent project. So Quality here is a chance to be sure in couple things:
- the project should look reliable enough to use it
- you will be able to get rid of the solution if it will show negative consequences. That does not mean you have to abandon project, but it's at least chance to notify maintainers about the problem.


So here again will be useful to have a tool for tracking your existing dependency in time and report you once in a while about warnings or possible down trends in the behavior.
What could be the reasons to remove dependency?
- Security issues
- Crossing resources limits for the dependency usage (proved by tests suite and load testing which have to be introduced)
- Drastic down trend in the maintenance capacity or behavior
- Drastic down trend in the level of adoption

## Sustainablilty

High speed of projects growth with the much less growth of developers obviously leads us to lower development resources per project. Thus as there are a lot of corporate solutions depending on open-source
we're able to capture some amount of money to increase the sustainability of mission critical projects. Of course, the amount of available income is limited so we have to deliver it only to projects which
Quality is critical for all software infrastructure. So basically we have to discover:
1. The group of most adopted software
2. Calculate Quality in terms of LTS and reliability

If we'll be able to have that data, the problem of money distribution will be simplified a ton.

