# SKILL LAB PRATICAL HACKATHON

## Final Project README

> **Project Weight:** 100%  
> **Team Size:** 4/3 students  
> **Project Duration:** 8 hours  
> **Total Time Available:** 32 effort-hours per team  
> **Project Type:** Playful, interactive, technology-based experience

---

# Before you begin

## Fork and rename this repository

After forking this repository, rename it using the format:

`SKILLLAB_PROR-2026-TeamName`

### Example

`SKILLLAB_PROR-2026-AuroWizards`

Do not keep the default repository name.

---

# How to use this README

This file is your team’s **working project document**.

You must keep updating it throughout the build period.  
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

`group7`

## 1.2 Team Members

| Name           | Primary Role                    | Secondary Role | Strengths Brought to the Project |
| -------------- | ------------------------------- | -------------- | -------------------------------- |
| `Saloni Sawant` | `Documentation` | `Hardwarwe`  | `Documentation, Gift of Gab `|
| `Pushkar Sawlani`  | `Documentation`   | `Coding`     | `Material Handling, Hardware`    |
| `Faizan Shah` | `Hardware` | `Documentation`  | `Documentation, Gift of Gab `|
| `Aditya Singh`  | `Hardware`   | `Coding`     | `Material Handling, Hardware`    |

## 1.3 Project Title

`"Intelligent waste classfiction system "`

`(because Project-or)`

<img width="1600" height="1131" alt="image" src="https://github.com/pushjjjj/SKILLLAB__PROR_2026_group7/blob/main/images/group7_geotag.jpeg" />
<img width="1600" height="1131" alt="image" src="https://github.com/pushjjjj/SKILLLAB__PROR_2026_group7/blob/main/images/team_logo.jpeg" />

## 1.4 One-Line Pitch

`Think less sort smart`

## 1.5 Expanded Project Idea

In 1–2 paragraphs, explain:

- what your project is,
- what kind of experience it creates,
- what technologies are involved.

**Response:**  
`Our project, Intelligent Waste Classification System, is a smart setup that automatically sorts waste into metal, wet, and dry categories using a single input bin. When someone drops waste into the bin, the system quickly checks what type it is using simple sensors, then rotates the base and opens a small flap to drop it into the correct compartment. It’s designed to make waste sorting feel effortless and automatic.
While building this project, we gained a lot of hands-on experience. We didn’t just connect components—we had to figure out how everything works together in real life. We faced issues like sensors giving unstable readings, servos not moving properly due to power problems, and alignment errors in the rotating base. Fixing these taught us a lot about debugging, teamwork, and practical problem-solving. Overall, it helped us understand how to turn an idea into a working system using technologies like Shrike Lite, sensors, and motors.`
.`

---

# 2. Philosophy Fit

## 2.1 Experience, Not Social Problem

`While making the Intelligent Waste Classification System, we got real hands-on experience of how things actually work outside of theory. In the beginning, everything looked simple, but once we started building, we realized even small things like loose wires or wrong sensor values could affect the whole system. We spent time testing, adjusting, and fixing issues until the sensors started giving stable readings and the system behaved the way we wanted.
The mechanical part was even more interesting. Getting the rotating base to align perfectly with the bins and making the trapdoor open at the right time took a lot of trial and error. We also faced problems with servo power, where motors didn’t work properly until we fixed the power supply. Throughout this process, we worked together, shared ideas, and helped each other debug problems. In the end, it felt really satisfying to see our idea turn into a working system, and we learned a lot about practical electronics, teamwork, and problem-solving.`





# 3. Inspiration

## 3.1 References

List what inspired the project.

| Source Type | Title / Link                                                        | What Inspired You                                                                         |
| ----------- | ------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| `chatgpt`   | `https://chatgpt.com/share/69f0519f-790c-8324-baa5-1d6b88c218c7`    | `Ideas`|
|             |                                                                     |                                                                                           |
|             |                                                                     |                                                                                           |

## 3.2 Original Twist

What makes your project original?

**Response:**  
`What makes our project original is how everything works together in a smooth, step-by-step way, just like shown in the diagram. Instead of directly throwing waste into separate bins, our system first stops the waste, checks it using sensors, decides the type, and then moves the correct bin into position before dropping it. This “think → rotate → drop” process makes it feel more like an intelligent system rather than a simple dustbin.
Another thing that makes it unique is that we used simple components in a smart way. A magnet is used to detect metal, a moisture sensor checks for wet waste, and if neither is detected, it automatically considers it dry. Then, instead of multiple openings, we use one input and a rotating base with three bins, which makes the design compact and efficient. It’s not just about separating waste, it’s about showing how a system can sense, decide, and act, making it more interactive and interesting to use..`

