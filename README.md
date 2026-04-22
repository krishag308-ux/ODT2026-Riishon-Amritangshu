# Open Design and Technology  
## Final Project README

> **Project Weight:** 70%  
> **Team Size:** 2 students  
> **Project Duration:** 4 weeks  
> **Class Time Available:** 6 hours per class  
> **Total Time Available:** 48 effort-hours per team  
> **Project Type:** Playful, interactive, technology-based experience

---

# Before you begin

## Fork and rename this repository
After forking this repository, rename it using the format:

`ODT-2026-TeamName`

### Example
`ODT-2026-PixelWizards`

Do not keep the default repository name.

---

# How to use this README

This file is your team’s **working project document**.

You must keep updating it throughout the 4-week build period.  
By the final review, this README should clearly show:
- your idea,
- your planning,
- your design decisions,
- your technical process,
- your build progress,
- your testing,
- your failures and changes,
- your final outcome.

## Rules
- Fill every section.
- Do not delete headings.
- If something does not apply, write `Not applicable` and explain why.
- Add images, screenshots, sketches, links, and videos wherever useful.
- Update task status and weekly logs regularly.
- Use this file as evidence of process, not only as a final report.

---

# 1. Team Identity

## 1.1 Studio / Group Name
`Gamesworks studio`

## 1.2 Team Members

| Name | Primary Role | Secondary Role | Strengths Brought to the Project |
|---|---|---|---|
| `Amritangshu Goswami` | `Mechanics` | `Electronics` | `3d visualisation, Front-end design, Material knowledge` |
| `Rishon Rahul` | `Electronics` | `Coding` | `Illustrator proficiency, Back end cable management, Prompt engineering` |

## 1.3 Project Title
`Cybertronic Laser Arcade`

## 1.4 One-Line Pitch
`A responsive laser mounted turret against `

## 1.5 Expanded Project Idea
In 1–2 paragraphs, explain:
- what your project is,
- what kind of playful experience it creates,
- what makes it fun, curious, engaging, strange, satisfying, competitive, or delightful,
- what technologies are involved.

**Response:**  
`The project provides a classic shooting arena themed game. Inspired by classic DOOM series video games, here you experience a similar situation. The controllable aspect of the game is a moveable turret. This turret is mounted with a laser diode. The goal is simple- there are enemy target pop ups- and you need to shoot them to score. This in the intended view is meant to be an engaging playful experience. However we, as creators also see a possibility in the prospect of competitive essence. 
The project makes use of simple readily available technologies. This includes laser diodes, ldr sensors, servo motors and a buck resistor(important). Due to it being made of such easily available materials we believe this is one of the more engaging and accessible fun projects one could take on. The casing in our use case is simply laser cut mdf board- which again, leave a huge room for customisability. `

---

# 2. Philosophy Fit

## 2.1 Experience, Not Social Problem
This module does **not** require your project to solve a large social problem.

You are allowed to build:
- toys,
- games,
- interactive objects,
- playful machines,
- kinetic artifacts,
- humorous devices,
- strange but delightful experiences,
- things that are entertaining to use or watch.

## 2.2 What kind of experience are you creating?
Answer the following:
- What is the experience?
- What do you want the player or participant to feel?
- Why would someone want to try it again?

**Response:**  
`As mentioned in this section, the project is not really a "design intervention" of any sort that aims to or claims to solve any real issue. Boredom is however one issue we believe it could very well solve. The intent of this project was to bring a sense of arcade and 90s FPS video games to a very buildable format. We are fans of video games like DOOM, ULTRAKILL, etc and wanted to bring that to a physical existence via the language of arcade games. We want the participant to feel engaged and "locked in" while trying to pan and hit the targets. It being completely crafted makes sure the player has enough room to customise the difficulty via the code. The feel of gettingn most targets right on a default difficulty makes it boring however. But as mentioned- that coult be changed. This ability to create a sense of challenge is in our felt and intended experience is something that could- keep people wanting to try again. `

## 2.3 Design Persona
Complete the sentence below:

