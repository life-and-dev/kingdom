---
description: A study of biblical feasts, their stated requirements, enduring clauses, and limits on modern observance.
keywords: biblical feasts, appointed times, Passover ordinance, Day of Atonement, biblical calendar limits
---

# Feasts and Comparable Observances

Shared framing, calendar limits, and cross-feast evidence. Detail drafts preserve event-specific material.

## Calendar, Counting, and Conversion Limits

### Explicit Scripture

Bible texts state a month beginning and a count. They do not identify universal calculation authority, location, time zone, lunar-visibility standard, month lengths, leap-month rule, or Gregorian conversion. For example:

> “This month shall be for you the beginning of months. It shall be the first month of the year for you.” — Exodus 12:2 (ESV)

> “In the first month, on the fourteenth day of the month at twilight, is the LORD’s Passover. And on the fifteenth day of the same month is the Feast of Unleavened Bread to the LORD; for seven days you shall eat unleavened bread.” — Leviticus 23:5–6 (ESV)

> “You shall count seven full weeks from the day after the Sabbath, from the day that you brought the sheaf of the wave offering. You shall count fifty days to the day after the seventh Sabbath. Then you shall present a grain offering of new grain to the LORD.” — Leviticus 23:15–16 (ESV)

Reported dates remain conditional on declared assumptions and different communities may observe the same feast on different Gregorian dates as a best effort to follow the same biblical text.

### Reasonable Inference

This table is reproducible conditional arithmetic, not biblical certainty. It shows why changing Abib 1, a month length, intercalation, location, time zone, lunar visibility, or Sabbath interpretation changes result.

Use these declared inputs:

- $A_y$: Gregorian date/time corresponding to Abib 1 in year $y$, under declared calendar method, location, and time zone.
- $L_{y,m}$: declared length of biblical month $m$ in year $y$.
- $B_{y,m}=A_y+\sum_{i=1}^{m-1}L_{y,i}$: month $m$, day 1.
- $W_y$: wave-sheaf day under declared Leviticus 23:15 Sabbath interpretation.
- $S_0$: known weekly-Sabbath anchor; weekly Sabbaths are $S_0+7k$, for integer $k$.

A biblical day begins at sunset or twilight, not at Gregorian midnight. Inclusive counting counts stated starting day as day 1. All outputs below are exact only under fixed declared inputs, not biblical certainty.

| Event                                                     | Start-counting conditions/anchor inputs                                                     | Formula yielding Gregorian date or range after inputs |
| --------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ----------------------------------------------------- |
| [Passover](feasts/passover.draft.md)                      | Declared $A_y$; twilight begins day 14                                                      | $A_y+13$ at twilight                                  |
| [Unleavened Bread](unleavened-bread.draft.md)             | Declared $A_y$; days 15 through 21 inclusive                                                | $A_y+14$ through $A_y+20$                             |
| [Wave Sheaf Firstfruits](wave-sheaf-firstfruits.draft.md) | Declared $W_y$ from Sabbath interpretation; harvest and land condition                      | $W_y$                                                 |
| [Weeks Pentecost](weeks-pentecost.draft.md)               | Declared $W_y$; wave day is inclusive day 1 of fifty                                        | $W_y+49$                                              |
| [Trumpet Memorial](trumpet-memorial.draft.md)             | Declared seventh-month day 1                                                                | $B_{y,7}$                                             |
| [Day of Atonement](day-of-atonement.draft.md)             | Declared seventh-month day 10; ninth evening to tenth evening                               | $B_{y,7}+9$, from ninth evening to tenth evening      |
| [Booths Tabernacles](booths-tabernacles.draft.md)         | Declared seventh-month days 15 through 21 inclusive                                         | $B_{y,7}+14$ through $B_{y,7}+20$                     |
| [Eighth Day Assembly](eighth-day-assembly.draft.md)       | Declared seventh-month day 22                                                               | $B_{y,7}+21$                                          |
| [Weekly Sabbath](weekly-sabbath.draft.md)                 | Known $S_0$; nonannual weekly cycle                                                         | $S_0+7k$, integer $k$                                 |
| [New Moons](new-moons.draft.md)                           | Declared month $m$, day 1                                                                   | $B_{y,m}$                                             |
| [Purim](purim.draft.md)                                   | Declared month-12/Adar identity and intercalation; days 14 and 15                           | $B_{y,12}+13$ and $B_{y,12}+14$                       |
| [Dedication](dedication.draft.md)                         | John 10 places it in winter; no biblical formula. Under extra-biblical Kislev 25 convention | $B_{y,9}+24$                                          |

Purim and Dedication are not Torah-appointed annual feasts.

## Pilgrimage Rules

These texts either summarise obligations spanning several feasts or state broader cultic rules.

> “Three times in the year you shall keep a feast to me.
>
> 1. You shall keep the **Feast of Unleavened Bread**. As I commanded you, you shall eat unleavened bread for seven days at the appointed time in the month of Abib, for in it you came out of Egypt. None shall appear before me empty-handed.
> 2. You shall keep the **Feast of Harvest**, of the firstfruits of your labor, of what you sow in the field.
> 3. You shall keep the **Feast of Ingathering** at the end of the year, when you gather in from the field the fruit of your labor.
>
> Three times in the year shall all your males appear before the Lord GOD.
>
> — Exodus 23:14-17 (ESV); Deuteronomy 16:16

These pilgrimage conditions does not specify a duration clause like "forever".

> “Take care that you **do not offer** your burnt offerings at any place that you see, but at **the place that the LORD will choose** in one of your tribes, there you shall offer your burnt offerings, and there you shall do all that I am commanding you.” — Deuteronomy 12:13–14 (ESV)

This pilgrimage conditions do not create sanctuary-free replacement rites. It restricts every burnt offering, including feast offerings, to the LORD’s chosen place.

## Trumpet Memorial

> The LORD spoke to Moses, saying, “Make two silver trumpets. Of hammered work you shall make them, and you shall use them for summoning the congregation and for breaking camp.
>
>...
>
> But when the assembly is to be gathered together, you shall blow a long blast, but you shall not sound an alarm. And **the sons of Aaron**, the priests, shall blow the trumpets. The trumpets shall be to you for a perpetual statute throughout your generations.
>
> And **when you go to war** in your land against the adversary who oppresses you, then you shall sound an alarm with the trumpets, that you may be remembered before the LORD your God, and you shall be saved from your enemies.
>
> On the day of your gladness also, and at your appointed feasts and at the beginnings of your months, you shall blow the trumpets **over your burnt offerings and over the sacrifices of your peace offerings**. They shall be a reminder of you before your God: I am the LORD your God.”
>
> — Numbers 10:1-2,7-10 (ESV)

Although the blowing of the trumpets was established as “a perpetual statute throughout your generations”, Numbers 10:8 assigns this duty to Aaron’s sons within Israel’s the Mosaic law system. This passage applied to literal Israelite warfare and worship by sacrificial offerings.

Certain charismatic interpretations apply “a holy priesthood” (1 Peter 2:5) and “a royal priesthood” (1 Peter 2:9) to Christians and blow a trumpet as a form of [*"worship"*](https://word.ofgod.info/terms/worship) or an expression of *"spiritual warfare"*. However, neither Numbers 10 nor 1 Peter directly commands or explicitly authorises this practice for Christians.

## Conclusion

Without an authorised sanctuary, altar, and priestly service, modern remembrance is [symbolic](https://word.ofgod.info/symbolism) rather than literal performance of these cultural commands.
