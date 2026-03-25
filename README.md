# My Unoriginal Thoughts

A directory of links and blog excerpts I find interesting.

## Engineering

### [How good engineers write bad code at big companies](https://www.seangoedecke.com/bad-code-at-big-companies/)

#### Old hands

To some extent, this problem is mitigated by “old hands”: engineers who happen to have been in the orbit of a particular system for long enough to develop real expertise. These engineers can give deep code reviews and reliably catch obvious problems. But relying on “old hands” has two problems.

First, this process is entirely informal. Big tech companies make surprisingly little effort to develop long-term expertise in individual systems, and once they’ve got it they seem to barely care at all about retaining it. Often the engineers in question are moved to different services, and have to either keep up their “old hand” duties on an effectively volunteer basis, or abandon them and become a relative beginner on a brand new system.

Second, experienced engineers are always overloaded. It is a busy job being one of the few engineers who has deep expertise on a particular service. You don’t have enough time to personally review every software change, or to be actively involved in every decision-making process. Remember that you also have your own work to do: if you spend all your time reviewing changes and being involved in discussions, you’ll likely be punished by the company for not having enough individual output

---

### [Weak Engineers](https://www.seangoedecke.com/weak-engineers/)

For example, there’s a hard division between engineers who can ship complex projects and engineers who can’t. It’s not as if weaker engineers do it more slowly - they just can’t seem to do it at all. Either a nearby strong engineer ghost-leads the project or the project fails.

One tactic is to avoid time-asymmetrical helping. Don’t do work for them that takes much more time than it took them to ask about it. For instance, if you’re asked “hey, I have this issue, how would you approach it”, don’t take the time to work out the actual solution and hand it to them. Fire off a quick response that points them at the next immediate step (e.g. “oh yeah, looks like something in the billing code, you should see how service X handles it”). This means they can’t spend minutes of their day tying up hours of yours.

---

### [Predators](https://www.seangoedecke.com/predators/)

Large tech companies are full of predators: people who want to extract uncompensated work from competent engineers who are generous with their time. Once a predator identifies a good target, they will routinely send work to that person via DMs instead of going through normal channels. “Uncompensated” is a key word here. When your manager asks you to do work, that isn’t predatory, because you’re being paid for it and (hopefully) rewarded for it at review time. When a colleague asks you to do work, that isn’t predatory, because they’re in a position to do you a favor as well. Predators are asking you to do work that gives them a lot of value but doesn’t do anything for you (or is even harmful). 

---

### [What makes strong engineers strong?](https://www.seangoedecke.com/what-makes-strong-engineers-strong)

#### Pragmatism

Strong engineers get things done. They bias towards working solutions. In my experience, strong engineers are all ruthless pragmatists: every design decision is judged by how well it will work, not how clean or elegant it is. That’s not to say strong engineers don’t produce elegant solutions. Elegant solutions are often the most straightforward ones. But strong engineers resist adding layers of abstraction just for neatness’ sake. They’re typically happy to make compromises in the interest of shipping.

Strong engineers don’t need to be geniuses. In fact, often genius runs counter to the skills you need to be a strong engineer. Some of the smartest people I’ve worked with - in terms of raw brainpower - were not particularly effective engineers, because they struggled with pragmatism and speed. I’d much rather work with an averagely-intelligent engineer who was unusually confident and pragmatic.

---

### [95%-ile isn't that good](https://danluu.com/p95-skill/)

#### Overwatch

At 90%-ile and 95%-ile ranks in Overwatch, the vast majority of players will pretty much constantly make basic game losing mistakes. These are simple mistakes like standing next to the objective instead of on top of the objective while the match timer runs out, turning a probable victory into a certain defeat. See the attached footnote if you want enough detail about specific mistakes that you can decide for yourself if a mistake is "basic" or not.

Some reasons we might expect this to happen are:

- People don't want to win or don't care about winning
- People understand their mistakes but haven't put in enough time to fix them
- People are untalented
- People don't understand how to spot their mistakes and fix them.

#### Practicing

Most people consider doing 30 practice runs for a talk to be absurd, a totally obsessive amount of practice, but I think Gary Bernhardt has it right when he says that, if you're giving a 30-minute talk to a 300 person audience, that's 150 person-hours watching your talk, so it's not obviously unreasonable to spend 15 hours practicing (and 30 practice runs will probably be less than 15 hours since you can cut a number of the runs short and/or repeatedly practice problem sections). One thing to note that this level of practice, considered obessive when giving a talk, still pales in comparison to the amount of time a middling table tennis club player will spend practicing.

---


### [Embrace the Suck](https://danluu.com/productivity-velocity/)

I find this a bit funny since I'm not a naturally quick programmer. Learning to program was a real struggle for me and I was pretty slow at it for a long time (and I still am in aspects that I haven't practiced). My "one weird trick" is that I've explicitly worked on speeding up things that I do frequently and most people have not. I view the situation as somewhat analogous to sports before people really trained. For a long time, many athletes didn't seriously train, and then once people started trying to train, the training was often misguided by modern standards. For example, if you read commentary on baseball from the 70s, you'll see people saying that baseball players shouldn't weight train because it will make them "muscle bound" (many people thought that weight lifting would lead to "too much" bulk, causing people to be slower, have less explosive power, and be less agile). But today, players get a huge advantage from using performance-enhancing drugs that increase their muscle-bound-ness, which implies that players could not get too "muscle bound" from weight training alone. An analogous comment to one discussed above would be saying that athletes shouldn't worry about power/strength and should increase their skill, but power increases returns to skill and vice versa.

Coming back to programming, if you explicitly practice and train and almost no one else does, you'll be able to do things relatively quickly compared to most people even if, like me, you don't have much talent for programming and getting started at all was a real struggle. Of course, there's always going to be someone more talented out there who's executing faster after having spent less time improving. But, luckily for me, relatively few people seriously attempt to improve, so I'm able to do ok.

---

## Leadership

### [Embrace the Suck](https://andrewmurphy.io/blog/embrace-the-suck)

#### The Suck is the job

I used to think good leadership meant having good conversations. Productive meetings. Aligned teams. Smooth sailing.

Lol. Nope.

Good leadership means having the conversations nobody wants to have. It means sitting across from someone and saying "this isn't working" when every cell in your body wants to say to them "it's fine, you're doing great, please don't cry."

It means telling your best engineer that their code is excellent but their attitude is poisoning the team. Telling someone you hired, someone you believed in, that they're not going to make it here. Having the same feedback conversation for the third time because they still haven't heard you.

These conversations are not fun. They are not good. They actively suck.

And they're the whole goddamn job. The suck isn't a bug in leadership. It's a feature.