> We are designing this project as if we are a small creative studio making a **[toy / game / playable object / interactive experience]** for **[children / teens / adults / classmates / exhibition visitors / mixed audience]**.

**Response:**  
`We are designing this project as if we are a small creative studio making a playable object for mixed audience.`

---

# 3. Inspiration

## 3.1 References
List what inspired the project.

| Source Type | Title / Link | What Inspired You |
|---|---|---|
| `Video game` | `DOOM series` | `We borrowed the aspect of aiming and one shotting targets at a rapid format` |
| `Arcade games` | `N/A (because its a generalised inspiration and not a specific title)` | `We learnt how they create a more physically interactable interface to video games` |


## 3.2 Original Twist
What makes your project original?

**Response:**  
`What makes the project original is how physical it is. All of the primary inspirations for this game has been digital mediums. Or digital mediums approached with a more physical medium. However our project is 100% physical. Another aspect it brings with itself is the vast amount of customisability. Size, target amounts, game difficulty, action speed, etc are all open to customisation. `

---

# 4. Project Intent

## 4.1 Core Interaction Loop
Describe the main loop of interaction.

Examples:
- press → launch → score → reset
- connect → control → observe → repeat
- turn → trigger → react → repeat
- move object → sensor detects → sound/light response → player reacts

**Response:**  
`objects move → player reacts → control → sensor detects → motion response → point scored/point missed `

## 4.2 Intended Player / Audience

| Question | Response |
|---|---|
| Who is this for? | `Action based game enthusiasts ` |
| Age range | `5-30` |
| Solo or multiplayer | `Solo` |
| Expected duration of one round | `~30 seconds` |
| What should the player feel? | `Concentration` |
| Is explanation required before use? | `Mild` |

## 4.3 Player Journey
Describe exactly how a player will use the project.

1. **Approach:** `The player first oberves the entire model, layout and grabs the joystick`
2. **Start:** `Upon moving the joystick the game starts as targets start popping up`
3. **First Action:** `The first action is to grab control of the turret via the joystick and attempt to move it towards the turret`
4. **Main Interaction:** `The control of the turret with the joystick is the primary interaction`
5. **System Response:** `The targets respond to being hit by a laser by instantly proping down`
6. **Win / Lose / End Condition:** `The end calculation is however many targets you successfully hit`
7. **Reset:** `After the set amount of targets disappear the game ends and resets`

## 4.4 Rules of Play
If your project is a game, list the rules clearly.

- `Targets prop up randomly`
- `Targets stay propped for a limited time only`
- `Targets missed will be calculated as null points`
- `Each hit target amounts to +1 point`

---

# 5. Definition of Success

## 5.1 Definition of “Playable”
Your project will be considered complete only if these conditions are met.

- [ ] `random targets pop up`
- [ ] `turret functions`
- [ ] `targets hit by laser respond appropreiately `
- [ ] `Missed targets prop down and count as null points`

## 5.2 Minimum Viable Version
What is the smallest version of this project that still delivers the core experience?

**Response:**  
`Two propped up targets that have a light that indicates the active target. One axis movement turret controlled by any means. `

## 5.3 Stretch Features
What features are nice to have but not essential?

- `N/A (All the used elements are core features that are essential for the experience. However number of targets could possibly be lowered. `

---

# 6. System Overview

## 6.1 Project Type
Check all that apply.

- [ o ] Electronics-based
- [ o ] Mechanical
- [ o ] Sensor-based
- [ ] App-connected
- [ ] Motorized
- [ ] Sound-based
- [ o ] Light-based
- [ ] Screen/UI-based
- [ ] Fabricated structure
- [ o ] Game logic based
- [ ] Installation / tabletop experience
- [ ] Other: `[Write here]`

## 6.2 High-Level System Description
Explain how the system works in simple terms.

Include:
- input,
- processing,
- output,
- physical structure,
- app interaction if any.

**Response:**  
`The esp32 is the core device being used. The joystick is the primary input device being controlled. It provides input which is presented as an output by the two servo SG90 motors on the pan-tilt bracket. The esp 32 randomly activates the wall mounted servos and LED lights. The laser diode provides an input to the ldr sensors which sence it. The physicsl structure functions as the archuitectural skeleton to the mechanics of the project.  `

