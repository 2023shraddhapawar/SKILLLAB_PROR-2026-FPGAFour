# SKILL LAB PRATICAL HACKATHON

## Final Project README

> **Project Weight:** 100%  
> **Team Size:** 4/3 students  
> **Project Duration:** 16 hours  
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

`Project^2`

## 1.2 Team Members

| Name                  | Primary Role                    | Secondary Role   | Strengths Brought to the Project |
| --------------        | ------------------------------- | --------------   | -------------------------------- |
| `Shraddha Pawar` | `[Electronics / Coding / App ]` | `Documentation`  | `Documentation, Gift of Gab `|
| `Shubham Surve` | `[Electronics / Coding / App ]` | `Documentation`  | `Documentation, Gift of Gab `|
| `Soham Baing` | `[Electronics / Coding / App ]` | `Documentation`  | `Documentation, Gift of Gab `|
| `Gauransh Dubey` | `[Electronics / Coding / App ]` | `Documentation`  | `Documentation, Gift of Gab `|

## 1.3 FPGAFour

`"Project Project"`

`(because Project-or)`

<img width="1600" height="1131" alt="image" src="https://github.com/user-attachments/assets/c64bfbd4-b3b7-43d9-83ad-c203a5aa11bc" />

## 1.4 One-Line Pitch

`A programmable FPGA-based smart traffic light system that efficiently controls road traffic using real-time signal timing and digital logic implementation on a Boolean board.`

## 1.5 Expanded Project Idea

**Response:**  
`The Smart Traffic Light Control System is a hardware-based traffic management project designed using Vivado software and implemented on an FPGA Boolean board. The system controls traffic lights at an intersection by managing red, yellow, and green signals in a predefined sequence using digital logic circuits. It can be programmed to adjust signal timing, improving traffic flow and reducing waiting time.

This project creates a practical embedded systems experience by combining hardware programming, digital circuit design, and real-time control systems. It demonstrates how FPGA technology can be used in smart city applications for reliable and fast signal processing. The project involves technologies such as Verilog/VHDL coding, FPGA implementation, Vivado Design Suite, Boolean board interfacing, and sequential logic design.`

---

# 2. Inspiration

## 2.1 References

List what inspired the project.

| Source Type        | Title / Link                         | What Inspired You                                                                                    |
| ------------------ | ------------------------------------ | ---------------------------------------------------------------------------------------------------- |
| Real-world System  | Urban Traffic Signal Control Systems | Inspired the idea of improving traffic management through automation and smart timing control.       |
| Software Tool      | Vivado Design Suite                  | Inspired the implementation of digital logic design and FPGA programming for real-time applications. |
| Hardware Platform  | FPGA Boolean Board                   | Inspired the use of reconfigurable hardware for efficient traffic signal control.                    |
| Technology Concept | Digital Logic Design                 | Inspired the finite state machine and sequential logic approach used in traffic light sequencing.    |

## 2.2 Original Twist

What makes your project original?

**Response:**  

Unlike traditional timer-based traffic light systems, our project uses an FPGA-based programmable controller designed in Vivado Design Suite on a Boolean board, which offers high-speed parallel processing, reliability, and real-time control. The system is modular and can be expanded with vehicle density sensors, pedestrian crossing buttons, emergency vehicle priority, and adaptive signal timing. This makes it closer to a smart city traffic solution rather than a basic digital electronics project.---

# 3. Project Intent

## 3.1 User Journey 

Describe exactly how a user will use the project.Make it a story
**Response:**  
Imagine a busy road intersection during peak hours. Normally, vehicles wait unnecessarily because traffic lights follow fixed timing regardless of road congestion. With our Smart Traffic Light Control System, the FPGA board continuously runs programmed traffic sequences with precise timing and fast switching control.

When the system starts, lights begin in a safe default state—Red ON for one road, Green ON for the other. After the programmed interval, signals change smoothly through Yellow to Red/Green transitions. If future sensors are added, the FPGA can quickly adjust timing based on traffic density.

For the user (operator/demo viewer), the experience is simple: power ON the Boolean board, observe the synchronized LED traffic signals, and monitor how digital logic controls real-world traffic behavior efficiently, accurately, and safely.
                                                  |



---

# 4. Definition of Success

