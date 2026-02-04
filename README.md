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


### Activity 4
Proposal: [Final Project Proposal First Draft](https://docs.google.com/document/d/1fnsY2dn8RalB8GGQmQtA4OftlRL5nsa3st6-GqeGGi8/edit?usp=sharing)

