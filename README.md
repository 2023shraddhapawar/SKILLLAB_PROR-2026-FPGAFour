# SKILL LAB PRATICAL HACKATHON

## Final Project README

> **Project Weight:** 100%  
> **Team Size:** 4/3 students  
> **Project Duration:** 16 hours  
> **Total Time Available:** 32 effort-hours per team  
> **Project Type:** Playful, interactive, technology-based experience

---

# 1. Team Identity

## 1.1 FPGAFour




## 1.2 Team Members

| Name                  | Primary Role                    | Secondary Role   | Strengths Brought to the Project |
| --------------        | ------------------------------- | --------------   | -------------------------------- |
| `Shraddha Pawar` | `Documentation` | `Implementation of FPGA`  | ` Documentation `|
| `Shubham Surve` | `Coding` | `Vivado synthesis`  | ` Vivado synthesis `|
| `Soham Baing` | ` Coding ` | `Vivado synthesis`  | `Coding`|
| `Gauransh Dubey` | `Implementation of FPGA` | `Hardware`  | `Hardware`|

## 1.3 FPGAFour

<img width="1254" height="1254" alt="poster" src="https://github.com/user-attachments/assets/d4d71825-2fed-49b7-a4b6-8673aa20c623" />


## 1.4 One-Line Pitch

`A programmable FPGA-based smart traffic light system that efficiently controls road traffic using real-time signal timing and digital logic implementation on a Boolean board.`

## 1.5 Expanded Project Idea


`The Smart Traffic Light Control System is a hardware-based traffic management project designed using Vivado software and implemented on an FPGA Boolean board. The system controls traffic lights at an intersection by managing red, yellow, and green signals in a predefined sequence using digital logic circuits. It can be programmed to adjust signal timing, improving traffic flow and reducing waiting time.

This project creates a practical embedded systems experience by combining hardware programming, digital circuit design, and real-time control systems. It demonstrates how FPGA technology can be used in smart city applications for reliable and fast signal processing. The project involves technologies such as Verilog/VHDL coding, FPGA implementation, Vivado Design Suite, Boolean board interfacing, and sequential logic design.`

---

# 2. Inspiration

## 2.1 References


| Source Type        | Title / Link                         | What Inspired You                                                                                    |
| ------------------ | ------------------------------------ | ---------------------------------------------------------------------------------------------------- |
| Real-world System  | Urban Traffic Signal Control Systems | Inspired the idea of improving traffic management through automation and smart timing control.       |
| Software Tool      | Vivado Design Suite                  | Inspired the implementation of digital logic design and FPGA programming for real-time applications. |
| Hardware Platform  | FPGA Boolean Board                   | Inspired the use of reconfigurable hardware for efficient traffic signal control.                    |
| Technology Concept | Digital Logic Design                 | Inspired the finite state machine and sequential logic approach used in traffic light sequencing.    |

## 2.2 Original Twist

Unlike traditional timer-based traffic light systems, our project uses an FPGA-based programmable controller designed in Vivado Design Suite on a Boolean board, which offers high-speed parallel processing, reliability, and real-time control. The system is modular and can be expanded with vehicle density sensors, pedestrian crossing buttons, emergency vehicle priority, and adaptive signal timing. This makes it closer to a smart city traffic solution rather than a basic digital electronics project.---

# 3. Project Intent

## 3.1 User Journey 
  
Imagine a busy road intersection during peak hours. Normally, vehicles wait unnecessarily because traffic lights follow fixed timing regardless of road congestion. With our Smart Traffic Light Control System, the FPGA board continuously runs programmed traffic sequences with precise timing and fast switching control.

When the system starts, lights begin in a safe default state—Red ON for one road, Green ON for the other. After the programmed interval, signals change smoothly through Yellow to Red/Green transitions. If future sensors are added, the FPGA can quickly adjust timing based on traffic density.

For the user (operator/demo viewer), the experience is simple: power ON the Boolean board, observe the synchronized LED traffic signals, and monitor how digital logic controls real-world traffic behavior efficiently, accurately, and safely.
                                                  