## 6.3 Input / Output Map

| System Part | Type | What It Does |
|---|---|---|
| `Laser Diode` | Input | `Signals the ldr sensors that the target has been hit` |
| `Joysrick Module` | Input | `Inputs data for the pan tilt servos to move ` |
| `ESP32` | Processing | `Acts as the main processing unit of the entire project` |
| `Servo` | Output | `React to the ldr sensots, esp 32 and joystick module` |
| `LED` | Output | `Used by esp32` |
| `MDF cutouts` | Physical Action | `provide a physical skeleton for the functioning of the motors` |

---

# 7. Sketches and Visual Planning

## 7.1 Concept Sketch
Add an early sketch of the full idea.

**Insert image below:**  
`[[Upload image and link here]](https://drive.google.com/drive/folders/1T5MRtfmZk03ib4DMRt__p7CoivhCXcXO?usp=sharing)`

Example:
```md

```

## 7.2 Labeled Build Sketch
Add a sketch with labels showing:
- structure,
- electronics placement,
- user touch points,
- moving parts,
- output elements.

**Insert image below:**  
`N/A (This step was mainly iterated on Blender) `

## 7.3 Approximate Dimensions

| Dimension | Value |
|---|---|
| Length | `28cm` |
| Width | `33cm` |
| Height | `15cm` |
| Estimated weight | `500gm` |

---

# 8. Mechanical Planning

## 8.1 Mechanical Features
Check all that apply.

- [ ] Gears
- [ ] Pulleys
- [ ] Belt drives
- [ ] Linkages
- [ ] Hinges
- [ ] Shafts
- [ ] Springs
- [ ] Bearings
- [ ] Wheels
- [ ] Sliders
- [ ] Levers
- [ 🗸 ] Not applicable

## 8.2 Mechanical Description
Describe the mechanism and what it is meant to do.

**Response:**  
`N/A ( The project does not feature the aforementioned mechanical parts.)`

## 8.3 Motion Planning
If something moves, explain:
- what moves,
- what causes the movement,
- how far it moves,
- how fast it moves,
- what could go wrong.

**Response:**  
` The are mainly two moving parts in the project. The wall mounted targets and the laser diode. The wall mounted targets move because they are attached to servo motors. They pop up relatively fast and stay. Its a rotational motion so not much distance is covered. If not properly alligned the target might hit something and it may mess up the servo orientation. 
The laser diode moves as its mounted on top of a pan tilt bracket. This bracket is a combination of two servos which are moved by signals sent by the joystick module. No notable distance is covered. A lack of stability of the bracket could cause colapse of the structure and damage the servos. ` 

## 8.4 Simulation / CAD / Animation Before Making
If your project includes mechanical motion, document the digital planning before fabrication.

| Tool Used | File / Link | What Was Tested |
|---|---|---|
` (N/A) Because Blender was used for visualisation, not physics testing. `

## 8.5 Changes After Digital Testing
What changed after the CAD, animation, or simulation stage?

**Response:**  
`(N/A) Because Blender was used for visualisation, not physics testing.`

---

# 9. Electronics Planning

## 9.1 Electronics Used

| Component | Quantity | Purpose |
|---|---:|---|
| `[ESP32]` | `1` | `[Main controller]` |
| `SG90 servo motors` | `4` | `Wall mounted trgets & Pan-tilt bracket` |
| `Ldr sensor` | `4` | `Sensors used on the targets` |
| `Laser diode` | `1` | `Used to trigger the ldr sensors on the targets` |

## 9.2 Wiring Plan
Describe the main electrical connections.

**Response:**  
`The whole thing is processed by the esp 32. The main components, i.e. Servo motors, LDR sensors and Joystick module are all connected to different pins of the Esp 32. The model also includes a buck resistor and a 2a adapter. The buck resistor 5v is connected to one side and 12v to the other. All the gnd and and electricity connections happen towards the 5v side. `

## 9.3 Circuit Diagram
Insert a hand-drawn or software-made circuit diagram.

