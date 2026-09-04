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

## Cross-Feast Texts Stated Once

These texts apply across sections and are not silently imported as replacement rites.

> “Three times in the year shall all your males appear before the Lord GOD.” — [Exodus 23:17 (ESV)](https://www.esv.org/Exodus+23%3A17/)

> “Three times a year all your males shall appear before the LORD your God at the place that he will choose: at the Feast of Unleavened Bread, at the Feast of Weeks, and at the Feast of Booths. They shall not appear before the LORD empty-handed.” — [Deuteronomy 16:16 (ESV)](https://www.esv.org/Deuteronomy+16%3A16/)

> “Take care that you do not offer your burnt offerings at any place that you see, but at the place that the LORD will choose in one of your tribes, there you shall offer your burnt offerings, and there you shall do all that I am commanding you.” — [Deuteronomy 12:13–14 (ESV)](https://www.esv.org/Deuteronomy+12%3A13-14/)

> “And the sons of Aaron, the priests, shall blow the trumpets. The trumpets shall be to you for a perpetual statute throughout your generations.” — [Numbers 10:8 (ESV)](https://www.esv.org/Numbers+10%3A8/)

Numbers 10:8 is a general priestly-trumpet rule. It does not add a feast-specific forever clause to Trumpet Memorial.

## Detail drafts

Detail drafts: [Passover](feasts/passover.draft.md), [Unleavened Bread](feasts/unleavened-bread.draft.md), [Wave-Sheaf / Firstfruits](feasts/wave-sheaf-firstfruits.draft.md), [Weeks / Pentecost](feasts/weeks-pentecost.draft.md), [Trumpet Memorial](feasts/trumpet-memorial.draft.md), [Day of Atonement](feasts/day-of-atonement.draft.md), [Booths / Tabernacles](feasts/booths-tabernacles.draft.md), [Eighth-Day Assembly](feasts/eighth-day-assembly.draft.md), [Weekly Sabbath](feasts/weekly-sabbath.draft.md), [New Moons](feasts/new-moons.draft.md), [Purim](feasts/purim.draft.md), and [Dedication](feasts/dedication.draft.md).

## Conclusion

Shared texts define calendar, place, and priestly limits; each [detail draft](#detail-drafts) separates explicit text, inference, and undefined questions.
