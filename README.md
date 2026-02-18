## Instructions
Put each week's activities under new headers like the one shown above. Headers are created with the # symbol. More # symbols = smaller header.

## W1
### Activity 1
Read the rubric carefully, make sure every point works.
make sure to playtest you itch link, send it to your classmates.

### Activity 2.
1. 10
2. 2
3. printMessage prints "hello world"
4. Monobehavior
5. it gives PrintMessage a value of 10 and store it in parameter x, then Debug.Log prints x = 10.
6. argument string parameter, the purpose is to give printMessage a value, then print "x =" and the value of parameter x.
7. Transform is a class, you can't call Translate on Transform it self, you need a specific object.
8. Change Transform to a specific object name, for example _playerTransform.

### Activity 3
https://docs.google.com/document/d/1f7G4mzHXPIyRTfI2d5UnagogdDLsxSn7crcgg0hPKuU/edit?usp=sharing

## W2
### Activity 1 
![IMG_6292](https://github.com/user-attachments/assets/6eb71aa5-741c-49aa-95bf-f38b9d2dc8f6)

### Activity 2
[MG2 commit](https://github.com/UCI-GDIM32-W25/mg2-Huhrz/commits/main/)

I set up the basic MG2 gameplay structure by implementing the player jump mechanic and starting the coin spawning system. I also began organizing scripts for player control, coins, and UI updates.

## W3
### Activity 0-2
Allen Hu Tiancheng Li

### Activity 3
![IMG_3703](https://github.com/user-attachments/assets/e3b99a62-776b-435a-96a9-f9f09be94879)

## W4
### Activity 0
Tiancheng Li

### Activity 1
When multiple Locator objects are added to the Scene and the game runs, only one Locator remains active while the others destroy themselves. This happens because the Locator uses the Singleton pattern, which ensures there is only one valid instance at runtime. This confirms the Singleton is working correctly and prevents conflicting references to the player.

### Activity 2
![IMG_6453](https://github.com/user-attachments/assets/9d192b67-b24e-46e9-85e2-8124fe716189)

### Activity 3
[MG4 Commit](https://github.com/Huhrz/HW4/commit/f1ea86d28c2d4ded54a5d95e5df39ce5275dade3)
I made the objects that i think will be used in MG4, and i finished the BirdControl script that makes the bird flap when you tap Space.

## W5

### Activity 1
The design separates shared behavior (Item) from optional capabilities (IBreakable). For me, I’d keep this structure but refine it by reducing duplicated durability logic, for example, with a shared breakable base class and making values like durability data-driven so designers can tune them easily. Overall, the idea is solid, but I’d slightly refactor it to scale better and avoid repetition.

### Activity 2
Model: EnemeyState,ItemW5Demo2  
Veiw: DialogueBubble, InventoryUI  
Controller: EnemyW5Demo2, PlayerW2Demo2

### Activity 3
#### Scenario 1
Use ScriptableObjects to represent each beat as data (key, screen position, timestamp), the spawner/manager can use an MVC setup where the song timer triggers events and the view spawns the correct beat visuals, while beat behavior uses polymorphism if different beat types have different hit rules.

#### Scenario 2
Use a base abstract character class + interfaces for shared systems (health, movement, weapon handling), then implement unique attacks as modular components using polymorphism (each ability/attack overrides a shared “Execute” style method). Use a Finite State Machine for movement/combat/animation states.

#### Scenario 3
Use interfaces/abstract classes,  so rocks, crops, and seeds share interactions without one giant inheritance tree. Store crop/tool/object stats in ScriptableObjects for easy tuning.


### Activity 4
Attendence: Allen Hu, Tiancheng Li, Yaokun Wan  
Proposal: [Final Project Proposal First Draft](https://docs.google.com/document/d/1fnsY2dn8RalB8GGQmQtA4OftlRL5nsa3st6-GqeGGi8/edit?usp=sharing)


## W6

### Activity 1
Gizmos: Gizmos will help us visualize interaction ranges, such as the trigger distance for NPC dialogue and item interaction. This will make it much easier to debug positioning issues in our small office environment and ensure players can clearly access tasks.

Profiling: Because our game includes timers, audio layers, dialogue systems, and state machines, profiling will help us monitor performance and prevent lag. It ensures that slow mechanics (like printer loading) are intentional design choices, not performance problems.

Breakpoint: Our project includes multiple systems. Breakpoints will help us debug state transitions and task completion logic, ensuring the game behaves correctly under pressure scenarios.

### Activity 2

Attendence: Allen Hu, Tiancheng Li, Yaokun Wan  
Proposal: [Final Project Proposal Final Draft](https://docs.google.com/document/d/1fnsY2dn8RalB8GGQmQtA4OftlRL5nsa3st6-GqeGGi8/edit?usp=sharing)


## W7

### Activity 1
The duck switches between these states based on whether a raycast detects the player, which simulates line of sight and shows how physics checks can control behavior. When pursuing, the duck calculates a normalized direction vector toward the player and rotates smoothly using Vector3.RotateTowards, creating more natural movement. When wandering, it randomly chooses directions and uses a SphereCast to detect obstacles, allowing it to avoid walls instead of getting stuck.

### Activity 2
Attendence: Allen Hu, Tiancheng Li, Yaokun Wan   

### Activity 3
![IMG_6731](https://github.com/user-attachments/assets/16307d67-ccc1-4642-bf7b-47f67b48fbe4)

### Activity 4
[Tasks](https://docs.google.com/document/d/1rLxHEqQ7WVbr2whNHvd6AkNOCeKE-MZJDp9sczpUW1g/edit?usp=sharing)

### Activity 5
[Commit](https://github.com/TianchengLiRed/GDIM32-Final/commit/8595fdfeb056aa962a07be319db024e67af8c04f)


