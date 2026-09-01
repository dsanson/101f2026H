---
title: The Wager
date: 2026-08-31
title-slide-attributes:
  data-background-image: media/casino.jpg
  data-background-size: cover
  data-background-opacity: "0.9"
include-in-header:
  - text: |
      <style>
      #title-slide.quarto-title-block {
        background-color: rgba(255, 255, 255, 0.8);
      }
      </style>

---

# Preliminaries

## Reminders 

<!--

# Notes to self

## Pedagogy

- Focus relentlessly on the arguments.
- Allow distinctions to arise out of objections.

## Revealjs

- Consider using dynamic slides:
  - Set `contenteditable=true` for each slide
  - See [this
    site](https://www.xjavascript.com/blog/add-remove-slides-from-reveal-js-dynamically/)
    for API for creating slides on the fly.
 
---

-   use roughnotation to draw around items for focus
-   use attribution for image attribution?
-   use cascade to repeat headings
-   use agenda to automatically transform top level slides into agenda slides



-->

- Return paragraphs (no comments; didn't read them; happy to talk about them with you)
- For today, the reading was Chapter 2, "Why You Should Bet on God"
- No new reading for Wednesday.
- You should re-read the chapter after today's lecture.

# Pragmatic Arguments for Belief

## The Happiness Argument

:::{.argument}
- (GH1) You will be happier if you believe in God than if you don't.
- (GH2) You should believe whatever will make you happier.
- (GH3) So, you should believe in God.
:::

A **pragmatic** argument for belief offers a reason to believe something that is
**not about whether it is true or false**.

:::notes

Defense of GH1:

-   We live in a religious society. 
-   Nonbelievers are surrounded by believers who consider nonbelievers immoral and untrustworthy (polls regularly show that the majority of Americans think atheists are worse than rapists).
-   One of the primary forms of community is your church. 
-   These things are liable to make you less happy.
:::

## The Argument for Betting on God 

::: {.argument}
- (BG1) One should always choose the option with the greatest expected
  utility.
- (BG2) Believing in God has a greater expected utility than not
  believing in God.
- (BG3) So you should believe in God.
:::

What is expected utility?

# Expected Utility

## Insurance Costs{contenteditable=true}

I offer you a deal:

-  You pay me $200.
-  If your laptop breaks in the next year, I will pay you $100 (which you can, if you wish, use to help fix or replace it).

Should you take this deal?

:::notes
-   What if the price was $100? $50? $10? $1?
-   invite the students to play around with the price and payout.
-   invite them to articulate the point that the likelihood that your laptop will break is relevant.
:::

## Uncertain Benefits

- When a benefit is uncertain, the actual value of that benefit depends on *how
  likely* you are to receive it.
- We measure *likelihood* by assigning *probabilities*:
  -  a probability of 0 means it absolutely won't happen.
  -  a probability of .5 means it has a 50% chance of happening.
  -  a probability of 1 means it absolutely will happen.

## Expected Utility{contenteditable=true}

- **Expected Utility** is a mathematical measurement of this: multiply the value
  of the benefit by the probability---represented as a number between 0 and 1---of receiving it

-   Suppose your laptop has a 5% chance of breaking in the next year. Then the expected utility of my payout is:

    Expected Utility of Sanson's Laptop Insurance
    :   $100 $\times$ .05 = $5

-   So, if you pay $5 for my insurance, you can expect, on average, to get $5 back.

---

Actually, it's more complicated. People buy insurance because they are worried that, if something bad happens, they won't have enough money to deal with it, and so will suffer further consequences. Our analysis has not yet considered these further consequences.

Also, we haven't considered other ways you might spend that $5.

# Decision Matrices

## Factors that Matter

When you make a decision, you need to consider:

-  each action available to you. 
-  for each action, every possible outcome.
-  for each outcome, both its value to you should it occur and the likelihood of that it will occur.

To keep track of all this, we can use a **decision matrix**.

## Decision Matrix for Laptop Insurance

Should you pay $5 for my $100 insurance policy?

:::{.list-table contenteditable=true aligns="l,r,r,r"}
- - []{.dummy} 
  - Laptop breaks (5%)
  - Laptop doesn't break (95%)
  - Expected Utility
- - Buy Insurance
  - +95
  - -5 
  - ?
:::

We calculate the Expected Utility by taking the sum of the value of each outcome times its probability:

$$(95 \times .05) + (-5 \times .95)$$

---


:::{.list-table contenteditable=true aligns="l,r,r,r"}
- - []{.dummy} 
  - Laptop breaks (5%)
  - Laptop doesn't break (95%)
  - Expected Utility
- - Buy Insurance
  - +95
  - -5 
  - 0
- - Don't
  - ?
  - ?
  - ?
:::

## Decision Matrix for Laptop Insurance {.scrollable .smaller}

Instead of holding onto the $5, you could invest in GameStop...

:::{.list-table contenteditable=true aligns="l,r,r,r,r,r,r,r"}
- - []{.dummy} 
  - Laptop breaks and GameStop crashes (2%)
  - Laptop breaks and GameStop holds steady (2%)
  - Laptop breaks and GameStop goes to the moon (1%)
  - Laptop doesn't break and GameStop crashes (38%)
  - Laptop doesn't break and GameStop holds steady (38%)
  - Laptop doesn't break and GameStop goes to the moon (19%)
  - Expected Utility
- - Buy Insurance
  - ?
  - ?
  - ? 
  - ?
  - ?
  - ? 
  - ? 
- - Hold your cash
  - ?
  - ?
  - ?
  - ?
  - ? 
  - ? 
  - ?
- - Invest in GameStop
  - ?
  - ?
  - ?
  - ? 
  - ? 
  - ?
  - ?
:::

:::notes
Need more columns:

-  Laptop breaks and GameStop crashes
-  Laptop breaks and GameStop goes to the moon
-  Laptop doesn't break and Gamestop crashes
-  Laptop doesn't break and GameStop goes to the moon

Probability of combined independent outcomes is the product of probability of each.
:::

# Betting on God

## The Argument for Betting on God 

::: {.argument}
- (BG1) One should always choose the option with the greatest expected
  utility.
- (BG2) Believing in God has a greater expected utility than not
  believing in God.
- (BG3) So you should believe in God.
:::

Why believe (BG2)?

## Decision Matrix for Believing in God

:::{.list-table contenteditable=true aligns="l,r,r,r"}
- - []{.dummy} 
  - God (?%)
  - No God (?%)
  - Expected Utility
- - Believe
  - ?
  - ? 
  - ? 
- - Don't
  - ?
  - ?
  - ?
:::

:::notes

-   Start by setting probabilities at 50%.
-   Start by setting the payouts at all finite values.
-   Change the probabilities to lower probability that God exists. Note that, if it gets low enough, believe in God loses.
-   Change payout for believing in God to infinity.
:::

# Objections

## Objections Discussed in the Chapter

-   Does an infinite good even make sense?
-   How do we know the probabilities?
-   Maybe believing in God isn't enough?
-   Do we know that the value of salvation is infinite?
-   Belief in which God?
-   Belief isn't voluntary.

## Does an infinite good even make sense?

Yes, it does. Access to unlimited donuts is better than access to a finite number of donuts.

## How do we know the probabilities?

-  The probabilities don't matter! 
-  As long as the probability that God exists is some finite positive number, no matter how small, the expected utility of believing in God will be infinite.

## Maybe believing in God isn't enough? {.smaller .scrollable}

:::{.list-table contenteditable=true aligns="l,r,r,r"}
- - []{.dummy} 
  - God (?%)
  - No God (?%)
  - Expected Utility
- - Believe and Be Good
  - $\infty$ 
  - ? 
  - ? 
- - Believe and Be Bad
  - ?
  - ? 
  - ? 
- - Don't Believe and Be Good
  - ?
  - ? 
  - ? 
- - Don't Believe and Be Bad
  - ?
  - ? 
  - ? 
:::

## Do we know that the value of salvation is infinite?

:::{.list-table contenteditable=true aligns="l,r,r,r,r"}
- - []{.dummy} 
  - Generous God<br/>(?%)
  - Stingy God<br/>(?%)
  - No God <br/>(?%)
  - Expected Utility
- - Believe
  - $\infty$ 
  - ? 
  - ? 
  - ?
- - Don't Believe
  - ?
  - ? 
  - ? 
  - ?
:::


## Belief in which God? {.smaller .scrollable}

:::{.list-table contenteditable=true aligns="l,r,r,r,r,r"}
- - []{.dummy} 
  - Christian God<br/>(?%)
  - Yahweh (but not Jesus)<br/>(?%)
  - Zeus<br/>(?%)
  - No God <br/>(?%)
  - Expected Utility
- - Believe in Christian God
  - $\infty$ 
  - ?
  - ? 
  - ? 
  - ? 
- - Believe in Yahweh
  - ? 
  - $\infty$ 
  - ?
  - ? 
  - ? 
  - ? 
- - Believe in Zeus
  - ?
  - ? 
  - $\infty$ 
  - ? 
  - ? 
  - ? 
- - Don't Believe
  - ?
  - ? 
  - ? 
  - ?
  - ? 
  - ? 
:::

This yields a three-way tie. Still, the matrix shows that it is better to believe that *some* God exists than not.

## Belief isn't Voluntary

I will give you $10 if you believe that there is a sheep in the room, standing next to me.

-  Assume I can read your mind, so I know whether or not you really believe it.
-  Can you collect the $10?

## The Argument for Trying to Believe

::: {.argument}

- (TB1) One should always choose the option with the greatest expected
  utility.
- (TB2) Making an effort to believe in God has greater expected utility
  than not making an effort to believe in God.
- (TB3) So, one should make an effort to believe in God.

:::

## Decision Matrix for Trying to Believe


:::{.list-table contenteditable=true aligns="l,r,r,r"}
- - []{.dummy} 
  - God exists<br/>?
  - God doesn't exist<br/>?
  - Expected Utility
- - Try to Believe
  - ?
  - ? 
  - ? 
- - Don't Try to Believe
  - ?
  - ?
  - ?
:::

But this doesn't work. The outcome depends on whether or not you *succeed* at believing.

## Decision Matrix for Trying to Believe {.smaller}

:::{.list-table contenteditable=true aligns="l,r,r,r,r,r" }
- - []{.dummy} 
  - God +<br/> belief<br/>?
  - God +<br/> no belief<br/>?
  - no God +<br/> belief<br/>?
  - no God +<br/> no belief<br/>?
  - Expected Utility
- - Try\ to\ Believe
  - ?
  - ? 
  - ? 
  - ?
  - ?
- - Don't Try
  - ?
  - ?
  - ?
  - ?
  - ?
:::

'God' is short for 'God exists'; 'no God' for 'God does not exist'. 'belief' is short for 'you end up believing God exists'; 'no belief' is short for 'you end up not believing that God exists'.

Notice that there is a non-zero probability that you end up believing in God even if you don't try. That is interesting.