**Insert image below:**  
`https://drive.google.com/file/d/16pyrT3zxEgqAVGI5x4Baeao4lcbL2esl/view?usp=drive_link `

## 9.4 Power Plan

| Question | Response |
|---|---|
| Power source | `adapter` |
| Voltage required | `5v` |
| Current concerns | `The ESP32's 3.3V pin can only supply around 600mA total, so don't power the servos from it — they can draw up to 1A each under load which would instantly overload the board. Use a separate 5V supply (phone charger or power bank) for all 4 servos. The sensors, LEDs, joystick and display together draw well under 200mA so they are safe on the ESP32's 3.3V pin.` |
| Safety concerns | `The ESP32 runs on 3.3V logic, so never connect 5V directly to any GPIO pin — it will damage the chip permanently. Always use a 220Ω resistor with each LED, and make sure the external 5V power supply for the servos shares a common GND with the ESP32. Keep all wires secure on the breadboard so nothing shorts out during the game.` |

---

# 10. Software Planning

## 10.1 Software Tools

| Tool / Platform | Purpose |
|---|---|
| `MicroPython` | `Micropython was used to code the whole project` |

## 10.2 Software Logic
Describe what the code must do.

Include:
- startup behavior,
- input handling,
- sensor reading,
- decision logic,
- output behavior,
- communication logic,
- reset behavior.

**Response:**  
`Code detects game started. Animation on the display indicates the start. Rotate the servos at random OR light an LED light at random. Then its supposed to exist at that stage for the mentioned duration. If the ldr sensor activated senses laser it turns the servo back to its initial angle. Simultaneously active feedback from the joystick module on x and y axis is taken. This feedback is then output by two servos- one for x and one for y. After a set amounts of targets are popped, final score is calculated and displayed. Behaviour resets.`

## 10.3 Code Flowchart
Insert a flowchart showing your code logic.

Suggested sequence:
- start,
- initialize,
- wait for input,
- read input,
- decision,
- trigger output,
- repeat or reset,
- error handling.

**Insert image below:**  
`N/A (a code flowchart doesnt exist or we do not understand how to provide one)`

## 10.4 Pseudocode

```text
N/A (the pseudocode wasnt properly written as it doesnt help with our workflow)
```

---

# 11. MIT App Inventor Plan

## 11.1 Is an app part of this project?
- [ ] Yes
- [🗸] No

If yes, complete this section.

## 11.2 Why is the app needed?
Explain what the app adds to the experience.

Examples:
- remote control,
- score tracking,
- mode selection,
- personalization,
- triggering effects,
- displaying data.

**Response:**  
`[Write here]`

## 11.3 App Features

| Feature | Purpose |
|---|---|
| `[Bluetooth connect button]` | `[Purpose]` |
| `[Score display]` | `[Purpose]` |
| `[Control button / slider / label]` | `[Purpose]` |

## 11.4 UI Mockup
Insert a sketch or screenshot of the app interface.

**Insert image below:**  
`[Upload image and link here]`

## 11.5 App Screen Flow

1. `[Step 1]`
2. `[Step 2]`
3. `[Step 3]`
4. `[Step 4]`

---

# 12. Bill of Materials

## 12.1 Full BOM

| Item | Quantity | In Kit? | Need to Buy? | Estimated Cost | Material / Spec | Why This Choice? |
|---|---:|---|---|---:|---|---|
| `[ESP32]` | `1` | `Yes` | `No` | `0` | `[Spec]` | `[Reason]` |
| `Servo SG90` | `4` | `Yes` | `Yes` | `500` | `[Spec]` | `Can calibrate angles` |
| `Ldr sensor` | `4` | `Yes` | `Yes` | `70` | `[Spec]` | `Senses laser` |
| `Laser diode` | `1` | `Yes` | `No` | `0` | `[Spec]` | `laser` |
| `Joystick` | `1` | `No` | `No` | `70` | `[Spec]` | `Provides x axis y axis movement feedback` |

## 12.2 Material Justification
Explain why you selected your main materials and components.

