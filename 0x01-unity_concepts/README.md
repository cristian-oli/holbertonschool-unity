# 0x01. Unity - Unity Concepts
## Details
      By Carrie Ybay, Software Engineer at Holberton School          Weight: 1                Ongoing project - started Apr 18, 2022 , must end by Apr 22, 2022           - you're done with 200% of tasks.              Checker will be released at Apr 20, 2022 12:00 AM        An auto review will be launched at the deadline      ## Concepts
For this project, students are expected to look at these concepts:
* [Install Unity3D](https://intranet.hbtn.io/concepts/88) 

* [Install Unity3D](https://intranet.hbtn.io/concepts/88) 

## Resources
Read or watch :
* [Unity Manual: GameObjects](https://intranet.hbtn.io/rltoken/AUA9J1q6DJfaWX2-BTb7dw) 

* [GameObjects and Components](https://intranet.hbtn.io/rltoken/3UIiXKpgYR6aw_zypM7EZw) 

* [Creating GameObjects and Types of GameObjects](https://intranet.hbtn.io/rltoken/OfVGXS7AlWg_yKEcTksL8w) 

* [Unity Manual: Components](https://intranet.hbtn.io/rltoken/gaHopVZVBtwZrkWPsBHqZQ) 

* [Components](https://intranet.hbtn.io/rltoken/TcpARIiqdJ1TmIEpXC9OyQ) 

* [Unity Manual: Prefabs](https://intranet.hbtn.io/rltoken/Ay8cQwWFh3GlcTUBORet6g) 

* [Creating and Using Prefabs](https://intranet.hbtn.io/rltoken/3yLeKfWA5Mzdj1yR6EVC0g) 

* [Unity Manual: Tags](https://intranet.hbtn.io/rltoken/zMVHYRfYWvFdsJehxZ1h3Q) 

* [Unity Manual: Layers](https://intranet.hbtn.io/rltoken/XVio6-PNR3ZmXGuYsEtrBw) 

* [The Beginner’s Guide to Game Mechanics](https://intranet.hbtn.io/rltoken/tFuCPP8fhZ2GzLeoWKCUow) 

* [The 13 Basic Principles of Gameplay Design](https://intranet.hbtn.io/rltoken/L-qQYJw60jqK1ioCrHIQVg) 
 (Read all 4 pages)
* [Gameplay and Game Mechanics Design: A Key to Quality in Videogames](https://intranet.hbtn.io/rltoken/nBirDzahZMxfOASWX7JoTA) 

* [Unity Manual](https://intranet.hbtn.io/rltoken/UZXixbexQ03CgIs4LNhIVQ) 

## Learning Objectives
At the end of this project, you are expected to be able to  [explain to anyone](https://intranet.hbtn.io/rltoken/xnNHjD6_TKCjWAieM7Z45A) 
 ,  without the help of Google :
### General
* What is a GameObject
* What is a Component
* What is a Prefab
* What is a Tag
* What is a Layer
* How to create and change the properties of a GameObject
* How to create a Prefab
* How to add Tags and Layers
* Why is it important to name GameObjects and assets clearly and organize your project hierarchy
* What are gameplay and game mechanics and how do they relate to developing any kind of interactive experience
## Requirements
### General
* A  ` README.md `  file, at the root of the folder of the project
* Use Unity’s default  ` .gitignore `  in your  ` holbertonschool-unity `  directory – you may need to edit it so that it applies to your entire repo
* Push the entire project folder  ` 0x01-unity_concepts `  to your repo, including  ` .meta `  files – make sure that any files/folders in the  ` .gitignore `  are not being pushed
* Scenes and project assets such as Materials must be named and organized as described in the tasks
* No scripts are allowed for this project
## Quiz questions
Great!          You've completed the quiz successfully! Keep going!          (Show quiz)#### 
        
        Question #0
    
 Quiz question Body What is a GameObject?
 Quiz question Answers * a 3D model

* a container for Components

* built-in game assets that come with Unity

 Quiz question Tips #### 
        
        Question #1
    
 Quiz question Body A GameObject must not be empty.
 Quiz question Answers * True

* False

 Quiz question Tips #### 
        
        Question #2
    
 Quiz question Body What Component is required for all GameObjects?
 Quiz question Answers * Transform

* Box Collider

* Size

 Quiz question Tips #### 
        
        Question #3
    
 Quiz question Body How can you add your own code as a Component of a GameObject?
 Quiz question Answers * right-click on the GameObject in the Hierarchy window and choose “Add Script”

* add a new Script Component to the GameObject in the Inspector window

* drag a script from the Project window to the GameObject’s Inspector window

 Quiz question Tips #### 
        
        Question #4
    
 Quiz question Body What is a Prefab?
 Quiz question Answers * a built-in game asset that comes with Unity

* a template created from an existing GameObject and its components and properties

* a Component of a GameObject

 Quiz question Tips #### 
        
        Question #5
    
 Quiz question Body What are the benefits of using Prefabs?
 Quiz question Answers * Prefabs can be used to make copies easily of a GameObject and make changes to all of them efficiently

* Prefabs can be used in multiple scenes

* Prefabs don’t need Components to edit their properties

 Quiz question Tips #### 
        
        Question #6
    
 Quiz question Body How could you use Tags in a Unity project?
 Quiz question Answers * to sort GameObjects in the Project window

* to organize Components in a GameObject

* to identify and organize GameObjects for scripting purposes

 Quiz question Tips #### 
        
        Question #7
    
 Quiz question Body A GameObject can have multiple Tags assigned to it.
 Quiz question Answers * True

* False

 Quiz question Tips #### 
        
        Question #8
    
 Quiz question Body What is the purpose of Layers?
 Quiz question Answers * to render only part of a scene

* to restrict raycasting to only specific parts of a scene

* to keep track of scene drafts

 Quiz question Tips #### 
        
        Question #9
    
 Quiz question Body What is gameplay?
 Quiz question Answers * The game controller / keyboard controls used in interacting with a game

* How a player interacts with a game

* A rule designed for a player’s interaction with the game

 Quiz question Tips #### 
        
        Question #10
    
 Quiz question Body What are game mechanics?
 Quiz question Answers * The inner workings of a game’s engine

* How a player interacts with a game

* A set of rules designed for the player’s interaction with the game

 Quiz question Tips ## Tasks
### 0. Floor plans
          mandatory         Progress vs Score  Task Body Create a new 3D Unity project called   ` 0x01-unity_concepts `  . Save your new scene as   ` 0-floor `  . Create a new Cube GameObject named   ` Floor `   with the following Transform properties:
* Position:  ` X: 0 ` ,  ` Y: 0 ` ,  ` Z: 0 ` 
* Rotation:  ` X: 0 ` ,  ` Y: 0 ` ,  ` Z: 0 ` 
* Scale:  ` X: 16 ` ,  ` Y: 0.5 ` ,  ` Z: 16 ` 
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-unity ` 
* Directory:  ` 0x01-unity_concepts ` 
* File:  ` 0x01-unity_concepts/Assets/Scenes/0-floor.unity ` 
 Self-paced manual review  Panel footer - Controls 
### 1. On the ball
          mandatory         Progress vs Score  Task Body Duplicate   ` 0-floor `   by selecting the scene in the Project window and either   ` Edit > Duplicate `   from the Toolbar or   ` CTRL / CMD + D `  . Rename the scene   ` 1-ball `   and open it. Create a new Sphere GameObject named   ` Ball `   with the following Transform properties:
* Position:  ` X: 0 ` ,  ` Y: 8 ` ,  ` Z: 0 ` 
* Rotation:  ` X: 0 ` ,  ` Y: 0 ` ,  ` Z: 0 ` 
* Scale:  ` X: 1.5 ` ,  ` Y: 1.5 ` ,  ` Z: 1.5 ` 
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-unity ` 
* Directory:  ` 0x01-unity_concepts ` 
* File:  ` 0x01-unity_concepts/Assets/Scenes/1-ball.unity ` 
 Self-paced manual review  Panel footer - Controls 
### 2. Colors!
          mandatory         Progress vs Score  Task Body Duplicate   ` 1-ball `  , rename it   ` 2-colors `  , and open it. Create a   ` Materials `   folder in the Project window, then create a new material named   ` floor `  . In the Inspector window, change the Albedo color to any color you like using the color picker. Assign the material to the Floor GameObject.
Create a second new material named   ` ball `  . Change the material color and assign the new material to the Ball GameObject.
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-unity ` 
* Directory:  ` 0x01-unity_concepts ` 
* File: ```bash
0x01-unity_concepts/Assets/Scenes/2-colors.unity, 0x01-unity_concepts/Assets/Materials/floor.mat, 0x01-unity_concepts/Assets/Materials/ball.mat
```

 Self-paced manual review  Panel footer - Controls 
### 3. Gravity is a harsh mistress
          mandatory         Progress vs Score  Task Body Duplicate   ` 2-colors `  , rename it   ` 3-gravity `  , and open it. Add a Rigidbody Component to the Ball GameObject. Press Play to see what happens. Wouldn’t it be better if the ball bounced when it fell?
Create a new folder in the Project window named   ` Physic Materials `   and create a new Physic Material called   ` bounce `  . Feel free to edit the material’s settings to get an idea of what the different settings affect. Add the   ` bounce `   material to the Ball’s Sphere Collider. Press   ` Play `  . For this task, your final   ` bounce `   material settings should be:
*  ` Bounciness: 0.8 ` 
*  ` Bounce Combine: Maximum ` 
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-unity ` 
* Directory:  ` 0x01-unity_concepts ` 
* File: ```bash
0x01-unity_concepts/Assets/Scenes/3-gravity.unity, 0x01-unity_concepts/Assets/Physic Materials/bounce
```

 Self-paced manual review  Panel footer - Controls 
### 4. Prefabricated
          mandatory         Progress vs Score  Task Body Duplicate   ` 3-gravity `  , rename it   ` 4-prefab `  , and open it. Create a new folder named   ` Prefabs `  . Create a prefab from the Ball inside the new folder, then, using the prefab, add four more instance of the Ball to the scene. Position and scale them any way you like.
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-unity ` 
* Directory:  ` 0x01-unity_concepts ` 
* File:  ` 0x01-unity_concepts/Assets/Scenes/4-prefab.unity, 0x01-unity_concepts/Assets/Prefabs/Ball ` 
 Self-paced manual review  Panel footer - Controls 
### 5. Even more colors!
          mandatory         Progress vs Score  Task Body Duplicate   ` 4-prefab `  , rename it   ` 5-more_colors `  , and open it. Change the colors of each ball so they are different hex colors as defined below. New materials should be named as listed below. You cannot use scripts in this task.
*  ` ball-red `  :  ` FF0000FF ` 
*  ` ball-blue `  :  ` 0000FFFF ` 
*  ` ball-green `  :  ` 00FF00FF ` 
*  ` ball-white `  :  ` FFFFFFFF ` 
*  ` ball-black `  :  ` 000000FF ` 
Take a look at the Hierarchy window. Having a bunch of GameObjects with the same name is hard to navigate, right? It’s important to clearly name your GameObjects and assets, especially when working with others in the same project. Rename each Ball GameObject in your scene with their color name.
*  ` Red Ball ` 
*  ` Blue Ball ` 
*  ` Green Ball ` 
*  ` White Ball ` 
*  ` Black Ball ` 
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-unity ` 
* Directory:  ` 0x01-unity_concepts ` 
* File:  ` 0x01-unity_concepts/Assets/Scenes/5-more_colors.unity, 0x01-unity_concepts/Assets/Materials/ball-* ` 
 Self-paced manual review  Panel footer - Controls 
### 6. Tag yourself
          mandatory         Progress vs Score  Task Body Duplicate   ` 5-more_colors `  , rename it   ` 6-tags `  , and open it. Add a tag to all Ball objects called   ` Obstacles `  .
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-unity ` 
* Directory:  ` 0x01-unity_concepts ` 
* File:  ` 0x01-unity_concepts/Assets/Scenes/6-tags.unity, 0x01-unity_concepts/Assets/Prefabs/Ball.prefab ` 
 Self-paced manual review  Panel footer - Controls 
### 7. Textures
          #advanced         Progress vs Score  Task Body Duplicate   ` 6-tags `  , rename it   ` 100-textures `  , and open it. Create a new instance of Ball named   ` Textured Ball `   and add a texture to it. Your texture asset should be in a folder named   ` Textures `   and your new material should be called   ` ball-texture `  .
Free Texture Sources:
* [textures.com](https://intranet.hbtn.io/rltoken/gvVcxLjQYYNQQo4wHrvEOw) 

* [texturex.com](https://intranet.hbtn.io/rltoken/scl6bmXu0u0VNznolGZRVA) 

* [Unity Asset Store](https://intranet.hbtn.io/rltoken/JgJhgq2oJz76jk5bjek5MA) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-unity ` 
* Directory:  ` 0x01-unity_concepts ` 
* File: ```bash
0x01-unity_concepts/Assets/Scenes/100-textures.unity, 0x01-unity_concepts/Assets/Materials/ball-texture, 0x01-unity_concepts/Assets/Textures/<texture_name>
```

 Self-paced manual review  Panel footer - Controls 