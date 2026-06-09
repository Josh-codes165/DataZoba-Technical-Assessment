# The Story Pitch: The Leapfrog Effect

## 1. The Dataset
I used the **"Individuals using the Internet (% of population)"** dataset from **World Bank Open Data** (Indicator: `IT.NET.USER.ZS`), filtering specifically for **Sub-Saharan Africa** from 2005 to 2025.

## 2. The Hidden Story
When you open this chart, the first thing that hits you is the year 2009. Before that, internet access in Sub-Saharan Africa was basically flatlining under 5%. Then suddenly, the line just takes off, shooting straight up past 35%. 

The real story here isn't just about telecoms or fiber cables; it's about a massive shortcut. While the West spent decades setting up telephone poles, desktop PCs, and dial-up internet, millions of people in Africa skipped that entire middle step. They went straight from zero connectivity to running businesses, handling mobile banking, and learning to code directly on mobile smartphones. The steepness of that curve is the sound of a whole generation completely bypassing old infrastructure constraints.

## 3. The Visualization Strategy
Since this is a frontend assessment, a boring, static line chart feels like a missed opportunity. I want the user to actually feel the speed of this change. 

I’d build an **interactive scrollytelling map**. As the user scrolls down, a map of Africa would light up year-by-year, changing colors as the internet spreads. If you hover over a country, a quick tooltip would pop up showing two lines: one for fixed desktop broadband staying dead flat at the bottom, and another for mobile internet adoption spiking straight into the sky. It keeps the focus on the contrast that makes this data interesting.

## 4. Why It Matters
This matters because it changes how we think about building software. The next wave of internet users, consumers, and developers coming out of Africa aren't using laptops on stable Wi-Fi; they are mobile-first, data-conscious, and incredibly resourceful. It shows that you don't need a legacy infrastructure blueprint to build a massive tech ecosystem—sometimes, starting from a clean slate lets you move way faster.