Examples:
- Why acrylic instead of cardboard?
- Why MDF instead of 3D print?
- Why servo instead of DC motor?
- Why bearing instead of a plain shaft hole?

**Response:**  
`Mdf was used because laser cutting is a much faster process. This is also very simple and provides all the requirements for our needs. Servo was used instead of a DC because it provides vetter caliberation. `

## 12.3 Items to Purchase Separately

| Item | Why Needed | Purchase Link | Latest Safe Date to Procure | Status |
|---|---|---|---|---|
| `Joystick` | `control` | `N/A (local shops) ` | `N/A` | `Received` |


## 12.4 Budget Summary

| Budget Item | Estimated Cost |
|---|---:|
| Electronics | `800` |
| Mechanical parts | `0` |
| Fabrication materials | `0` |
| Purchased extras | `800` |
| Contingency | `100` |
| **Total** | `1000` |

## 12.5 Budget Reflection
If your cost is too high, what can be simplified, removed, substituted, or shared?

**Response:**  
`The budget was not too high. However servos could be costly so they must be used carefully.`

---

# 13. Planning the Work

## 13.1 Team Working Agreement
Write how your team will work together.

Include:
- how tasks are divided,
- how decisions are made,
- how progress will be checked,
- what happens if a task is delayed,
- how documentation will be maintained.

**Response:**  
`The tasks are divided based off of who is more interested in which step of the work. Decisions were made collaboratively. Both the members will keep a check and keep each other updated. If task is delayed we move on to the next possible task or wait deoending on the scenario. Pictorgaphical documentation will be maintained.  `

## 13.2 Task Breakdown

| Task ID | Task | Owner | Estimated Hours | Deadline | Dependency | Status |
|---|---|---|---:|---|---|---|
| T1 | `[Finalize concept]` | `Amritangshu` | `2` | `[Date]` | `None` | `To Do` |
| T2 | `[Complete BOM]` | `Rishon` | `1` | `[Date]` | `T1` | `To Do` |
| T3 | `[Test electronics]` | `Rishon` | `2` | `[Date]` | `T1` | `To Do` |
| T4 | `[Build structure]` | `Amritangshu` | `4` | `[Date]` | `T1` | `To Do` |
| T5 | `[Write control code]` | `Rishon` | `4` | `[Date]` | `T3` | `To Do` |
| T6 | `[Integrate system]` | `Rishon` | `4` | `[Date]` | `T4, T5` | `To Do` |
| T7 | `[Playtest]` | `Amritangshu` | `2` | `[Date]` | `T6` | `To Do` |
| T8 | `[Refine and document]` | `Amritangshu` | `3` | `[Date]` | `T7` | `To Do` |

## 13.3 Responsibility Split

| Area | Main Owner | Support Owner |
|---|---|---|
| Concept and gameplay | `Amritangshu` | `Rishon` |
| Electronics | `Amritangshu` | `Rishon` |
| Coding | `Amritangshu` | `Rishon` |
| App | `Amritangshu]` | `Rishon` |
| Mechanical build | `Amritangshu` | `Rishon` |
| Testing | `Amritangshu` | `Rishon` |
| Documentation | `Amritangshu` | `Rishon` |

---

# 14. Weekly Milestones

## 14.1 Four-Week Plan

### Week 1 — Plan and De-risk
Expected outcomes:
- [🗸 ] Idea finalized
- [ ] Core interaction decided
- [ 🗸] Sketches made
- [ ] BOM completed
- [ ] Purchase needs identified
- [ ] Key uncertainty identified
- [ ] Basic feasibility tested

### Week 2 — Build Subsystems
Expected outcomes:
- [🗸 ] Electronics tests completed
- [ 🗸] CAD / structure planning completed
- [ ] App UI started if needed
- [ ] Mechanical concept tested
- [ ] Main subsystems partially working

### Week 3 — Integrate
Expected outcomes:
- [🗸 ] Physical body built
- [ ] Electronics integrated
- [ ] Code connected to hardware
- [ ] App connected if required
- [ ] First playable version exists

### Week 4 — Refine and Finish
Expected outcomes:
- [ ] Technical bugs reduced
- [🗸 ] Playtesting completed
- [ ] Improvements made
- [ 🗸] Documentation completed
- [ ] Final build ready