## 4.1 Definition of “Usable”

The project is usable when the FPGA successfully controls Red, Yellow, and Green LEDs in proper sequence with correct timing and no signal conflict.

## 4.2 Minimum Usable Version

What is the smallest version of this project that still delivers the core experience?

**Response:**  

A basic 2-road traffic signal controller where one road gets Green while the other remains Red, followed by Yellow transition, then the sequence switches.## 4.3 Stretch Features

What features are nice to have but not essential?

Vehicle density sensing
Pedestrian crossing button
Emergency vehicle override
Night mode flashing signal
Countdown timer display using 7-segment display
IoT monitoring dashboard

---

# 5. System Overview

## 5.1 Project Type

- [x] Electronics-based

- [ ] Mechanical

- [x] Sensor-based

- [ ] App-connected

- [ ] Motorized

- [ ] Sound-based

- [x] Light-based

- [x] Screen/UI-based

- [x] Fabricated structure

- [ ] Game logic based

- [x] Installation

- [ ] Other:

## 5.2 High-Level System Description

Explain how the system works in simple terms.

Include:

- input,
- processing,
- output,
- physical structure,
- app interaction if any.

**Response:**  
The system accepts timing/input parameters, processes them using FPGA logic (Finite State Machine), and outputs control signals to LEDs representing traffic lights. The Boolean board acts as the hardware controller, while Vivado is used for simulation, synthesis, and implementation.
## 5.3 Input / Output Map

| System Part             | Type       | What It Does               |
| ----------------------- | ---------- | -------------------------- |
| Clock Input             | Input      | Controls timing sequence   |
| Reset Button            | Input      | Restarts traffic cycle     |
| Sensor Input (optional) | Input      | Detects traffic density    |
| FPGA Logic              | Processing | Runs signal algorithm      |
| LEDs                    | Output     | Shows traffic signal state |
| Display Module          | Output     | Shows timer/countdown      |


# 6. System Design, Sketches and Visual Planning 

## 6.1 Concept Architecture/sketch/schematic

Add an early sketch of the full idea.

**Insert image below:**  
``

Example:

```md

```



## 6.2 Labeled Build Sketch/architecture/flow diagram/algorithm

Add a sketch with labels showing:

- structure,
- electronics placement,
- user touch points,
- moving parts,
- output elements.

**Insert image below:**  
`[Upload image and link here]`
<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/95637f31-b4e7-4427-a9e1-4b63fbeb0ac5" />

## 6.3 Approximate Dimensions

| Dimension        | Value |
| ---------------- | ----- |
| Length           | 16 cm |
| Width            | 16 cm |
| Height           | 6 cm  |
| Estimated weight | 300 g |


---

# 7. Electronics Planning

## 7.1 Electronics Used

| Component               | Quantity | Purpose                  |
| ----------------------- | -------- | ------------------------ |
| FPGA Boolean Board      | 1        | Main controller          |
| LEDs (Red/Yellow/Green) | 6–12     | Signal indication        |
| Resistors               | 6–12     | Current limiting         |
| Push Buttons            | 2        | Reset / pedestrian input |
| Breadboard              | 1        | Circuit setup            |
| Jumper Wires            | Multiple | Connections              |
| Power Supply            | 1        | Board powering           |

## 7.2 Wiring Plan

Describe the main electrical connections.

**Response:**  
`The FPGA Boolean board GPIO pins are connected to Red, Yellow, and Green LEDs through current-limiting resistors. Each traffic lane has a dedicated LED set representing signal states. Push buttons are connected to FPGA input pins for reset and optional manual override. A common ground is maintained throughout the circuit for stable operation. The clock signal is generated internally on FPGA, and all traffic light transitions are controlled through programmed state logic.`

## 7.3 Circuit Diagram/architecture diagram

Insert a hand-drawn or software-made circuit diagram.

**Insert image below:**  
`[Upload image and link here]`
<img width="867" height="1156" alt="" src="" />


# 7.4. Power Plan

| Question         | Response                             |
| ---------------- | ------------------------------------ |
| Power source     | USB / DC Adapter                     |
| Voltage required | 5V                                   |
| Current concerns | Low current LED load                 |
| Safety concerns  | Avoid short circuits and overvoltage |


---

