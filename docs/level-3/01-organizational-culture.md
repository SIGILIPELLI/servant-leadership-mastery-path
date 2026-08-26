# 01 · Organizational Culture & Servant Leadership

Everything in Levels 1 and 2 lives inside one relationship at a time — you
and a report, you and a peer, you and a difficult conversation. Culture is
what happens when nobody is watching and you aren't in the room: the
default way people in your organization treat each other, make decisions,
and handle mistakes when there's no immediate authority telling them how.
A leader who is excellent one-on-one but has no theory of culture will
build a team that behaves well near them and reverts the moment they
leave. This module covers how individual servant-leadership behavior
becomes an organizational default, a framework for diagnosing the culture
you actually have (not the one on the wall), and how to shift it without
a mandate to rewrite everyone's job description.

## 1. Culture is the sum of what gets rewarded, not what gets said

Every organization has two culture documents. One is written — values on
a slide, a mission statement, an onboarding deck. The other is unwritten:
who got promoted last year and for what, whose mistakes got forgiven and
whose didn't, what happens to the person who raises the uncomfortable
question in the all-hands. Employees learn the unwritten one in their
first month and quietly discard the written one if the two disagree.

This gives you a diagnostic question that matters more than any values
workshop: **for the last three promotions, five terminations, and any
public recognition in the last quarter, what behavior was actually
rewarded?** If the written value is "we serve our people first" and the
last promotion went to someone who hit numbers by burning through three
direct reports, the real value is numbers, and everyone in that org
already knows it — they're just not going to say so in a survey with
their name on it.

## 2. The Culture Audit

A one-page tool for finding the gap between stated and lived culture.
Run it honestly and it will be uncomfortable — that discomfort is the
signal it's working.

```text
CULTURE AUDIT

STATED VALUE: ________________________________________

EVIDENCE FOR (specific, dated, named where possible)
  - Decision or action that visibly lived this value:
  - Who was rewarded/promoted/recognized for it:

EVIDENCE AGAINST
  - Decision or action that visibly contradicted this value:
  - Who was rewarded/promoted/recognized despite contradicting it:
  - What happened to someone who tried to live the value and it cost them:

GAP SCORE (1 = fully lived, 5 = performative only): ____

IF GAP > 2, THE REAL LEVER IS:
  [ ] A promotion or hiring decision that needs to change
  [ ] A leader whose behavior contradicts the value in public view
  [ ] An incentive/metric that rewards the opposite
  [ ] A story that needs to be told about someone who paid a cost to live it
  [ ] Nothing structural — it just hasn't been named out loud yet
```

Run this on every value your organization claims, not just the ones you
personally believe in. A values statement with a gap score of 4 on three
out of five values is not a communication problem; it is a set of
incentives that need to change before the words mean anything.

## 3. How one leader's behavior becomes a team's default

Culture change at the level of a single team doesn't come from a
statement — it comes from repeated, visible, low-cost moments where you
had an easy option and a values-consistent option, and you took the
values-consistent one where people could see it.

> Rosa manages a 12-person engineering team inside a company whose stated
> value is "we don't ship blame." Two weeks after a production outage,
> the postmortem draft names the engineer who wrote the bug in the first
> paragraph.

> **Rosa (in the postmortem review):** Before we go further — pull his
> name out of the summary. Put "a change to the rate-limiter" instead.
>
> **Author of the doc:** But it's factually who wrote it. Isn't that
> just accurate?
>
> **Rosa:** It's accurate and it's also the wrong subject. The question
> this document answers is "what let this happen," not "who did it."
> Kofi wrote code that passed review, passed tests, and matched the spec
> as written — three other people signed off before it shipped. If his
> name is the headline, the actual finding — that our staging traffic
> doesn't match production load — gets buried under one person's
> discomfort, and reasonably so.
>
> **Author of the doc:** Okay. What do I put instead?
>
> **Rosa:** "The rate-limiter change was validated against staging
> traffic that is 40x lower than production. Three reviewers, including
> me, didn't catch the gap." Notice I put myself in it. If I'm asking the
> team to write blameless docs and my name is never in one, they'll
> notice that too.

The mechanism: Rosa didn't announce a new value. She intervened once, in
public, at real cost to the easy narrative, and named her own share of
it. That single edited paragraph will get repeated in Slack by people who
weren't in the room — "Rosa made them take his name out and put her own
in" travels further than any values poster.

## 4. Diagnosing the culture you have

Before trying to shift anything, name what's actually there using a
simple two-axis map: how much people trust leadership's competence, and
how much they trust leadership's intent (that leadership is actually
trying to look after them, even imperfectly).

| | Low trust in intent | High trust in intent |
|---|---|---|
| **Low trust in competence** | Cynical / disengaged — people comply and route around leadership | Anxious / overloaded — people believe you mean well but doubt you can execute, so they self-protect |
| **High trust in competence** | Wary / political — people respect the results but hide problems from you | Genuinely high-trust — people surface bad news early because neither their safety nor their respect for you is at risk |

Most teams that "have a culture problem" are actually in the anxious/
overloaded or wary/political quadrants, not the cynical one — which
matters because the fix is different. A cynical team needs proof of
intent (small, visible, costly-to-you gestures like Rosa's). A wary/
political team needs proof of competence paired with a genuine ask for
bad news, because they already believe you're capable and are protecting
themselves from your judgment, not your incompetence.

## 5. Shifting culture without formal mandate

You will rarely be handed the authority to "change the culture." What you
usually have is a team, a set of rituals you run, and repeated choices.
Three levers that don't require executive sponsorship:

- **Change what gets celebrated in the room you control.** If your
  team meeting always highlights the biggest number, spend thirty seconds
  highlighting the person who flagged a risk early instead. Repetition is
  what makes it a norm rather than a one-off.
- **Change what you personally do at cost.** Values only become believed
  when someone with something to lose visibly pays a price for them —
  admitting an error in public, giving credit away, protecting someone
  when it would be easier to let them take the hit.
- **Change the story that gets told.** Cultures run on stories more than
  policies. "Remember when Priya got promoted after the ERP failure
  because of how she ran the postmortem, not despite it" does more work
  over five years than a values deck ever will — but only if it's true.

## Exercise

Run the Culture Audit in section 2 on your own team, using one value your
organization claims to hold. Be specific: name real people, real
decisions, real dates. Score the gap honestly, even if the honest score
is uncomfortable.

Then identify one low-cost, visible, values-consistent choice you can
make in the next two weeks that you have been quietly avoiding because
the easy option was more convenient — an edit to a document, a credit
you should reassign, a piece of bad news you should surface rather than
smooth over. Make it, in public, the way Rosa did.