## 14.2 Weekly Update Log

| Week | Planned Goal | What Actually Happened | What Changed | Next Steps |
|---|---|---|---|---|
| Week 1 | `[Write here]` | `[Write here]` | `[Write here]` | `[Write here]` |
| Week 2 | `[Write here]` | `[Write here]` | `[Write here]` | `[Write here]` |
| Week 3 | `[Write here]` | `[Write here]` | `[Write here]` | `[Write here]` |
| Week 4 | `[Write here]` | `[Write here]` | `[Write here]` | `[Write here]` |

---

# 15. Risks and Unknowns

## 15.1 Risk Register

| Risk | Type | Likelihood | Impact | Mitigation Plan | Owner |
|---|---|---|---|---|---|
| `parts not working` | `technical` | `medium` | `medium` | `buy new stuff` | `N/A` |
| `code not working` | `computer science` | `medium` | `medium` | `consult a trusted coder` | `N/A` |

## 15.2 Biggest Unknown Right Now
What is the single biggest uncertainty in your project at this stage?

**Response:**  
`We dont know how to make it properly fuction completelty because joining the circuitry is a but tricky`

---

# 16. Testing and Playtesting

## 16.1 Technical Testing Plan

| What Needs Testing | How You Will Test It | Success Condition |
|---|---|---|

| `[Mechanism movement]` | `test code` | `when it works like it should` |
| `[Sensor behavior]` | `test code` | `when it detects behaviour` |


## 16.2 Playtesting Plan

| Question | How You Will Check |
|---|---|
| Do players understand what to do? | `tell them` |
| Is the interaction satisfying? | `ask for feedback` |
| Do players want another turn? | `observe enthusiasm` |
| Is the response clear and immediate? | `observation` |

## 16.3 Testing and Debugging Log

| Date | Problem Found | Type | What You Tried | Result | Next Action |
|---|---|---|---|---|---|
| `[Date]` | `[Describe issue]` | `[Technical / Mechanical / UI / Gameplay]` | `[What you did]` | `[Worked / Partly / Failed]` | `[Next step]` |
| `[Date]` | `[Describe issue]` | `[Type]` | `[What you did]` | `[Result]` | `[Next step]` |

## 16.4 Playtesting Notes

| Tester | What They Did | What Confused Them | What They Enjoyed | What You Will Change |
|---|---|---|---|---|
| `[Peer / friend / classmate]` | `[Observation]` | `[Observation]` | `[Observation]` | `[Action]` |
| `[Peer / friend / classmate]` | `[Observation]` | `[Observation]` | `[Observation]` | `[Action]` |

`N/A playtesting was done amongst mainly the teammates only prior to release`

---

# 17. Build Documentation

## 17.1 Fabrication Process
Describe how the project was physically made.

Include:
- cutting,
- 3D printing,
- assembly,
- fastening,
- wiring,
- finishing,
- revisions.

**Response:**  
`The project was physically made it laser cut individual pieces. These pieces are clamped together. This makes the setup modular so the inner part is filled with wiring while the casing covers it. Glue and foam board was only used for making the pan tilt bracket. `

## 17.2 Build Photos
Add photos throughout the project.

Suggested images:
- early sketch,
- prototype,
- electronics testing,
- mechanism test,
- app screenshot,
- final build.

Example:
```md

https://drive.google.com/drive/folders/1T5MRtfmZk03ib4DMRt__p7CoivhCXcXO?usp=drive_link

```

## 17.3 Version History

| Version | Date | What Changed | Why |
|---|---|---|---|
| `v1` | `22.4.2026` | `Not fully complete` | `Under construction due to electrical malfunctions` |


---

# 18. Final Outcome

## 18.1 Final Description
Describe the final version of your project.