---

# 4. Project Intent

## 4.1 User Journey 

Describe exactly how a user will use the project.Make it a story
**Response:** 
`Arjun walks up to the system holding a small piece of waste. At first glance, it looks like a normal bin with a single opening on top. Curious, he drops the waste inside. Instead of it falling straight down, it pauses for a moment inside the box—almost like the system is “thinking.”
Behind the scenes, the sensors quickly check the waste. Within a second, the base below starts to rotate smoothly, bringing one of the bins right under the chamber. Arjun watches as the system quietly makes its decision. Then, a small flap opens, and the waste drops neatly into the correct bin. The flap closes, and the system goes back to its ready position.
He tries again with a different item. This time, the base rotates to a different bin before dropping it. It feels like the system understands what he’s giving it. What seemed like just another dustbin turns into something interesting. He doesn’t have to think about sorting anymore, he just drops the waste and watches the system handle everything on its own..`
                                                  



---

# 5. Definition of Success

## 5.1 Definition of “Usable”
`The system is “usable” if a user can simply drop waste into the bin without needing any instructions, and the system takes care of the rest. It should work quickly, reliably, and safely, without confusing the user. A usable system also means the process is smooth to observe—detecting, rotating, and dropping—so anyone can understand how it works just by watching it..`


## 5.2 Minimum Usable Version

What is the smallest version of this project that still delivers the core experience?

**Response:**  
## 5.2 Minimum Usable Version

`The Minimum Usable Version of this project is the simplest working model that still performs the main task of sorting waste automatically into the correct bin.
For this Smart Waste Segregation System, the minimum usable version would include:
1 input bin where waste is inserted
1 metal sensor to detect metal waste
1 wet sensor to detect wet waste
1 Shrike Lite controller to read sensor data and make decisions
1 rotating base with 3 bins (Metal, Wet, Dry)
1 servo motor for rotating the base
1 servo motor for opening the trapdoor
How it works in the minimum version:
When a user puts waste into the input bin, the sensors check the type of waste.

If metal is detected → the base rotates to the metal bin
If wet waste is detected → the base rotates to the wet bin
If neither is detected → it is treated as dry waste

After the correct bin comes under the trapdoor, the servo opens the trapdoor and the waste falls into that bin.`


## 5.3 Stretch Features

What features are nice to have but not essential?

`Stretch features are enhancements that improve the system’s performance, appearance, or user experience but are not required for the core functionality of waste classification and sorting. One useful addition is a three-category system (metal, wet, and dry) by integrating a moisture sensor along with the existing metal detection. Another enhancement is adding LED indicators or a buzzer to provide clear feedback about the detected waste type, making the system more interactive and easier to understand during demonstrations.Further improvements could include a transparent viewing window so users can see the internal working, or an LCD display that shows messages like “Metal Detected” or “Wet Waste.” You could also add automatic lid opening using an ultrasonic sensor for a touchless experience. For a more advanced version, features like data logging, IoT connectivity, or mobile app integration can be included to track waste patterns. While these features make the project more impressive and user-friendly, the system can still function effectively without them.`


# 6. System Overview

## 6.1 Project Type

Check all that apply.

- [x] Electronics-based

- [ ] Mechanical

- [x] Sensor-based

- [x] App-connected

- [x] Motorized

- [x] Sound-based

- [ ] Light-based

- [ ] Screen/UI-based

- [x] Fabricated structure

- [ ] Game logic based

- [x] Installation

- [ ] Other:

## 6.2 High-Level System Description

Explain how the system works in simple terms.

Include:

- input,
- processing,
- output,
- physical structure,
- app interaction if any.

