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
| `Saloani Sawant` | `[Electronics / Coding / App ]` | `Documentation`  | `Documentation, Gift of Gab `|
| `Pushkar Sawlani`  | `[Electronics / Fabrication]`   | `[Coding]`     | `Material Handling, Hardware`    |
| `Faizan Shah` | `[Electronics / Coding / App ]` | `Documentation`  | `Documentation, Gift of Gab `|
| `Aditya Singh`  | `[Electronics / Fabrication]`   | `[Coding]`     | `Material Handling, Hardware`    |

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
`An Intelligent Waste Classification System is a smart prototype that automatically identifies and separates waste into categories such as metal, wet, and dry. The system uses a single input bin where the waste is first analyzed using simple sensing methods—magnetic detection for metals and a moisture sensor for wet waste. Based on this classification, a controller processes the data and activates a mechanical system that directs the waste into the appropriate bin, ensuring efficient and organized disposal.
The system creates a real-time, interactive experience where users can observe how waste is detected and sorted automatically without manual effort. It combines sensor-based decision-making with mechanical automation, making the process both educational and practical. Technologies involved include a Shrike Lite controller, servo motors for rotating the bin base and operating a trapdoor, and sensors like a soil moisture sensor and magnet-based detection. This project demonstrates how basic electronics and automation can contribute to smarter waste management solutions.`

---

# 2. Philosophy Fit

## 2.1 Experience, Not Social Problem

`The project creates an interactive and engaging experience where users can observe how a system intelligently identifies and sorts waste in real time. When an item is dropped into the top bin, the system pauses briefly to analyze it, then smoothly rotates the base and releases the waste into the correct compartment. This sequence—detect, decide, rotate, and drop—gives a clear visual understanding of how automation and decision-making work together, making the system feel responsive and “intelligent.”
From a user’s perspective, the experience is simple and intuitive: just drop an item and watch the system handle the rest. The motion of the rotating base, the timing of the trapdoor, and optional feedback like LEDs or buzzer signals make the process dynamic and easy to follow. It demonstrates how sensors, controllers, and actuators can be combined to create a smart, automated system, turning a basic action into an engaging technological interaction.`





# 3. Inspiration

## 3.1 References

List what inspired the project.

| Source Type | Title / Link                                                        | What Inspired You                                                                         |
| ----------- | ------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| `[Video]`   | `https://www.instagram.com/reel/DW4CT7WCDry/?igsh=cXg3dzAxYmdncDBo` | `How projection mapping can be used to create interactive digital + physical experiences` |
|             |                                                                     |                                                                                           |
|             |                                                                     |                                                                                           |

## 3.2 Original Twist

What makes your project original?

**Response:**  
`What makes this project original is its combination of sensing, decision-making, and mechanical movement in a compact, single-input design. Instead of using separate bins or a simple drop mechanism, the system first holds the waste in a sensing chamber, classifies it, and only then uses a servo-driven rotating base to align the correct bin before releasing it through a controlled trapdoor. This “detect → decide → rotate → drop” sequence makes the system more structured and reliable compared to basic sorting prototypes.
Another unique aspect is the hybrid classification approach using simple, low-cost methods—magnetic detection for metal and moisture sensing for wet waste—while assigning everything else as dry waste. This keeps the system practical and easy to build, yet still demonstrates intelligent automation. The integration of multiple mechanisms (dual servo control, rotating platform, and staged processing) gives the project a more advanced and polished feel, making it stand out as both a mechanical and electronics-based innovation rather than just a basic sensor demo.`

---

# 4. Project Intent

## 4.1 User Journey 

Describe exactly how a user will use the project.Make it a story
**Response:** 
`Riya stood in front of what looked like an ordinary dustbin, turning a small metal bottle cap in her hand. “It’s just a bin,” she thought—until she noticed a small label: Intelligent Waste Classification System. Curious, she dropped the cap into the opening.
Instead of falling straight down, the cap seemed to pause inside. For a second, nothing happened. Then she heard a soft hum. Inside the system, something was deciding. The base beneath began to rotate slowly, almost like it knew exactly where to go. Suddenly, a small flap opened, and the cap dropped neatly into one of the hidden bins below. A tiny LED blinked, confirming the action. Riya smiled, impressed.
She tried again, this time with a piece of wet tissue. The same process repeated—pause, think, rotate, drop—but this time the base stopped at a different position. It felt almost alive, like the bin was “understanding” what she gave it. What seemed like a simple dustbin had turned into an interactive experience—one where every drop of waste triggered a quiet moment of intelligence, making her see something ordinary in a completely new way.`
                                                  