**Response:**  
`As mentioned in this section, the project is not really a "design intervention" of any sort that aims to or claims to solve any real issue. Boredom is however one issue we believe it could very well solve. The intent of this project was to bring a sense of arcade and 90s FPS video games to a very buildable format. We are fans of video games like DOOM, ULTRAKILL, etc and wanted to bring that to a physical existence via the language of arcade games. We want the participant to feel engaged and "locked in" while trying to pan and hit the targets. It being completely crafted makes sure the player has enough room to customise the difficulty via the code. The feel of gettingn most targets right on a default difficulty makes it boring however. But as mentioned- that coult be changed. This ability to create a sense of challenge is in our felt and intended experience is something that could- keep people wanting to try again.`

## 18.2 What Works Well
- `Display`
- `Pan tilt bracket joystick`
- `ldr sensors`

## 18.3 What Still Needs Improvement
- `Servo management`
- `Attaching pieces`


## 18.4 What Changed From the Original Plan
How did the project change from the initial idea?

**Response:**  
`The plan had a slightly different layout structure. That layout structure was changed throughout the project. This was realised by facing real life physical contstraints regarding the size of the cutout model. `

---

# 19. Reflection

## 19.1 Team Reflection
What did your team do well?  
What slowed you down?  
How well did you manage time, tasks, and responsibilities?

**Response:**  
`The team tried hard on the last bit of the project. However more evenly spread effort could have been implied. The laser cut was nit of proper, enough dimensions, etc. We still managed to accomplish a lot. It was an overall good learning experience. `

## 19.2 Technical Reflection
What did you learn about:
- electronics,
- coding,
- mechanisms,
- fabrication,
- integration?

**Response:**  
`A major technical issue was faced by the team. Th kit provided power supplier was unable to handle 4 servos at once. This led the power supplier to fry all the servos. This caused a massive dent in the team's progress. We later acquired a buck resistor but unfortunatelt werent able to present a working model during class hours. The team is still working on it trying to recover and bounce back. Luckily most other parts survived.  `

## 19.3 Design Reflection
What did you learn about:
- designing for play,
- delight,
- clarity,
- physical interaction,
- player understanding,
- iteration?

**Response:**  
`Although ultimately not fully realised the team is pretty satisfied with th concept of the project. The servos worked the intended way before they were fried. The team also learnt a lot about the physicsl aspects of it. Specifically how size of display impacts user experience. `

## 19.4 If You Had One More Week
What would you improve next?

**Response:**  
`We would improve the casing size of the whole project. Rebuild the whole project properly again with a buck resistor to make sure nothinmg fries again. `

---

# 20. Final Submission Checklist

Before submission, confirm that:
- [🗸 ] Team details are complete
- [🗸 ] Project description is complete
- [ 🗸] Inspiration sources are included
- [🗸 ] Player journey is written
- [ 🗸] Sketches are added
- [🗸 ] BOM is complete
- [ 🗸] Purchase list is complete
- [ 🗸] Budget summary is complete
- [ ] Mechanical planning is documented if applicable
- [ ] App planning is documented if applicable
- [ ] Code flowchart is added
- [🗸 ] Task breakdown is complete
- [🗸 ] Weekly logs are updated
- [🗸 ] Risk register is complete
- [ 🗸] Testing log is updated
- [ 🗸] Playtesting notes are included
- [ 🗸] Build photos are included
- [ 🗸] Final reflection is written

---

# 21. Suggested Repository Structure

```text
project-repo/
├── README.md
├── images/
│   ├── concept-sketch.jpg
│   ├── labeled-sketch.jpg
│   ├── circuit-diagram.jpg
│   ├── ui-mockup.jpg
│   ├── prototype-1.jpg
│   └── final-build.jpg
├── code/
│   ├── main.py
│   ├── test_code.py
│   └── notes.md
├── cad/
│   ├── models/
│   └── screenshots/
└── docs/
    ├── references.md
    └── extra-notes.md
```

---

# 22. Instructor Review

## 22.1 Proposal Approval
- [ 🗸] Approved to proceed
- [ 🗸 ] Approved with changes
- [ 🗸] ] Rework required before proceeding

**Instructor comments:**  
`[Instructor fills this section]`

## 22.2 Midpoint Review
`[Instructor fills this section]`

## 22.3 Final Review Notes
`[Instructor fills this section]`
