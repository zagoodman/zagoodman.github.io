---
layout: post
title:  "Endurance Thermodynamics: how much fuel do you need?"
author: zack
categories: false
image: '/assets/images/2021/imthermo/cradle.jpg'
description: "Calculating macronutrient needs in an Ironman"
featured: false
hidden: true
---

I remember being blown away after hearing Michael Phelps consumed 12,000 calories a day in his build up to the Olympics in 2008. [It turns out](http://www.thepostgame.com/michael-phelps-debunks-12000-calorie-diet-myth) the real amount was "only" 8,000 - 10,000, or about 4-5 times the RDA for your average non-Olympian.

10,000 calories seems like a lot - and it is for most people - but I was surprised...

## How many Ironmans on just bodyfat?

On any given day I weigh somewhere around 175 pounds, 10% of which is bodyfat. Let's make the math easy and assume I have about 10 pounds of bodyfat I could use as fuel before risking serious medical complications (not that I'd want to do this - it's just a thought experiment).

People often assume a pound of bodyfat contains 3,500 kcal. A pound of olive oil contains just shy of 4,000 kcal. Bodyfat contains fewer calories because bodyfat contains cellular matter in addition to the calorie-laden lipids. That said, the actual caloric content of any given person's bodyfat will vary, probably in the range of 3,500 - 4,000 kcal. Let's be pessimistic and assume our 20 pounds of bodyfat contains 3,500 usable calories per pound, or 70,000 calories.

Next we need to figure out how many calories it takes to complete an Ironman.

### Calculating calories burned using a power meter

> The Law of Conservation of Energy: energy can neither be created nor destroyed; it can only be changed or transferred from one form to another.

With modern technology like power meters, we can more accurately estimate the total mechanical work done by one's body while exercising. And since that energy had to come from somewhere (i.e., food or fat stores), we can estimate how many calories you would have had to consume to produce said mechanical work.

The math is pretty straightforward:

`Food energy (kcal) = Power (W) * Time (s) * 0.000239 (kcal / J) * 1/efficiency (%)`

We start with `Power * Time`, a measure of total energy required to propel the bike, with units of `J` (Joules). Next we convert Joules to kcal. At this point, we've calculated the calories required if our metabolic engines were 100% efficient. Alas, we can at best convert [about 25%](https://link.springer.com/article/10.1007/s00421-010-1410-1) of food calories to useful mechanical work, so we'll need to multiply by 4 to get the minimum food energy required.

### Caloric need during an Ironman

Let's calculate the energy requirements for someone my size who finishes in:
1. 10 hours, considered a competitive time for age group athletes, and
2. 17 hours, the cutoff time for the Ironman.

To finish in 10 hours, a typical Ironman athlete will spend about 1 hour swimming, 5.5 hours cycling, and 3.5 hours running. Here's how caloric demand breaks down:

_Cycling_
We'll do this one first because it's the easiest to calculate. Covering 112 miles in 5.5 hours requires a pace of 20.4 mph. With minimal elevation gain, light winds, no braking, and [reasonable assumptions](https://www.gribble.org/cycling/power_v_speed.html) about losses to drag, drivetrain friction, and rolling resistance, someone my size has to supply about 210 watts to sustain 20.4 mph. Using our equation above, 210 watts for 5.5 hours requires 3,975 kcal, or about 4,000 kcal.

_Running_
Short of visiting a [lab](https://sites.udel.edu/coe-engex/2018/03/07/how-it-works-direct-calorimetry/), calculating energy need for running is less of an exact science. There doesn't exist a strain-based power meter for running like there does for cycling, though [one company](https://www.stryd.com/en/) claims to estimate "running power" using a wearable foot pod.





All energy expended while exercising came from somewhere, usually from energy stored in the food we consume or the fat we carry.





## Fueling to avoid the bonk

In the endurance world, "bonking" or "hitting the wall" is when one's athletic performance deteriorates at the hands of insufficient fuel availability. Contrary to what some believe is your body "running out of fuel", bonking is a survival adaptation that triggers long before your body is completely out of fuel.

Though in theory you could run out of bodyfat, as we discuss earlier most people carry enough bodyfat to complete several Ironmans. Hence, the substrate to blame for the bonk is typically glucose.

Our bodies are like tanker trucks. We carry with us a massive reserve fuel source - bodyfat - as well as a much smaller but generally more easily accessible gasoline tank: our glycogen reserves. Whereas our bodyfat can carry us through several Ironmans, our glycogen reserves in our muscles and our liver combine to about 2,000 calories max, or about a quarter of an Ironman.

[insert pic of tanker truck]

Avoiding the bonk is about keeping that glycogen tank far from empty, which is why most athletes eat during long competitions. How much do you have to eat to avoid bonking during an Ironman?

### Fueling for carb- vs fat-adapted athletes

Most athletes are carb-adapted as it's the food atmosphere most of us are raised in. Carb-adapted athletes' bodies have been trained to use carbohydrate, and hence performance is maximized when glucose is readily available during competition. On the other hand, fat-adapted athletes use fat as their primary fuel and depend less on glucose mid-race.

[Research](https://www.sciencedirect.com/science/article/pii/S0026049515003340) reveals how much of an impact food environment plays on substrate use. At 70% of VO2 max, which is approximately the Ironman effort level for many competitive age group athletes, the carb-adapted study participants sourced about 25% of their calories from fat whereas the fat-adapted participants sourced nearly 80% of their calories from fat.

How does this translate into fueling for an Ironman?

_Carb-adapted athlete_: Given the 10 hour example at 8,000 calories, a carb-adapted athlete would burn about 6,000 kcal of carbohydrate and 2,000 kcal of fat. Assuming he could use up to ~1,500 kcal of stored glycogen before bonking, he'd need to eat 4,500 kcal over the course of the race, or about 450 kcal per hour. To keep his glycogen levels full, he'd need to consume 600 kcal per hour.

At 4 kcal per gram, 450 kcal translates to 112 grams of carbohydrate per hour, which is getting into the [danger zone](link) for GI distress. The intestinal tract can only absorb so much carbohydrate over time, though some tactics like using liquid sources and mixing different kinds of carbohydrate can help speed up absorption.

_Fat-adapted athlete_: In the same race, the fat-adapted athlete would burn about 6,400 kcal of fat and only 1,600 kcal of glucose. This athlete could probably get away with not eating anything during the race, though he likely stands to perform better if he can keep his glycogen levels closer to full, which is possible at 160 kcal per hour.

Fat adaptation for long endurance races can reduce dependency on mid-race food since, in effect, you carry your food with you as body fat. This self-fueling cuts down on two risks: bonking and GI distress.

Why doesn't every Ironman athlete train to become fat-adapted? I'll save that for another article, but the crux of the answer is that it takes a long time to swap and can be difficult for some to sustain.





## How far can 10 pounds of fat get you? ##

Consider an extreme case of cycling while fasting, and suppose you started nearly glycogen depleted such that nearly all of your power came from fat stores. How far could you get with 10 pounds of body fat? Or asked another way, how far could 10 pounds of oil get you?

10 pounds of fat contains somewhere between 3,500 calories (the oft cited amount) and 4,000 calories (the upper bound assuming 100% of fat cells is lipids).

The optimal speed/watts will depend on BMR. Let's try
- BMR: 1800 kcal/day, 75/hour
- speed(watts): (300, 23.3); (250, 21.5); (200, 19.3); (150, 16.7)
- kcal/hour(watts) = 4 * 0.8604 * watts
- distance(watts) = total_cal / cals/hr * mi/hr =
  - (300, 736.4 miles); (250, )


Ever ran on a treadmill and been shocked by the "calories burned" that it reports? Yeah, me too.