# 4. Definition of Success

## 4.1 Definition of “Usable”

The project is usable when the FPGA successfully controls Red, Yellow, and Green LEDs in proper sequence with correct timing and no signal conflict.

## 4.2 Minimum Usable Version

A basic 2-road traffic signal controller where one road gets Green while the other remains Red, followed by Yellow transition, then the sequence switches.

## 4.3 Strech Features

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


<img width="1536" height="1024" alt="rough" src="https://github.com/user-attachments/assets/42af5c90-457c-430f-83bc-d7ecf40aa5d6" />



## 6.2 Labeled Build Sketch/architecture/flow diagram/algorithm


<img width="1536" height="1024" alt="cktdiagg" src="https://github.com/user-attachments/assets/d2991fa9-74a2-4edf-b163-a40b2870daae" />



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
| LEDs |   16    | Signal indication        |
| Push Buttons            | 4        | Reset / pedestrian input |
| Power Supply            | 1        | Board powering           |

## 7.2 Wiring Plan

`The FPGA Boolean board GPIO pins are connected to LEDs. Push buttons are connected to FPGA input pins for reset and optional manual override. A common ground is maintained throughout the circuit for stable operation. The clock signal is generated internally on FPGA, and all traffic light transitions are controlled through programmed state logic.`

## 7.3 Circuit Diagram/architecture diagram

Insert a hand-drawn or software-made circuit diagram.

**Insert image below:**  

<img width="1536" height="1024" alt="circuitdiagram" src="https://github.com/user-attachments/assets/d93d075e-2274-404c-847d-1d8f8c463694" />


# 7.4. Power Plan

| Question         | Response                             |
| ---------------- | ------------------------------------ |
| Power source     | USB / DC Adapter                     |
| Voltage required | 5V                                   |
| Current concerns | Low current LED load                 |
| Safety concerns  | Avoid short circuits and overvoltage |


---

# 8. Software Planning

## 8.1 Software Tools

| Tool / Platform      | Purpose                  |
| -------------------- | ------------------------ |
| Vivado Design Suite  | FPGA coding + simulation |
| Verilog HDL          | Logic design             |
| Xilinx Programmer    | Upload bitstream         |
| Circuit design tools | Diagram creation         |


## 8.2 Software Logic/Algorithm
 
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

<img width="1149" height="1369" alt="flowchart" src="https://github.com/user-attachments/assets/72d536fe-a237-4c80-b7aa-9b73f161226f" />


# 9. Bill of Materials

## 9.1 Full BOM

| Item                       | Quantity | In Kit? | Need to Buy? | Estimated Cost | Material / Spec        | Why This Choice?                  |
| -------------------------- | -------: | ------- | ------------ | -------------: | ---------------------- | --------------------------------- |
| FPGA Boolean Board         |        1 | Yes     | No           |              0 | FPGA Development Board | Main controller for traffic logic |
| LEDs   |     16 | No      | Yes          |           ₹100 | 5mm LEDs               | To represent traffic signals      |
| Push Buttons               |        4 | Yes     | No           |              0 | Digital input switch   | Reset / manual input              |
| Power Supply   |        1 | Yes     | No           |              0 | 5V supply              | Powers FPGA board                 |
| Display Board  |        1 | No      | Yes          |           ₹150 |  | For project demonstration         |



## 9.2 Material Justification

`DC motors (BO motors) were chosen instead of servos or steppers because the system requires continuous rotation for movement rather than precise angular control (Previously, we were considering using steppers as we were planning on tracking movement on the ESP using its relative position from an origin, but since we're using a camera now, this is not required). A motor driver (L298N) was used to allow bidirectional control and speed variation using PWM.`


## 9.3 Items You chose

| Item                   | Why Needed               | Purchase Link           | Latest Safe Date to Procure | Status   |
| ---------------------- | ------------------------ | ----------------------- | --------------------------- | -------- |
| LEDs Set               | Traffic light indication | Local electronics store | Before assembly             | Received |
| FPGA                   | Implementation           | 401 Lab                 | Before assembly             | Received |


