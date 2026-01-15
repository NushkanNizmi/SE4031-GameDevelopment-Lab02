# Lab 02 – Main Project Setup (VR Core Template) + Locomotion + Folders

Unity Version: 2022.3 LTS  
Lab Duration: 2 Hours  
This project continues until Lab 09.

---

## Objective

To create the main VR project using Unity’s VR Core Template, set up the correct project folder structure, save the main scene, and configure locomotion (teleport + smooth movement) inside a simple test room.

---

## Learning Outcomes

After completing this lab, students will be able to:

- Create a VR project using the VR Core Template
- Create the required folder structure for all labs
- Save the main scene correctly in the Scenes folder
- Identify key VR rig components (camera, controllers)
- Build a simple test room (floor + walls)
- Configure teleport locomotion using Teleportation Area
- Enable smooth locomotion using Continuous Move Provider (Action-based)
- Produce a short demonstration video for submission

---

## Step-by-Step Instructions

### 1) Create Project (VR Core)
Unity Hub → New Project  
Template: **VR Core**  
Project Name: VR_PartA_<ITNo>


---

### 2) Create Folder Structure (Must Match)
Inside `Assets`, create folder: _Project

Inside `Assets/_Project`, create:

- Scenes
- Scripts
- Prefabs
- Materials
- Audio
- UI

---

### 3) Save Main Scene
File → Save As  
Save to: Assets/_Project/Scenes/ 

Name: << Name Your Scene >> Eg : Main.unity


---

### 4) Understand Player Rig (Do NOT Delete)
In Hierarchy, locate the VR rig (XR Origin / Player).  
Expand and confirm:

- Main Camera
- Left Hand
- Right Hand

---

### 5) Create a Simple Test Room
Create floor:
3D Object → Plane → rename `Floor`

Create walls:
3D Object → Cube → scale and position 4 walls around the floor.

---

### 6) Verify Teleport
Select `Floor`  
Add Component → `Teleportation Area` (if missing)  
Press Play and verify teleport works.

---

### 7) Enable Smooth Movement (If Supported)
Select XR Origin / Player  
Add Component → `Continuous Move Provider (Action-based)`  
Set Move Speed = 1.5

---

## Submission Task (Video)

Record a 45–60 second screen recording showing:

- Teleport or smooth movement working
- Your test room
- Main scene saved in the correct folder

File name: Lab02_<ITNo>.mp4


Commit and push the video file to your GitHub Classroom repository.

---

## Next Lab

Lab 03: Environment setup with materials and lighting (VR safe design)

---

Lab sheet created by **Nushkan Nismi**.





