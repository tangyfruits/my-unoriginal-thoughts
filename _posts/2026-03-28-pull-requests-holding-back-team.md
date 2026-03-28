---
layout: post
title: "Are Pull Requests Holding Back Your Team?"
categories: [Engineering]
source_url: "https://medium.com/better-programming/are-pull-requests-holding-back-your-team-e8aec48986c2"
---

## If You're Using Pull Requests, You Probably Aren't Doing Continuous Integration

The software industry suffers badly from Cargo Cults. Organisations and individuals are often looking so hard for those Silver Bullets that they convince themselves they will magically solve all their problems. But alas, time often isn't taken to really understand the rationale nor applicability of said bullet. The ultimate example of this is probably "Agile™"; if you're doing stand-ups and sprints you're Agile™, right? Microservices is a more recent example, and I think Continuous Integration may be another. The term "CICD" for instance is bandied about frequently but I feel the "CI" part, in particular, has lost its meaning.

## Avoidance of Accountability

**I wonder whether PRs encourage developers to feel a false sense of security, allowing us to subconsciously think we can avoid a level of accountability by shifting it onto the reviewer.**

## Pull Requests Aren't Actually That Good for Code Reviews

Pull requests are very good for quickly eyeballing code and spotting obvious mistakes, but I'm not convinced they can be relied upon for consistent in-depth scrutiny. I think it's likely that reviewers regularly only engage in System 1 thinking rather than the necessary System 2. And I confess: I am guilty of this. It typically happens when I'm busy trying to get something done before the end of the sprint and someone wants me to review their PR.

In this situation, you need to fight against your instincts of prioritising your own work over the team's collective need — which is for you to stop what you're doing and diligently scrutinise your colleagues' work. Of course, the level of diligence/scrutiny in PR reviews will vary on the level of discipline in your team, but everyone is susceptible to human nature.

## Lean Thinking?

The PR workflow generates wasted time by the potential of multiple rounds of comments and additional commits (if you're lucky enough to have a diligent reviewer). Each comment/commit added to the PR fires off an asynchronous message between author and reviewer, and a period of time follows waiting for one of them to reply. During this wait, either of them is likely to go back to working on something else. This means that when a comment/commit response is added to the PR, the same disincentive that prevents the PR from being picked up in the first place is at play: they are required to switch context to go back to the PR. I've found that because of this, open PRs can be knocking about for quite a while.