---

# 5. Definition of Success

## 5.1 Definition of “Usable”
`A system is considered “usable” when a user can interact with it easily and achieve the intended outcome without confusion or assistance. In this project, usability means that a user can simply drop waste into the input bin and the system will automatically detect, classify, and direct it into the correct compartment without requiring any additional steps. The process should feel intuitive, smooth, and reliable, with clear feedback such as visible movement of the rotating base or indicator signals (LED or buzzer) confirming the action.
Additionally, the system should perform consistently under normal conditions, with minimal errors in classification and stable mechanical operation. The components should respond quickly, and the entire sequence—from detection to disposal—should occur within a few seconds. A usable system also implies that it is safe to handle, easy to demonstrate, and understandable to observers, making it suitable for real-world application as well as educational purposes.`


## 5.2 Minimum Usable Version

What is the smallest version of this project that still delivers the core experience?

**Response:**  
## 5.2 Minimum Usable Version

`The smallest version of this project that still delivers the core experience is a **two-category system (Metal vs Normal waste)** using a **single input bin, one detection method, and one servo mechanism**. In this version, the user drops waste into the top chamber, where a simple **magnet-based detection** identifies whether the item is metal. Based on this, a **single servo motor** rotates or directs the waste toward either the metal bin or the normal waste bin. This keeps the system simple while still demonstrating the key idea of automated classification and sorting.
Even without multiple sensors or advanced features, this minimal setup still provides the essential experience: the system detects, makes a decision, and physically directs the waste accordingly. The user can clearly observe the sequence—input, detection, movement, and output—which is the core concept of the project. Additional features like wet waste detection, LEDs, or a rotating multi-bin base can be added later, but this basic version is enough to show a working, intelligent waste classification system.`


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
`Once the decision is made, a servo motor rotates the base so that the correct bin is aligned below the chamber. Then, a small trapdoor (controlled by another servo) opens, and the waste drops into the selected bin. The system may also give feedback using an LED or buzzer.`
`4. Physical Structure`
`The system has a top input bin, a middle sensing chamber, and a bottom rotating platform with three bins attached. The servo motor is placed at the center to rotate the base, and another servo controls the trapdoor. The structure can be built using cardboard or lightweight materials.`
`5. App Interaction (if any)`
`In the basic version, there is no mobile app involved. The system works automatically based on sensors and programmed logic. However, in advanced versions, an app or display can be added to show waste type or system status.`

## 6.3 Input / Output Map

| System Part                              | Type            | What It Does                                                               |
 Top Input Bin / Funnel                    | input           | Receives waste from the user and guides it into the sensing chamber
 Magnet (Metal Detection)                  | input           | Identifies if the waste is metal based on magnetic attraction
 Soil Moisture / Capacitive Sensor         | input           | Detects moisture level to classify wet waste
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
<img width="1600" height="1200" alt="image" src="https://github.com/pushjjjj/SKILLLAB__PROR_2026_group7/blob/main/images/7.2_Labled_sketch.jpeg" />


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
The system monitors for input using an ultrasonic sensor (if used) or assumes input when waste is placed in the chamber. Once an object is detected, the system temporarily pauses further actions to allow stable sensor readings.

**Sensor Reading**
The controller reads data from the sensors:
Checks magnetic condition (metal detection using magnet logic)
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
Optional: activates LED or buzzer to indicate the detected category

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
<img width="1600" height="1200" alt="image" src="https://github.com/pushjjjj/SKILLLAB__PROR_2026_group7/blob/main/images/7.1_concept_sketch.jpeg" />




# 11. Bill of Materials

## 11.1 Full BOM