**Response:**  
`1. Input`
`The user simply drops a piece of waste into the top opening of the bin. The waste enters a small chamber inside the system instead of falling directly down.`
`2. Processing`
`Inside the chamber, the system checks the type of waste. A magnet is used to detect if the object is metal, and a moisture sensor checks if it is wet. The controller (Shrike Lite) reads these inputs and decides which category the waste belongs to—metal, wet, or dry.`
`3. Output`
`Once the decision is made, a servo motor rotates the base so that the correct bin is aligned below the chamber. Then, a small trapdoor (controlled by another servo) opens, and the waste drops into the selected bin.`
`4. Physical Structure`
`The system has a top input bin, a middle sensing chamber, and a bottom rotating platform with three bins attached. The servo motor is placed at the center to rotate the base, and another servo controls the trapdoor. The structure can be built using cardboard or lightweight materials.`
`5. App Interaction (if any)`
`In the basic version, there is no mobile app involved. The system works automatically based on sensors and programmed logic. However, in advanced versions, an app or display can be added to show waste type or system status.`

## 6.3 Input / Output Map

| System Part                              | Type            | What It Does                                                               |
 Top Input Bin / Funnel                    | input           | Receives waste from the user and guides it into the sensing chamber
 Magnet (Metal Detection)                  | input           | Identifies if the waste is metal based on magnetic attraction
 Soil Moisture                             | input           | Detects moisture level to classify wet waste
 Shrike Lite Controller                    | processing      | Reads sensor data and decides the waste category (metal, wet, or dry)
 Servo Motor (Rotating Base)               | output          | Rotates the base to align the correct bin under the chamber
 Servo Motor (Trapdoor)                    | output          | Opens/closes the flap to release waste into the selected bin
 Rotating Base with 3 Bins                 |  output         | Collects segregated waste in separate compartments


# 7. Sketches and Visual Planning

## 7.1 Concept Sketch

Add an early sketch of the full idea.

**Insert image below:**  
`[Upload image and link here]`
<img width="1600" height="1200" alt="image" src="https://github.com/pushjjjj/SKILLLAB__PROR_2026_group7/blob/main/images/7.1_concept_sketch.jpeg" />




## 7.2 Labeled Build Sketch

Add a sketch with labels showing:

- structure,
- electronics placement,
- user touch points,
- moving parts,
- output elements.

**Insert image below:**  
`[Upload image and link here]`
<img width="1600" height="1200" alt="image" src="https://github.com/pushjjjj/SKILLLAB__PROR_2026_group7/blob/main/images/7.2_Labled_sketch.jpeg" />

## 7.3 Approximate Dimensions

| Dimension        | Value   |
| ---------------- | ------- |
| Length           | `16 cm` |
| Width            | `16 cm` |
| Height           | `8 cm`  |
| Estimated weight | `400 g` |

---

# 8. Electronics Planning

## 8.1 Electronics Used

| Component                 | Quantity | Purpose                                            |
| ------------------------- | --------:| ---------------------------------------------------|
| `[Shrike Lite Controller]`| `1`      | `[Main controller]`                                |
| `[servo  Motor Driver]`   | `1`      | `[Control Motors]`                                 |
| `[Soil Moisture Sensor]`  | `1`      | `[Detects wet waste based on moisture content]`    |
| `[Power Supply (5V ]`     | `1`      | `[Supplies power to the controller and components]`|


## 8.2 Wiring Plan

Describe the main electrical connections.

**Response:**  
`The Shrike Lite controller acts as the central hub for all connections. It is powered using a stable 5V supply, with the VCC and GND pins distributed to all components through a breadboard to ensure a common ground.
The soil moisture sensor is connected with its VCC to 5V, GND to GND, and output pin to an analog input pin of the controller, allowing it to measure moisture levels. The ultrasonic sensor (if used) has its VCC and GND connected to power, while its TRIG and ECHO pins are connected to two digital pins on the controller for object detection.
For actuation, two servo motors are used. The rotating base servo (MG995/MG996) has its power (red) connected to an external 5V supply, ground to common GND, and signal wire connected to a PWM digital pin on the controller. The trapdoor servo (SG90) is connected similarly, with its signal wire going to another PWM pin. It is important to use a stable power source for servos to avoid voltage drops.
Optional output components like LEDs are connected to digital pins through current-limiting resistors, and the buzzer is connected to a digital pin and ground for sound feedback. All components share a common ground, ensuring proper communication and stable operation of the system.`

## 8.3 Circuit Diagram

Insert a hand-drawn or software-made circuit diagram.

**Insert image below:**  
`[Upload image and link here]`
<img width="1600" height="1200" alt="image" src="https://github.com/pushjjjj/SKILLLAB__PROR_2026_group7/blob/main/images/circuit_diagram.jpeg" />


# 9. Power Plan

