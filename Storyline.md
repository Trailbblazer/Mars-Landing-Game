<h1>Storylines with ideas for Mars Landing Game</h1>

<h2>Phase 1 (Beginning of the game—before landing on Mars and sending the bots)</h2>

Opening: Tell the opening story (around 2-3 lines short).
Tell the brief story of the mission and its goal of landing on Mars (also focus on finding the suggestion on Mars too, but I have no idea what the suggestion finding from the bots related to the goal is).

————————————————————————————————————

**(Pop-up)**

"The Aurora hangs in Mars' orbit in 2078. Three scout bots will launch humanity's first habitat mission after decades of preparation, looking for important clues on the surface to determine where to build a foothold.”

**(/Click)**

"Commander, your mission is to launch three bots, read their reports, and determine which report is correct. Time and ship energy are limited, so make wise choices.”

————————————————————————————————————

<h2>Phase 2 (After the spaceship landed on Mars / After the 3 bots have landed)</h2>
Continue to tell the story 2-3 times—mainly focus on the process of spaceship landing; the player sends the bots, and the bots land at different locations on Mars. 

————————————————————————————————————

**(Pop-up)**

“Aurora is getting ready for a de-orbit burn. Ground telemetry stabilizes as heat shields glow. T-minus 30 is the touchdown time, according to mission control.”

**(/Click)**

"Main engines are silent. Brace your landing legs. Solid footing is reported by the landing site sensors. Commander, get ready to launch probes.”

**(/Click)**

“At different coordinates, three scout bots eject and land. Each begins local scans and sends a suggestion back to Aurora. One report is faulty (sensor error or corruption), while the other two are accurate. Choose the correct one.”

————————————————————————————————————

<h2>Phase 3 (In-game section)</h2>

The storyline mainly tells the game instructions, and the player will get ready to guess the bot’s suggestion.

Also, mention that the time limit is around 2 or 3 minutes. And also we have some amount of energy  (Don’t know the cost yet)

Bots randomly give/generate the suggestion to find on the specific location on Mars
The developer (Our group) knows which two are correct and which one is wrong. I think it’s a good idea to let the bots generate several suggestions (more than 15 include 10 right and 5 wrong). However, the player doesn’t know which two are correct and which one is wrong.

**Outcomes after guessing:**

Each storyline has 1-2 lines short to explain the players

**-Good End:** (Happy tone)
Idea of the storyline: The mission completed on Mars with process updated
(Consider that the game still have time and energy left)

**-Bad End:** (Not Happy Tone / Mission failed)
—> Also can lead to the time ends or Run out of energy 
You can think different types of Bad end: 
1. The time ends
2. Run out of the energy

Idea of the storyline: The mission failed and has to return back with no process updated

————————————————————————————————————

**(Pop-up)**

In-game instruction text (short): <br>
“You have 5 turns to evaluate bot reports. Each turn, you have to select one suggestion that you believe is correct. Two reports are correct, and one is incorrect. No hints available, so choose wisely.”

**(/Click)**

**Rules and Resources:** <br>
Time: 180 seconds total. <br>
Energy: Start with 100 energy. <br>
Scoring: Correct pick = +10 energy. Wrong pick = −30 energy. <br>
Fail: Time runs out or energy ≤ 0 → mission fails. <br>
Goal: To ensure mission success, get the majority right in five turns. <br>
————————————————————————————————————

Button: Start Mission (or Got it)
Implementation note: show Pop-Up 1 → user clicks Next → show Pop-Up 2 → user clicks Start Mission to start the 180s timer and Turn 1.

Outcomes

-If energy ≤ 0 after update: Energy depleted—mission failed. (show bad-end page)
-If time ≤ 0 at any moment: Time expired—mission failed. (show bad-end page)

————————————————————————————————————
<h3>Good Ending:</h3>

**(Pop-up)**

Title: Mission Accomplished
- **Storyline 1:** You obtained enough accurate data. Humanity takes its first real step on Mars when an outpost location is confirmed and construction starts.
- **Storyline 2:** Steady hands, accurate decisions. The new foothold on Mars will remain in place when the Aurora sends out a green beacon.
- **Storyline 3:** The reports from your team provided direction. Your name appears in the mission log.

Stats line:Correct answers: {C}/5 • Time left: {T}

<h3>Bad Ending:</h3>

**(Pop-up)**

Title: Mission Incomplete
- **Storyline 1 (no energy left):** "After a few misallocations, energy is running out. Aurora had to abort and return due to critical systems. 
- **Storyline 2 (no energy left):** "Too many faulty choices drained the ship’s reserves. The mission has ended as the systems have shut down.”

*Stats line:Correct answers: {C}/5 • Energy: 0*

- **Storyline 1 (time runs out):** "Time expired before final decisions could be made. Aurora gives up on the mission since there is no obvious location.
- **Storyline 2 (time runs out):** “The timer went off. Conflicting reports and the race against time forced an immediate return to Earth.”

*Stats line:Correct answers: {C}/5 • Time left: {T}*

————————————————————————————————————

Button label suggestion: Return to Menu / Restart (to Replay Mission)