| Item                             | Quantity | In Kit? | Need to Buy? | Estimated Cost | Material / Spec               | Why This Choice?          |
| -------------------------------- | --------:| ------- | ------------ | --------------:| ----------------------------- | ------------------------- |
| `[Shrike Lite Controller]`       | `1`      | `Yes`   | `No`         | `0`            | `Microcontroller board`       | `[To control components]` |
| `[Servo Motor]`                  | `[1]`    | `[Yes]` | `[No]`       | `0`            | `[MG995]`                     | `[Rotates base with bins]`|
| `[Soil Moisture Sensor]`         | `[1]`    | `[No]`  | `[Yes]`      | `[0]`          | `analog sensor`               | `[Detects wet waste]`     |
| `[Magnet]`                       | `[1]`    | `[No]`  | `[Yes]`      | `[25]`         |  `proximity`                  | `[Detects metal waste]`   |
| `[Power Supplyr]`                | `[1]`    | `[No]`  | `[Yes]`      | `[150]`        |  `5V 2A supply`               | `[Stable power for system]`|

## 11.2 Material Justification

Explain why you selected your main materials and components.

**Response:**  
`The system uses servo motors instead of DC motors or steppers because the application requires precise angular positioning (rotating to exact bin positions), not continuous rotation. A high-torque servo (MG995/MG996) is used for rotating the base because it can handle the weight of multiple bins, while a smaller servo (SG90) is sufficient for the trapdoor mechanism.
For sensing, a soil moisture sensor is selected for its simplicity and low cost to detect wet waste, and a magnet-based approach is used for metal detection since it is reliable and does not require complex circuitry. The Shrike Lite controller integrates all inputs and outputs, making it ideal for handling decision-making and control in a compact system.`


## 11.3 Items You chose

| Item                 | Why Needed               | Purchase Link | Latest Safe Date to Procure | Status       |
| -------------------- | ------------------------ | ------------- | --------------------------- | ------------ |
| `magnet`             | `Metal detection`        | `local store` | `before testing`            | `[Received]` |
| `5V Power Supply`    | `Stable power 0f 5v`     | `local store` | `before testing`            | `[Received]` |
| `Extra jumper wires` | `Backup connections`     | `local store` | `before testing`            | `Recieved`   |

## 11.4 Budget Summary

| Budget Item           | Estimated Cost              |
| --------------------- | ---------------------------:|
| Electronics           | `[150]`                     |
| Mechanical parts      | `[50]`                      |
| Fabrication materials | `[0 (Available on campus)]` |
| Purchased extras      | `[0]`                       |
| Contingency           | `[200]`                     |
| **Total**             | `[400]`                     |

## 11.5 Budget Reflection

If your cost is too high, what can be simplified, removed, substituted, or shared?

**Response:**  
If the cost needs to be reduced further, the system can be simplified by removing optional components such as the ultrasonic sensor, LEDs, and buzzer, as they do not affect the core functionality. A single servo design (2-bin system instead of 3-bin) can also be used to reduce complexity and power requirements. Additionally, using available lab components instead of purchasing new ones helps minimize expenses while still maintaining a functional prototype.
---

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
| T1      | `[Finalize concept]`    | `[Both]` | `2`             | `1st April`  | `None`     | `Done` |


## 12.3 Responsibility Split

| Area                 | Main Owner | Support Owner |
| -------------------- | ---------- | ------------- |
| Concept              | `[Gopal]`  | `[Kader]`    |
| Electronics          | `[]`       | `[]`     |
| Coding               | `[]`       | `[]`     |
| Mechanical build     | `[]`       | `[]`    |
| Testing              | `[]`       | `[]`    |
| Documentation        | `[]`       | `[]`     |

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
- [x] Final build ready

## 13.2  Update Log

| Hours   | Planned Goal   | What Actually Happened | What Changed   | Next Steps     |
| ------ | -------------- | ---------------------- | -------------- | -------------- |
| Hour 1 | `Idea finalization` | `Ideal Finalized`         | `[NA]` | `[Connection]` |
| Hour 2 | `[Hardware Finalization]` | `[Hardware connected]`| `Magnetic sensor changed with proximity sensor` | `Testing` |
| Hour 3 | `[Write here]` | `[Write here]`         | `[Write here]` | `[Write here]` |
| Hour 4 | `[Write here]` | `[Write here]`         | `[Write here]` | `[Write here]` |

---
<img width="1600" height="1131" alt="image" src="https://github.com/pushjjjj/SKILLLAB__PROR_2026_group7/blob/main/images/geotag1.jpeg" />
# 14. Risks and Unknowns