| Question         | Response                                                                                                                                          |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Power source     | `5v powersupply `                                                                                                                           |
| Voltage required | `5v dc `                                                                                                                                    |
| Current concerns | `1-2A`                                                                                                                                      |
| Safety concerns  | `Ensure correct polarity, avoid short circuits, use insulated connections, and do not overload the power supply to prevent overheating`     |

---

# 10. Software Planning

## 10.1 Software Tools

| Tool / Platform                | Purpose                                                                                   |
| ------------------------------ | ----------------------------------------------------------------------------------------- |
| `[Arduino IDE]`                | `Writing, compiling, and uploading code to the controller`                                |


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
`
**Startup Behavior**
When the system is powered on, the controller initializes all pins, sets the servo motors to their default positions (base aligned to a neutral position and trapdoor closed), and starts serial communication for debugging if required. The system then enters a standby mode, waiting for waste input.

**Input Handling**
The system monitors for input when waste is placed in the chamber. Once an object is detected, the system temporarily pauses further actions to allow stable sensor readings.

**Sensor Reading**
The controller reads data from the sensors:
Checks magnetic condition (metal detection using proximity sensor)
Reads analog values from the soil moisture sensor to determine if the waste is wet
Multiple readings may be taken to improve accuracy.

**Decision Logic**
Based on the sensor data:
If metal is detected → classify as metal
Else if moisture level is above threshold → classify as wet
Else → classify as dry
The system selects the corresponding bin position.

**Output Behavior**
The controller sends signals to the servo motors:
Rotates the base servo to align the correct bin (e.g., 0°, 120°, 240°)
After alignment, activates the trapdoor servo to open and drop the waste
Closes the trapdoor after a short delay

**Communication Logic**
If debugging is enabled, the system sends sensor readings and classification results to the serial monitor. In advanced versions, this can be extended to display output on an LCD or send data to an app.

**Reset Behavior**
After the waste is dropped, the system resets by:
Returning the base servo to a default standby position
Ensuring the trapdoor is closed
Clearing any temporary variables
Returning to idle state, ready for the next input


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
<img width="1600" height="1200" alt="image" src="https://github.com/pushjjjj/SKILLLAB__PROR_2026_group7/blob/main/images/flow%20chart.jpeg" />




# 11. Bill of Materials

## 11.1 Full BOM

| Item                             | Quantity | In Kit? | Need to Buy? | Estimated Cost | Material / Spec               | Why This Choice?          |
| -------------------------------- | --------:| ------- | ------------ | --------------:| ----------------------------- | ------------------------- |
| `[Shrike Lite Controller]`       | `[1]`      | `[Yes]`   | `[No]`         | `[0]`            | `[Microcontroller board]`       | `[To control components]` |
| `[Servo Motor]`                  | `[1]`    | `[Yes]` | `[No]`       | `[0]`            | `[MG995]`                     | `[Rotates base with bins]`|
| `[Soil Moisture Sensor]`         | `[1]`    | `[No]`  | `[Yes]`      | `[0]`          | `[analog sensor]`               | `[Detects wet waste]`     |
| `[Magnet]`                       | `[1]`    | `[No]`  | `[Yes]`      | `[25]`         |  `[proximity]`                  | `[Detects metal waste]`   |
| `[Power Supplyr]`                | `[1]`    | `[No]`  | `[Yes]`      | `[150]`        |  `[5V 2A supply]`               | `[Stable power for system]`|
| `[Servo Motor]`                  | `[1]`    | `[Yes]` | `[No]`       | `[0]`            | `[SG90]`                     | `[Opens the trapdoor]`|

## 11.2 Material Justification

Explain why you selected your main materials and components.

**Response:**  
`The system uses servo motors instead of DC motors or steppers because the application requires precise angular positioning (rotating to exact bin positions), not continuous rotation. A high-torque servo (MG995/MG996) is used for rotating the base because it can handle the weight of multiple bins, while a smaller servo (SG90) is sufficient for the trapdoor mechanism.
For sensing, a soil moisture sensor is selected for its simplicity and low cost to detect wet waste, and a magnet-based approach is used for metal detection since it is reliable and does not require complex circuitry. The Shrike Lite controller integrates all inputs and outputs, making it ideal for handling decision-making and control in a compact system.`


## 11.3 Items You chose

| Item                 | Why Needed               | Purchase Link | Latest Safe Date to Procure | Status       |
| -------------------- | ------------------------ | ------------- | --------------------------- | ------------ |
| `Cardboard`             | `Assembly`        | `Local store` | `28th April 2026`            | `[Received]` |

## 11.4 Budget Summary

| Budget Item           | Estimated Cost              |
| --------------------- | ---------------------------:|
| Electronics           | `[0]`                     |
| Mechanical parts      | `[0]`                      |
| Fabrication materials | `[0 (Available on campus)]` |
| Purchased extras      | `[50]`                       |
| Contingency           | `[]`                     |
| **Total**             | `[50]`                     |

## 11.5 Budget Reflection

If your cost is too high, what can be simplified, removed, substituted, or shared?

**Response:**  
`A single servo design (2-bin system instead of 3-bin) can also be used to reduce complexity and power requirements. Additionally, using available lab components instead of purchasing new ones helps minimize expenses while still maintaining a functional prototype.`


# 12. Planning the Work

## 12.1 Team Working Agreement

Write how your team will work together.

Include:

- how tasks are divided,
- how decisions are made,
- how progress will be checked,
- what happens if a task is delayed,
- how documentation will be maintained.

**Response:**  
**1. Task Division**

Faizan → Responsible for hardware design and assembly (circuit, sensors, structure).

Aditya → Responsible for testing and debugging (checking functionality, fixing errors).

Pushkar & Saloni → Responsible for documentation (report writing, diagrams, presentation, and explanation).

**2. Decision-Making Process**

All major decisions will be discussed as a team.

Final decisions will be made based on majority agreement.

In case of technical issues, the person responsible for that area (e.g., hardware or testing) will have the final say.

**3. Progress Tracking**

Progress will be checked at the end of each work session.

Each member will give a quick update on:

What was completed

What is pending

A simple checklist will be maintained to track tasks.

**4. Handling Delays**

If a task is delayed:

The member must inform the team immediately.

Other members will assist if needed.

Tasks may be redistributed to ensure project completion on time.

**5. Documentation Maintenance**

All documentation will be handled by Pushkar and Saloni.

Work will be updated regularly (not left for the last moment).

Final documents will include:

Circuit diagram

Working explanation

Images of the project

Code (if applicable)

**6. Team Commitment**

All members will communicate clearly and respect deadlines.

Everyone will contribute actively to ensure successful completion of the project.

## 12.2 Task Breakdown

| Task ID | Task                    | Owner    | Estimated Hours | Deadline     | Dependency | Status |
| ------- | ----------------------- | -------- | ---------------:| ------------ | ---------- | ------ |
| T1      | `problem statement `    | `[All]`  | `1`             | `none`       | `None`     | `Done` |
| T2      | `project design`        | `[Saloni]`    | `1`             | `none`       | `None`     | `Done` |
| T3      | `programing `           | `[Aditya]`    | `1`             | `none`       | `None`     | `Done` |
| T4      | `testing & debug`       | `[Faizan]`    | `2`             | `none`       | `None`     | `Done` |
| T5      | `documenatation `       | `[Pushkar]`    | `2`             | `none`       | `None`     | `Done` |
## 12.3 Responsibility Split

| Area                 | Main Owner | Support Owner |
| -------------------- | ---------- | ------------- |
| Concept              | `[Aditya & Faizan]`   | `[Pushkar & Saloni]`               |
| Electronics          | `[Faizan]`                 | `[Faizan and Saloni]`                               |
| Coding               | `[Aditya]`                 | `[Faizan]`                               |
| Mechanical build     | `[Saloni]`                 | `[Faizan and Aditya]`                               |
| Testing              | `[Faizan and Aditya]`                 | `[Saloni]`                               |
| Documentation        | `[Pushkar]`                  | `[Saloni]`                              |

---

# 13. 2 hour Milestones

## 13.1 8-hour Plan

### Bi Hour 1 — Plan and De-risk

Expected outcomes:

- [x] Idea finalized
- [x] Core interaction decided
- [x] Sketches made
- [x] BOM completed
- [x] Purchase needs identified
- [ ] Key uncertainty identified
- [x] Basic feasibility tested

### Bi Hour 2 — Build Subsystems

Expected outcomes:

- [x] Electronics tests completed
- [ ] CAD / structure planning completed
- [ ] App UI started if needed
- [x] Mechanical concept tested
- [ ] Main subsystems partially working

### Bi Hour 3 — Integrate

Expected outcomes:

- [x] Physical body built
- [x] Electronics integrated
- [x] Code connected to hardware
- [ ] App connected if required
- [x] First playable version exists

### Bi Hour 4 — Refine and Finish

Expected outcomes:

- [x] Technical bugs reduced
- [x] Playtesting completed
- [x] Improvements made
- [x] Documentation completed
- [ ] Final build ready

## 13.2  Update Log

| Hours   | Planned Goal   | What Actually Happened | What Changed   | Next Steps     |
| ------ | -------------- | ---------------------- | -------------- | -------------- |
| Hour 1 | `Idea finalization` | `Ideal Finalized`         | `[NA]` | `[Connection]` |
| Hour 2 | `[Hardware Finalization]` | `[Hardware connected]`| `Magnetic sensor changed with proximity sensor` | `Testing` |
| Hour 3 | `[Testing and Debugging]` | `[Tested all the components and testing the system working]`         | `[NA]` | `[Proper working]` |
| Hour 4 | `[Final product assembly]` | `[Working of the project]`         | `[NA]` | `[NA]` |

---
<img width="1600" height="1131" alt="image" src="https://github.com/pushjjjj/SKILLLAB__PROR_2026_group7/blob/main/images/geotag1.jpeg" />
  <img width="1600" height="1131" alt="image" src="https://github.com/pushjjjj/SKILLLAB__PROR_2026_group7/blob/main/images/final_output.jpeg" />                  
# 14. Risks and Unknowns

## 14.1 Risk Register

## 14.1 Risk Register

| Risk | Owner | Type | Likelihood | Impact | Mitigation Plan | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Servo Power Brownout** | `[Connection]` | `Electrical` | `High` | `High` | Use dedicated external 5V/2A power supply for MG995 servos; add 1000uF capacitor to power rail. | `[To Do]` |
| **Sensor Fouling** | `[Connection]` | `Maintenance` | `Medium` | `Medium` | Design sensing chamber for easy cleaning; implement software "auto-calibration" at startup. | `[To Do]` |
| **Mechanical Jamming** | `[Design]` | `Physical` | `Medium` | `High` | Use high-torque servos for trapdoor; design smooth-walled funnel for waste entry. | `[In Progress]` |
| **False Metal Detection** | `[Software]` | `Technical` | `Low` | `Medium` | Implement "signal debouncing" in Shrike Lite logic (require 5 consecutive high readings). | `[Pending]` |
| **Bin Misalignment** | `[Mechanical]` | `Mechanical` | `Medium` | `Medium` | Implement software offsets for 120°/240° positions; use mechanical hard-stops for 0° index. | `[To Do]` |


## 14.2 Biggest Unknown Right Now

What is the single biggest uncertainty in your project at this stage?

**Response:**  
Contamination (Fouling): In a waste system, "wet" doesn't just mean water; it means food waste, liquids, and grime. After just a few cycles, the moisture sensor will likely be coated in a thin film of residue. This can cause the sensor to remain "triggered" (high moisture) even after the bin is empty, leading the system to send all subsequent dry waste into the "Wet" bin.

---

# 15. Testing 

## 15.1 Technical Testing Plan

| What Needs Testing | How You Will Test It | Success Condition |
| :--- | :--- | :--- |
| **Power Stability** | Simultaneous MG995 movement. | No system reset; Voltage > 4.8V. |
| **Metal Logic** | Steel nut vs. plastic bottle. | 0° rotation for metal only. |
| **Moisture Logic** | Dry paper vs. wet sponge. | 240° for paper; 120° for sponge. |
| **Trapdoor Torque** | 100g load on door mechanism. | Smooth motion without jitter. |
## 15.2 Testing and Debugging Log

Date | Problem Found | Type | What You Tried | Result | Next Action |
| :--- | :--- | :--- | :--- | :--- | :--- |
| `28-Apr` | Base instability | Mech | Added caster support | **Worked** | Finalize housing |
| `28-Apr` | MG995 stuttering | Elec | Powered via Shrike Lite | **Failed** | Wire external 6V |
| `28-Apr` | False wet trigger | Tech | Wiped sensor probes | **Partial** | Code debounce logic |

## 15.3 Playtesting Notes

| Tester | What They Did | What Confused Them | What They Enjoyed | What You Will Change |
| :--- | :--- | :--- | :--- | :--- |
| `faizin` | Navigated car through obstacles. | Obstacles weren't visually clear. | Interaction between projection and car. | Add red highlights around obstacle zones. |
| `aditya` | Disposed of mixed waste items. | Delay between sensing and rotation. | Seeing the MG995 snap to the correct bin. | Optimize code delay; add a "Sensing..." LED. |
| `faizain` | Tested with wet cardboard. | Why it went to "Dry" instead of "Wet". | The touchless trapdoor mechanism. | Adjust moisture threshold; tilt sensor for contact. |


---

# 16. Build Documentation

## 16.1 Fabrication Process

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
he Smart Waste Segregation System was built as a compact, layered prototype using cardboard and basic mechanical components. The structure was divided into three main sections: the input and sensing chamber, the actuation mechanism, and the output bins.

---

1. Base Structure (Foundation)

A sturdy base platform was created using thick cardboard to support the entire system. A servo motor (MG996R) was fixed at the center of this base using glue and support brackets. A circular rotating platform was attached to the servo shaft. Three lightweight bins (plastic cups) were fixed evenly on this circular platform at 120° intervals to represent metal, wet, and dry waste bins.

---

2. Input Funnel and Sensing Chamber

Above the rotating base, a funnel-shaped input section was constructed using cardboard to guide waste into a small enclosed sensing chamber.

Inside this chamber:

- A PNP proximity sensor was mounted on the side wall to detect metallic objects.
- A soil moisture sensor was placed at the bottom so that the waste comes in contact with it to measure moisture content.

The chamber was designed to temporarily hold the waste during detection to prevent premature dropping.

---

3. Trapdoor Mechanism

At the bottom of the sensing chamber, a small flap (trapdoor) was installed using cardboard.
This flap was connected to a second servo motor, which controls its opening and closing.

- When closed → waste stays in the chamber
- When opened → waste falls into the bin below

This mechanism ensures controlled and accurate disposal.

---

4. Rotating Bin Mechanism

The three bins were mounted on a rotating circular plate attached to the MG996R servo motor.

Based on the classification:

- The servo rotates to a specific angle (0°, 120°, or 240°)
- The correct bin aligns directly below the trapdoor

This design ensures that the waste falls into the correct bin without needing multiple chutes.

---

5. Electronics Integration

The Shrike Lite controller was placed on the side of the structure for easy access. All sensors and servos were connected using jumper wires.

- The proximity sensor was powered using a 9V battery with a voltage divider for safe signal input.
- The soil moisture sensor was connected to an analog input pin.
- Both servos were powered using a stable 5V supply.
- All grounds were connected together to ensure proper operation.

---

6. Assembly and Finishing

All components were secured using a glue gun and tape. The structure was kept lightweight to reduce load on the servo motor. Labels were added to bins (Metal, Wet, Dry) for clarity.

The final prototype was compact, portable, and designed for easy demonstration.

## 16.2 Build Photos

Add photos throughout the project.

Suggested images:

- early sketch,
- prototype,
- electronics testing,
- mechanism test,
- app screenshot,
- final build.
- <img width="960" height="1280" alt="WhatsApp Image 2026-04-24 at 9 46 02 AM (1)" src="https://github.com/pushjjjj/SKILLLAB__PROR_2026_group7/blob/main/images/final_output.jpeg" />





# 17. Final Outcome

## 17.1 Final Description

Describe the final version of your project.

**Response:**  
The final project is a Smart Waste Segregation System controlled by the Shrike Lite controller, designed to automatically classify waste into three categories: metal, wet, and dry waste.

The system uses a PNP proximity sensor to detect metallic objects and a soil moisture sensor to identify wet waste. Based on the sensor inputs, the controller processes the data and determines the appropriate category. A high-torque servo motor (MG996R) rotates a circular base containing three bins to align the correct bin under the outlet. A second servo motor operates a trapdoor mechanism that releases the waste into the selected bin.

The entire setup is built using a layered structure with a sensing chamber at the top, a controlled drop mechanism in the middle, and a rotating bin system at the bottom. The system operates automatically with minimal human intervention and demonstrates an efficient prototype for waste segregation at the source.

---

## 17.2 What Works Well

- The system successfully detects metal waste using the proximity sensor with good reliability.
- The soil moisture sensor effectively differentiates wet and dry waste after proper calibration.
- The servo-based rotating mechanism accurately aligns the correct bin, ensuring proper segregation.
- The trapdoor mechanism provides controlled disposal, preventing incorrect dropping of waste.
- The system is fully automated and touchless, improving hygiene and ease of use.
- The overall design is compact, low-cost, and easy to demonstrate.


## 17.3 What Still Needs Improvement
- The accuracy of wet waste detection can vary depending on sensor calibration and type of material.
- The system cannot distinguish between different types of dry waste (e.g., plastic vs paper).
- The proximity sensor detects only certain metals, and may not detect non-ferrous metals like aluminum effectively.
- The mechanical structure made from cardboard can be improved for better durability and stability.
- The system processes one item at a time, and cannot handle bulk waste.
- Additional features like display, IoT monitoring, or advanced sensors can further enhance functionality.


## 17.4 What Changed From the Original Plan

How did the project change from the initial idea?

**Response:**  
Initially, the project idea focused on building a fully advanced waste segregation system with multiple sensors and complex detection methods. However, due to time constraints and component limitations, the design was simplified to ensure a reliable working prototype.

---

# 18. Reflection

## 18.1 Team Reflection

What did your team do well?  
What slowed you down?  
How well did you manage time, tasks, and responsibilities?

**Response:**  
18. Reflection

18.1 Team Reflection

Our team worked well in terms of collaboration and idea sharing. Each member contributed to different parts of the project such as coding, wiring, mechanical design, and documentation. We were able to divide tasks effectively, which helped us progress steadily.

However, some challenges slowed us down, especially during the initial stages when we were deciding the final design and understanding how to integrate sensors with the mechanical system. Debugging issues like sensor inaccuracies and servo power problems also took additional time.

Overall, we managed time reasonably well by completing the core functionality first and then improving the system step by step. Clear communication and teamwork helped us overcome difficulties and complete the project successfully.

---

## 18.2 Technical Reflection

What did you learn about:

- electronics,
- coding,
- mechanisms,
- fabrication,
- integration?

**Response:**  
Through this project, we gained practical knowledge in multiple technical areas:

- Electronics:
  We learned how to safely connect different components, manage power requirements (especially for servos), and ensure proper grounding to avoid unstable behavior.

- Coding:
  We improved our understanding of microcontroller programming, including reading sensor data, implementing decision logic, and controlling actuators like servo motors.

- Mechanisms:
  We learned how to design and implement mechanical systems such as a rotating base and a trapdoor mechanism, ensuring proper alignment and smooth operation.

- Fabrication:
  We developed skills in building prototypes using cardboard, glue, and simple tools while maintaining structural stability.

- Integration:
  The most important learning was integrating all components—sensors, controller, and mechanical parts—into a single working system. We understood that integration is more challenging than individual components.

---


## 18.3 Design Reflection

What did you learn about:

- designing ,
- delight,
- clarity,
- physical interaction,
- understanding,
- iteration?

**Response:**  
This project helped us understand important design principles:

- Designing:
  We learned to convert an idea into a physical system by breaking it into smaller functional blocks.

- Clarity:
  Keeping the system simple (metal, wet, dry) improved reliability and made it easier to explain and demonstrate.

- Physical Interaction:
  Designing a single input bin with automated segregation improved usability and hygiene.

- Understanding:
  We realized that users prefer systems that are intuitive and require minimal effort.

- Iteration:
  Our design evolved multiple times—from a complex system to a simpler, more reliable one. Each iteration improved performance and stability.

---

## 18.4 If You Had One More hour

What would you improve next?

**Response:**  

`If we had one more hour, we would:

- Improve the mechanical finishing to make the structure more stable and professional
- Fine-tune the sensor thresholds for more accurate detection
- Make the servo movements smoother and faster
- Add visual indicators like LEDs or a display for better user feedback

These improvements would enhance both the performance and presentation of the system. `

---

# 19. Final Submission Checklist

Before submission, confirm that:

- [x] Team details are complete
- [x] Project description is complete
- [x] Inspiration sources are included
- [x] Sketches are added
- [x] BOM is complete
- [x] Purchase list is complete
- [x] Budget summary is complete
- [x] Mechanical planning is documented if applicable
- [ ] App planning is documented if applicable
- [x] Code flowchart is added
- [x] Task breakdown is complete
- [x] Weekly logs are updated
- [x] Risk register is complete
- [x] Testing log is updated
- [x] Playtesting notes are included
- [x] Build photos are included
- [x] Final reflection is written
<img width="1131" height="1600" alt="image" src="" />

---


---