# 8. Software Planning/

## 8.1 Software Tools

| Tool / Platform      | Purpose                  |
| -------------------- | ------------------------ |
| Vivado Design Suite  | FPGA coding + simulation |
| Verilog HDL          | Logic design             |
| Xilinx Programmer    | Upload bitstream         |
| Circuit design tools | Diagram creation         |


## 8.2 Software Logic/Algorithm

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
`The software logic for the Smart Traffic Light Control System is designed using Verilog HDL in Vivado Design Suite and implemented on an FPGA Boolean board. The system uses a Finite State Machine (FSM) to control the sequence of Red, Yellow, and Green lights for two intersecting roads.`

- **Startup behavior:**  
  When powered ON, the FPGA initializes the system in a safe default state, where Road A is Green and Road B is Red, while an internal timer starts counting.
- **Input handling:**  
The system continuously monitors the clock signal and reset button. Optional inputs like pedestrian buttons or traffic sensors can also be added in future versions.
- **Sensor reading:**
  Currently, timing is controlled internally, but the design supports future integration of sensors to detect vehicle density and adjust signal timing accordingly.
- **Decision logic:**  
  The FSM changes states in a fixed sequence—Green → Yellow → Red—based on timer values, ensuring that both roads never receive Green at the same time.
- **Output behavior:**  
  The FPGA sends output signals to LEDs, switching Red, Yellow, and Green lights according to the current state.
- **Communication logic:**  
  All processing happens internally on the FPGA using counters, registers, and logic circuits for fast and reliable operation.
- **Reset behavior:**  
  Pressing reset clears the timer and returns the system to its default starting state for a fresh traffic cycle.

## 8.3 Code Flowchart

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
<img width="1600" height="1200" alt="image" src="" />
<img width="1600" height="1200" alt="image" src="" />




# 9. Bill of Materials

## 9.1 Full BOM

| Item                       | Quantity | In Kit? | Need to Buy? | Estimated Cost | Material / Spec        | Why This Choice?                  |
| -------------------------- | -------: | ------- | ------------ | -------------: | ---------------------- | --------------------------------- |
| FPGA Boolean Board         |        1 | Yes     | No           |              0 | FPGA Development Board | Main controller for traffic logic |
| LEDs (Red, Yellow, Green)  |     6–12 | No      | Yes          |           ₹100 | 5mm LEDs               | To represent traffic signals      |
| Resistors                  |     6–12 | Yes     | No           |              0 | 220Ω / 330Ω            | Current limiting for LEDs         |
| Push Buttons               |        2 | Yes     | No           |              0 | Digital input switch   | Reset / manual input              |
| Breadboard                 |        1 | Yes     | No           |              0 | Standard breadboard    | Easy circuit connections          |
| Jumper Wires               | Multiple | Yes     | No           |              0 | Male-to-Male wires     | Interconnections                  |
| Power Supply / USB Cable   |        1 | Yes     | No           |              0 | 5V supply              | Powers FPGA board                 |
| Display Board / Model Road |        1 | No      | Yes          |           ₹150 | Foam board / cardboard | For project demonstration         |



## 9.2 Material Justification

Explain why you selected your main materials and components.

**Response:**  
`DC motors (BO motors) were chosen instead of servos or steppers because the system requires continuous rotation for movement rather than precise angular control (Previously, we were considering using steppers as we were planning on tracking movement on the ESP using its relative position from an origin, but since we're using a camera now, this is not required). A motor driver (L298N) was used to allow bidirectional control and speed variation using PWM.`


## 9.3 Items You chose

| Item                   | Why Needed               | Purchase Link           | Latest Safe Date to Procure | Status   |
| ---------------------- | ------------------------ | ----------------------- | --------------------------- | -------- |
| LEDs Set               | Traffic light indication | Local electronics store | Before assembly             | Received |
| Breadboard             | Circuit setup            | Local store             | Before testing              | Received |
| Jumper Wires           | Connections              | Lab kit / store         | Before testing              | Received |
| Foam Board / Cardboard | Road intersection model  | Local stationery shop   | Before demo                 | Pending  |
| Extra Push Buttons     | Reset / optional control | Local electronics store | Before testing              | Received |


## 9.4 Budget Summary


