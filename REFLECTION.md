# Reflection – Daily Schedule Simulator

## 1. Your Approach
I built a simulator that shows my typical day as a student and entrepreneur. I included realistic moments like hitting snooze, checking my phone, working on CS81 JavaScript assignments, lunch breaks with scrolling, study sessions, and evening chill time. I wanted it to feel authentic to my actual daily routine balancing coursework, business work, and trying to stay awake through it all.

## 2. One Timing Challenge or Surprise
At first, I set all the delays really close together (like 1 second apart) and everything printed instantly, which made it feel rushed and unrealistic. I had to space them out more (2+ seconds) so the "day" actually unfolds over time. I also noticed that my random surprise event sometimes showed up before lunch or after the evening, which made the timeline feel a bit chaotic—but that's kind of the point of a surprise!

## 3. Asynchronous vs. Sequential Code
This taught me that `setTimeout` doesn't pause or wait—it schedules things to happen later while the rest of the code keeps running. In normal sequential code, line 1 finishes before line 2 starts. But with async code, all my `setTimeout` calls got scheduled at once, and then they fired at their specific delays. It's like setting multiple alarms instead of waiting for one alarm to ring before setting the next.

## 4. Creative Twist
I added a random surprise event that picks from an array of funny, relatable interruptions: spontaneous boba runs, accidental hour-long naps, sudden room cleaning instead of studying, falling into TikTok/YouTube holes, or needing snacks immediately. The event fires at a random delay between 3 and 12 seconds, so every time you refresh the page, the surprise happens at a different point in the day. It makes the simulation feel less predictable and more true to real life where random stuff just happens.

## 5. Realism vs. Actual Time
Obviously this isn't real time my actual day takes 16+ hours, not 15 seconds. But the sequence and vibe are accurate. I compressed everything so the simulation feels like a sped-up version of my routine. The randomness also adds realism because life doesn't follow a perfect schedule. If I wanted true realism, I'd have to use way longer delays (like hours), but then no one would sit and wait for it. This version balances showing the flow of a day with keeping it watchable and interactive.