## 9.4 Budget Summary

| Budget Item     | Estimated Cost |
| --------------- | -------------- |
| Electronics     | ₹100           |
| Fabrication     | ₹100           |
| Extra materials | ₹100           |
| Contingency     | ₹200           |
| **Total**       | **₹500**       |


## 9.5 Budget Reflection

The project cost is low because the FPGA board and most components are available in the lab. Additional expenses are limited to LEDs and display materials.

# 10. Planning the Work

## 10.1 Team Working Agreement


Task division: coding, circuit setup, testing, and documentation are divided equally among team members.

## 10.2 Task Breakdown

| Task ID | Task                                                   | Owner | Estimated Hours | Deadline   | Dependency | Status      |
| ------- | ------------------------------------------------------ | ----- | --------------: | ---------- | ---------- | ----------- |
| T1      | Finalize project concept and design                    | Team  |               2 | 30st April  | None       | Done        |
| T2      | Create circuit setup on Boolean Board                  | Shubham, Gauransh  |               3 | 30th April  | T1         | Done        |
| T3      | Write and simulate Verilog code in Vivado Design Suite | Shubham, Soham, Gauransh  |               4 | 30th April | T2         | Done        
| T4      | Implement on FPGA and test LEDs                        | Shraddha, Soham |               3 | 30th April | T3         | Done        |
| T5      | Final testing and documentation                        | Shraddha  |               6 | 1th May | T4         | Done |

## 10.3 Responsibility Split

| Area                 | Main Owner     | Support Owner |
| -------------------- | ----------     | ------------- |
| Concept              | `[Team]`  | `[Team]`     |
| Electronics          | `[Shubham]`           | `[Soham]`          |
| Coding               | `[Soham]`           | `[Gauransh]`          |
| Mechanical build     | `[Gauransh]`           | `[Shubham]`          |
| Testing              | `[Shubham]`           | `[Shraddha]`          |
| Documentation        | `[Shraddha]`           | `[-]`          |

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
| Days  | Planned Goal                                                             | What Actually Happened                                                                                                                                                                             | What Changed                                                                                               | Next Steps                                         |
| ----- | ------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | -------------------------------------------------- |
| Day 1 | Complete project design, coding, simulation, hardware setup, and testing | The traffic light logic was designed in Vivado Design Suite, simulated successfully, uploaded to the FPGA Boolean Board, and tested using onboard LEDs. The core project was completed in one day. | Used normal onboard LEDs instead of separate Red, Yellow, and Green LEDs, which simplified implementation. | Start documentation and collect screenshots/photos |
| Day 2 | Complete documentation, screenshots, and final report preparation        | Circuit diagrams, flowcharts, simulation screenshots, testing details, reflections, and final report formatting were completed. All project images and records were organized for submission.      | Minor edits were made to improve clarity and presentation quality.                                         | Final submission                                   |


# 13. Risks and Unknowns

## 13.1 Risk Register

| Risk                          | Type      | Likelihood | Impact | Mitigation Plan                                       | Owner |
| ----------------------------- | --------- | ---------- | ------ | ----------------------------------------------------- | ----- |
| Incorrect FPGA pin assignment | Technical | Medium     | High   | Verify constraints file and pin mapping before upload | Team  |
| Timing sequence mismatch      | Technical | Medium     | Medium | Test simulation in Vivado before implementation       | Team  |
| LED output not working        | Hardware  | Low        | Medium | Check wiring and FPGA output pins                     | Team  |
| Reset button malfunction      | Technical | Low        | Low    | Add proper debounce / verify input logic              | Team  |


## 13.2 Biggest Unknown Right Now

The biggest uncertainty is how efficiently the system can be expanded in the future to include traffic sensors and adaptive signal timing while maintaining simple FPGA logic.


# 14. Testing 

## 14.1 Technical Testing Plan