| Budget Item           | Estimated Cost              |
| --------------------- | ---------------------------:|
| Electronics           | `[400]`                     |
| Mechanical parts      | `[200]`                     |
| Fabrication materials | `[0 (Available on campus)]` |
| Purchased extras      | `[0]`                       |
| Contingency           | `[300]`                     |
| **Total**             | `[900]`                     |

## 9.5 Budget Reflection

If your cost is too high, what can be simplified, removed, substituted, or shared?

**Response:**  

---

# 10. Planning the Work

## 10.1 Team Working Agreement

Write how your team will work together.

Include:

- how tasks are divided,
- how decisions are made,
- how progress will be checked,
- what happens if a task is delayed,
- how documentation will be maintained.

**Response:**  


## 10.2 Task Breakdown

| Task ID | Task                    | Owner    | Estimated Hours | Deadline     | Dependency | Status |
| ------- | ----------------------- | -------- | ---------------:| ------------ | ---------- | ------ |
| T1      | `[Finalize concept]`    | `[Both]` | `2`             | `1st April`  | `None`     | `Done` |


## 10.3 Responsibility Split

| Area                 | Main Owner     | Support Owner |
| -------------------- | ----------     | ------------- |
| Concept              | `[Mrugendra]`  | `[Jyoti]`     |
| Electronics          | `[]`           | `[]`          |
| Coding               | `[]`           | `[]`          |
| Mechanical build     | `[]`           | `[]`          |
| Testing              | `[]`           | `[]`          |
| Documentation        | `[]`           | `[]`          |

---

# 11 hour Milestones

## 11.1 8-hour Plan(tentetively you may set)

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
- [x] Main subsystems partially working

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

## 12.2  Update Log

| Days   | Planned Goal   | What Actually Happened | What Changed   | Next Steps     |
| ------ | -------------- | ---------------------- | -------------- | -------------- |
| Day 1 | `[Write here]` | `[Write here]`         | `[Write here]` | `[Write here]` |
| Day 2 | `[Write here]` | `[Write here]`         | `[Write here]` | `[Write here]` |
| Day 3 | `[Write here]` | `[Write here]`         | `[Write here]` | `[Write here]` |
| Day 4 | `[Write here]` | `[Write here]`         | `[Write here]` | `[Write here]` |

---

# 13. Risks and Unknowns

## 13.1 Risk Register

| Risk                                                            | Type         | Likelihood | Impact   | Mitigation Plan                                                                       | Owner                |
| --------------------------------------------------------------- | ------------ | ---------- | -------- | ------------------------------------------------------------------------------------- | -------------------- |
| WiFi connection between laptop and ESP32 becomes unstable       | `Technical`  | `Medium`   | `High`   | Keep ESP32 close, ensure stable power supply, reduce network load, add fail-safe stop | `[Gopal]`           |


## 13.2 Biggest Unknown Right Now

What is the single biggest uncertainty in your project at this stage?

**Response:**  


---

# 14. Testing 

## 14.1 Technical Testing Plan

| What Needs Testing     | How You Will Test It                                                                 | Success Condition                                                                                    |
| ---------------------- | ------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------- |
| `[Wifi connection]`    | `[Check if motor spins via app button]`                                              | `[Both motors accurately respond to wifi signals]`                                                   |
                       |
## 14.2 Testing and Debugging Log

| Date          | Problem Found                         | Type         | What You Tried                                | Result               | Next Action                                    |
| ------------- | ------------------------------------- | ------------ | --------------------------------------------- | -------------------- | ---------------------------------------------- |
| `18th April`  | `Car not balancing properly`          | `Mechanical` | `Add low-friction caster support to one side` | `Worked`             | `improve caster structure`                     |


## 14.3 Playtesting Notes

| Tester      | What They Did                        | What Confused Them                    | What They Enjoyed                         | What You Will Change                          |
| ----------- | ------------------------------------ | ------------------------------------- | ----------------------------------------- | --------------------------------------------- |
| `Gopal` | `Tried navigating through obstacles` | `Some obstacles ewren't clear enough` | `Liked projection + real car interaction` | `Add a slight red highlight around obstacles` |


---

# 15. Build Documentation

## 15.1 Fabrication Process(if any)

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

## 16 Build Photos

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