## 14.1 Risk Register

| Risk                                                            | Type         | Likelihood | Impact   | Mitigation Plan                                                                       | Owner                |
| --------------------------------------------------------------- | ------------ | ---------- | -------- | ------------------------------------------------------------------------------------- | -------------------- |
| WiFi connection between laptop and ESP32 becomes unstable       | `Technical`  | `Medium`   | `High`   | Keep ESP32 close, ensure stable power supply, reduce network load, add fail-safe stop | `[Gopal]`           |


## 14.2 Biggest Unknown Right Now

What is the single biggest uncertainty in your project at this stage?

**Response:**  


---

# 15. Testing 

## 15.1 Technical Testing Plan

| What Needs Testing     | How You Will Test It                                                                 | Success Condition                                                                                    |
| ---------------------- | ------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------- |
| `[Wifi connection]`    | `[Check if motor spins via app button]`                                              | `[Both motors accurately respond to wifi signals]`                                                   |
                       |
## 15.2 Testing and Debugging Log

| Date          | Problem Found                         | Type         | What You Tried                                | Result               | Next Action                                    |
| ------------- | ------------------------------------- | ------------ | --------------------------------------------- | -------------------- | ---------------------------------------------- |
| `18th April`  | `Car not balancing properly`          | `Mechanical` | `Add low-friction caster support to one side` | `Worked`             | `improve caster structure`                     |


## 15.3 Playtesting Notes

| Tester      | What They Did                        | What Confused Them                    | What They Enjoyed                         | What You Will Change                          |
| ----------- | ------------------------------------ | ------------------------------------- | ----------------------------------------- | --------------------------------------------- |
| `Gopal` | `Tried navigating through obstacles` | `Some obstacles ewren't clear enough` | `Liked projection + real car interaction` | `Add a slight red highlight around obstacles` |


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
`The fabrication process involved designing, manufacturing, assembling, and refining both the physical structure and electronic integration of the system.`

`Design (CAD Modeling):
The initial model was created using CAD software, where components were designed based on the actual dimensions of the electronic parts. This ensured accurate fitting and minimized errors during assembly.
Cutting (Laser Cutting):
The designed parts were fabricated using laser cutting techniques. Sheets were cut precisely according to the CAD model to create the structural base and mounts for components.`

`Components were fixed using adhesives and mechanical supports. Certain parts were intentionally kept modular (not permanently fixed) to allow easy replacement and modification of electronics.
Surface Finishing:
Some parts were sanded to smooth rough edges after cutting. Sawdust mixed with adhesive was used to fill gaps and uneven edges, improving structural finish. The final structure was then painted for better aesthetics and durability.`

`Environment Setup (Dark Room Fabrication):
To enhance projection visibility, a controlled dark environment was created using Z-boards, paper sheets, and bedsheets. This minimized external light interference and improved projection clarity.
Revisions and Iterations:
Multiple adjustments were made throughout the process, including refining alignment, improving structural stability, repositioning components, and optimizing the interaction between the physical car and projected environment.`

## 16.2 Build Photos

Add photos throughout the project.

Suggested images:

- early sketch,
- prototype,
- electronics testing,
- mechanism test,
- app screenshot,
- final build.
- <img width="960" height="1280" alt="WhatsApp Image 2026-04-24 at 9 46 02 AM (1)" src="https://github.com/user-attachments/assets/74baa570-5770-483e-be6d-d2f03386e37c" />





# 17. Final Outcome

## 17.1 Final Description

Describe the final version of your project.

**Response:**  


## 17.2 What Works Well



## 17.3 What Still Needs Improvement


## 17.4 What Changed From the Original Plan

How did the project change from the initial idea?

**Response:**  


---

# 18. Reflection

## 18.1 Team Reflection

What did your team do well?  
What slowed you down?  
How well did you manage time, tasks, and responsibilities?

**Response:**  


## 18.2 Technical Reflection

What did you learn about:

- electronics,
- coding,
- mechanisms,
- fabrication,
- integration?

**Response:**  


## 18.3 Design Reflection

What did you learn about:

- designing ,
- delight,
- clarity,
- physical interaction,
- understanding,
- iteration?

**Response:**  


## 18.4 If You Had One More hour

What would you improve next?

**Response:**  

` `

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


