[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: [your name]
### Student number: [your student number] 

This document discusses and reflects on the design of your platformer level for the Level Design assessment. It should be 1500 words. Make sure you delete this and all other instructional text throughout the document before checking your word count prior to submission. Hint: You can check word count by copying this text into a Word or Google doc.

Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:

```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

Name: Shayl 

Student Number: 47133443 

My Level design attempts to provide experiences of discovery, drama, challenge and exploration through teaching players core mechanics of the game. The 3 sections of the level each help familiarize the player with the game’s core mechanics and gameplay. The level was strongly inspired by the first level of Mega Man X by CAPCOM, with its intensity steadily increasing as the player learns the controls through gameplay. After the player gets comfortable with both the movement from the platforming section and the gun from the combat section respectively, they progress onto the final section that combines elements from both previous sections. This layout helps facilitate a sense of discovery as the player combines what they’ve learnt, and gains a sense of victory after completing the objective. 

(DocImages/<Level Design Overview.png>) 

Section 1 is layed out in a way that provides players with a simple obstacle course, having them become familiar with the 3 different kinds of platforms: Stationary, PassThroughPlatform and MovingPlatform. These are introduced as one obstacle at a time, before combining them at the end of the section. This slowly increases the intensity and allows the player to confirm their own mastery of the game’s movement. 

Section 2 intends to have a similar level of simplicity in it’s obstacles, as its section is layed out flat, so players are able to take on the new barriers one at a time. The moment they reach the section, they are met with a weapon, the gun (/Gun_Pickup). With this, they can take on the enemy that will shortly begin attacking them, the spitter (/Spitter1), which they can swiftly take out and move onto the next enemy, the chomper (/Chomper1). Unlike the spitter from earlier, the chomper is set on the ground, meaning a standing player’s shots will pass over them. Therefore the player is driven to experiment a bit more, before they crouch and shoot.  

At the end of section 2, there is an area blocked by a PassThrough wall with a similar body that gave the gun earlier (/PassThroughPlatform2, /Staff_Pickup). Given there is not way through, players will move forward up the Moving Platform until they see both a way down into the secret area, and given the players noting the Passthrough wall earlier, are able to understand going down will not be a tolling detour. Should they decide to go through with that decision, they will be rewarded with a new melee weapon, the staff. 

The third and final section serves as a test for players to apply what they’ve learnt into action. While Section 1 and Section 2 each taught separate mechanics in their respective controlled environments, Section 3 combines those mechanics into an arena of platforming and combat.  

The 3 sections of the level are positioned in a way that allows players to explore the level in their own path, while still being able to backtrack and explore other areas (/section 1, /section 2, /section 3). This was implemented to guide players to a sense of discovery and exploration when playing the level. Similarly, after defeating the enemies and progressing through section 2, players have an option to step off the moving platform that would take them to the final section and key, where they can pick up an optional 2nd weapon (/WeaponPickupStaff). Players - after completing section 2 – would see this weapon pickup through the wall on the right of the moving platform, giving them the agency to make a decision on whether or not to explore that area (/PassThroughPlatformLong).  

Acid: Acid pits would be a core factor of the platforming element, so it was implemented as the first obstacle of Section 1, and also one of the first few things the player sees. 

Passthrough Platforms: These would also play a strong part in platforming, as they allowed for a more free-flowing movement than that of the stationary or moving platforms. 

Moving Platforms: Moving platforms would be the main transitioner from section to section, and also to add a bit of drama with players figuring out the timing when jumping to and from them. This being said, they were used here and there only to add this element of play, and not to take away from the loose core platforming gameplay. 

Keys: Keys were positioned in a way that clearly presented them as the objective to be attained, as they sit toward an end of each section while plainly in sight. 

Spikes: Spikes were to be a minor asset in the level, as it was used only to heighten the drama and challenge of the platforming aspect, without convoluting the level with more main mechanics. 

Checkpoints: At the end of each of the first 2 sections, there is a checkpoint awaiting the player, giving the player a sense of relief with a short break and guarantee that should they fall into a pool of acid, they have a closer place to try again. These were used sparingly, as having the player experience relief through gameplay and overcoming challenge – such as eliminating all enemies of a section or obtaining a key - was a primary goal of this design. 

Weapon Pickup (Gun): Given this weapon’s versatility and potential with platforming, it has been introduced as the main weapon in the game. It was implanted only just before the combat, so players would discern its appropriate use for the combat and not a mechanic in the platforming. 

Spitters: Due to Spitters being a stationary enemy, they made for a simple obstacle to create drama with the player’s own positioning, as they shoot their projectiles in an arch pattern. 

Chompers: Chompers are placed as a subtle way of guiding the player through specific parts of the level, most notably being Section 3, toward the final key. 

Health Pickups: This level was intended to challenge the player with a comfortable degree of difficulty, and therefore health pickups would not be very necessary, however placing one just before Section 3 allows players a moment of relief and to recover any missing hearts before they take on the final challenge. 

Weapon Pickup (Staff): Given the Staff’s lower versatility, especially when paired with the platforming, I decided to make the gun a primary weapon. I would therefore implement the staff as a bonus to the level, and create a moment of exploration and reward with its placement behind the wall. 

(DocImages/<LevelDesignPrototype1.jpg>) 

The first prototype created was made before experimenting deeper with the optional and required assets of the level. As mentioned earlier this design took inspiration from Mega Man X, and was similarly set out on a – mostly – flat and linear map layout. After spending time exploring the assets and the scene provided, it seemed this prototype would not suit this design task, as it not only limited the exploration in the level, but also would require the design to be compressed to fit the map suitably. 

(DocImages/<LevelDesignPrototype2.jpg>) 

This second prototype of the level would only include the first 2 sections, as ideas of allowing these 2 sections to be explored freely (that is, without locking a player into a specific path) would become solidified in the design of the level. Here, spikes were only found in the Section 2, which made the section seem to combine a new platforming element, which would desirably be the role of Section 1. After experimenting with the weapon assets a bit more, it seemed the gun would be better suited for the learning experience with its adaptability to the player and their playstyle. Therefore, it soon became the only weapon in the combat section for the players to have more room to explore and discover its use and potential. 

(DocImages/<LevelDesignPrototype3.jpg>) 

This third prototype was the final and definite version to be made, as all 3 sections played their role efficiently. While Section 1 is mostly untouched – aside from the addition of spikes and platform tweaking – Section 2 was made to center more around the gun, as the staff had a more limited use, since it couldn’t quite be combined with crouching and required players to close their distance with the enemy. Therefore it was included as a bonus for players who preferred that close playstyle and blended attack ability, hidden behind a PassThrough wall facing against them. This prototype also revamped the original Section 3, as the first design was too mild in its intensity and had a limited conjunction of the platforming and combat elements. Instead of having a linear flat path with 2 separate acid pits, they were combined to create a more constant danger of falling and restarting at the checkpoint. Enemies were also increased to further test the player’s patience and skill with their use of combat and movement in the single final environment. 

(DocImages/<MoleculeDiagram.jpg>) 

The molecule diagram allowed for a solidified idea of how levels would flow into one another and play out with each other. It was the final conceptualisation of the level design’s layout before it would be properly constructed. While the level has remaining untouched potential in completely reaching its goal of providing players with a sense of discovery, drama, exploration and challenge, its inclusion and simulation of these elements is effectively executed and demonstrated through the level design and its gameplay. 