| What Needs Testing | How You Will Test It            | Success Condition                    |
| ------------------ | ------------------------------- | ------------------------------------ |
| LED sequence       | Observe output LEDs on board    | LEDs change in correct traffic order |
| Timing delay       | Count signal switching interval | Delay remains consistent             |
| Reset button       | Press reset during operation    | System returns to default state      |
| FPGA programming   | Upload code and run             | Board executes design successfully   |


## 14.2 Testing and Debugging Log

| Date       | Problem Found                         | Type      | What You Tried                              | Result | Next Action      |
| ---------- | ------------------------------------- | --------- | ------------------------------------------- | ------ | ---------------- |
| 30th April | LEDs not blinking in correct sequence | Technical | Checked FSM state transitions in simulation | Worked | Test on hardware |
| 30th April | Wrong output pin mapping              | Hardware  | Updated constraints file                    | Worked | Re-test board    |
| 30th April | Reset not restarting properly         | Technical | Modified reset logic in Verilog             | Worked | Final testing    |


## 14.3 Playtesting Notes

| Tester       | What They Did                 | What Confused Them            | What They Enjoyed               | What You Will Change           |
| ------------ | ----------------------------- | ----------------------------- | ------------------------------- | ------------------------------ |
| Team Members | Observed LED traffic sequence | Timer was not working properly | Liked real-time hardware output | Increase visible delay         |

---

# 15. Build Documentation

## 15.1 Fabrication Process(if any)

`The project was built mainly through electronic assembly and FPGA programming rather than mechanical fabrication. The traffic controller logic was designed in Vivado Design Suite using Verilog HDL and simulated before hardware implementation.

The FPGA Boolean Board was connected to LEDs through basic circuit wiring. Normal onboard LEDs were used to represent traffic signals. The output pins were mapped correctly using the constraints file, and testing was done by observing LED switching patterns.

Several revisions were made in timing values, output mapping, and reset behavior to ensure smooth and correct operation of the traffic light sequence.`


## 16 Build Photos


<img width="3024" height="4032" alt="booleanboard" src="https://github.com/user-attachments/assets/a6b3081f-e737-4465-8e07-021e1295a9fc" />



<img width="4160" height="3120" alt="setup" src="https://github.com/user-attachments/assets/af13b5c5-8a0f-490b-a005-3dbf54faf0db" />


# 17. Final Outcome

## 17.1 Final Description

The final project is a working Smart Traffic Light Controller implemented on an FPGA Boolean Board using Vivado Design Suite. It successfully controls onboard normal LEDs in a timed sequence to simulate traffic light operation using digital logic and Finite State Machine design.

## 17.2 What Works Well

Correct traffic light sequence execution
Stable FPGA operation
Reliable reset functionality
Accurate timing control
Successful hardware implementation on Boolean Board


## 17.3 What Still Needs Improvement

Add external traffic LEDs for better visualization
Include vehicle density sensors
Improve real-world smart traffic adaptability

## 17.4 What Changed From the Original Plan

Initially, the project idea included separate Red, Yellow, and Green LEDs for realistic traffic signal representation. During implementation, we switched to using the normal onboard LEDs available on the Boolean Board, which simplified wiring and made implementation easier. The core traffic logic remained unchanged, but hardware setup became simpler and more compact.
---

# 18. Reflection

## 18.1 Team Reflection

Our team worked well in dividing tasks between coding, hardware setup, testing, and documentation. Good communication helped solve technical issues quickly. Debugging FPGA pin mapping and timing delays took extra time, but overall tasks were completed on schedule.

## 18.2 Technical Reflection

We learned practical implementation of digital logic design, Verilog coding, FPGA programming, simulation in Vivado, circuit connections, and debugging hardware-software integration.

## 18.3 Design Reflection

We learned that simple design can still demonstrate strong concepts clearly. Careful planning, proper timing control, and repeated testing improved the final project significantly.

## 18.4 If You Had One More hour

`We would add sensor-based adaptive traffic control to make the system more interactive and closer to a real smart city traffic signal system. `

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
