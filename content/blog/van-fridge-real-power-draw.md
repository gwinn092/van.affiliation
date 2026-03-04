---
title: "How Much Power Does a Van Fridge Really Use? Real Numbers From 8 Years"
date: 2026-03-04
description: "Real measured power draw from a Dometic CFX65DZ running 24/7 across climates — Florida summer, Colorado winter, and everything in between."
featureimage: "/images/featured/power-stations.svg"
featured_image: "/images/featured/power-stations.svg"
categories: ["blog"]
tags: ["fridge", "power", "van-life", "measured"]
---

Most fridge power specs are measured in a 70°F laboratory. Your van is not a 70°F laboratory.

I've run a Dometic CFX65DZ chest fridge 24/7 for years in a black 2017 ProMaster, across Arizona summers, Colorado winters, Florida humidity, and New York fall. The difference between what the spec sheet suggests and what I've observed in real conditions is the whole point of this post.

## The Real Numbers (Measured)

| Condition | Observed Avg. Draw |
|-----------|-------------------|
| Florida summer (high ambient heat) | 20–25W/hr |
| Mild climate (spring, fall, moderate temps) | 10–12W/hr |
| Cold weather (Colorado winter) | Minimal — compressor cycles rarely |

These are observed averages from real daily use, not lab measurements. The methodology is simple: watch the watt display on the power station over time, account for other running loads, and note the baseline when the fridge is the dominant draw. Not precision-instrumented, but consistent across many observations. `Measured`

## Why the Numbers Vary So Much

The compressor in a 12V fridge doesn't run continuously. It cycles on and off to maintain the set temperature. How often it runs — and therefore how much power it draws on average — depends almost entirely on ambient temperature.

**In Florida summer:** The van interior gets hot. A black ProMaster in July can hit extreme interior temperatures that force the compressor to run almost continuously to maintain 38°F. That sustained cycle is where 20–25W/hr average comes from. The compressor isn't drawing that as a steady state — it cycles on at ~60–80W and off at 0W — but averaged over an hour in high heat, the result is 20–25Wh consumed.

**In mild conditions:** The compressor cycles more lazily. It runs, reaches target temp, stops for a stretch, runs again. In conditions around 65–70°F ambient, 10–12W/hr average reflects a compressor that's working maybe 15–20 minutes out of every hour.

**In cold weather:** In Colorado winter, I've seen the fridge draw almost nothing for extended periods. When ambient temperature is near or below the target fridge temperature, the compressor barely needs to run at all.

## Why This Matters for Power Planning

If you plan your fridge load from the manufacturer spec sheet, you'll often plan for 10–15W/hr average and think you're being conservative. In mild conditions, you might be. In Florida July in a dark van with no shade, you're undercounting by 50–100%.

This is not a hypothetical problem. In high-heat conditions, the fridge alone can consume 480–600Wh per day — before you account for laptop, fans, lights, or anything else. That's a meaningful portion of a 1,000–1,400Wh station just to keep food cold.

**Practical planning rule:** Use 15W/hr average as your baseline for fridge planning in temperate conditions. Use 25W/hr if you spend meaningful time in hot climates. Add those numbers to your other loads before sizing your power system.

## About the Dometic CFX65DZ Specifically

The CFX65DZ is a chest-style 65L compressor fridge. It's one of the established choices in the van life segment, with a good track record for durability and consistent temperature. The compressor is quiet enough to sleep through, which matters when it's cycling all night.

Its efficiency is real — 12V compressor fridges from reputable brands genuinely do draw less than their rated peak wattage on average, because the compressor cycles rather than running constantly. What varies is the cycle frequency, not the compressor efficiency.

In cold climates, it's genuinely excellent — almost free to run. In hot climates, it's doing real work and consuming real power. Plan for both.

## What I'd Consider If Buying Today

After years with the chest-style CFX65DZ, I'd seriously evaluate an upright fridge for a future build. Not for efficiency reasons — chest fridges have the efficiency advantage on paper — but for daily usability. Reaching into a chest fridge every single day for years gets old. An upright with pull-out drawers or door organization is easier to use on a daily basis, and that quality-of-life factor is real and cumulative.

The efficiency difference between a well-made upright and a chest fridge in the same size class is modest enough that I'd consider accepting it for the ergonomic improvement. `Estimate`

## Related Reading

- [How Many Watt-Hours Do I Need in a Van?](/blog/how-many-watt-hours-do-i-need/)
- [Best Fast-Charging Power Stations for Van Life](/best-of/best-fast-charging-power-stations/)
- [Stop Obsessing Over Watt-Hours](/blog/stop-obsessing-over-watt-hours/)
- [Van Life Heating on a Budget](/blog/van-life-heating-budget/)
