# [[Lidar - Player Experience |Player Experience]]

# Overview

## Genre 

### Mystery

- Conversation rather than combination lock (give feedback to theories the player presents).
    
- Two stories in a mystery; The mystery itself and the story of the player who is experiencing the mystery. In this 
    
- Construction rather than deduction
    

### Adventure

- Getting lost is part of the fun
    
- Discovering “new” and unique areas and experiences
    

### Puzzle

# Theme / Setting

## Who? 

- Explorer / Adventurer / cave dweller?
    
- Creatures that inhabit their own specific and unique environments
    

## What? 

- Experience the world through the senses of those around you
    

## Where? 

- Alien and foreign environments / universes that the player gets through into
    

## When?

-  A time loop that repeats 
    

## Why? 

- Stuck in a loop that can only be broken by understanding the world through the perspectives of other creatures in the region. 
    

## How? 

-   
    

## How many?

-   
    

## How much?

-   
    

# Story

# Gameplay

What is the moment to moment gameplay?

What is the hour to hour gameplay?

What is the session to session gameplay?

How does the gameplay extend beyond the game?

## Tools & Mechanics

Constraints?

Goals?

How do you use the tool?

Tools can change the way the player perceives things and add more complexity by adding new ways to view a problem.

### Understanding others perspectives and how they experience the world

- View the world through the perspectives of other creatures. Come to understand how they see the world around them and why they behave in a certain way.
    

### Lidar Gun

- Light reflects off some objects?
    
- Lidar only regenerates energy when in light.
    
- As you scan it automatically maps out the area as a 3d map.
    
- Some sections of caves are “dead zones” and cannot connect to the mapping system for some reason (in separate dimension)
    
- Play sound depending on depth of each beam
    
- Encounter other “scanner” in the world that allow you to use your knowledge of them and learn from them
    

### Grapple Hook

-   
    

### Traveling between dimensions

- Travel between realities to combine to interact with or combine things together.
    
- Perhaps you’re traveling more than just space when you swap universes, but also time?
    
- Your body can be in a different reality than the one you’re seeing.
    
- Picture the different realities as a graph of nodes.
    

### Materials

- Glassy material that scatters light
    
- Material that emits light once scanned
    
- Material that phases
    
- Material that has physics when it has energy 
    
- Material that teleports
    
- Material that reflects light
    

  

# Areas / levels

## Places that would be cool to explore

- Twilight forest
    
- Stalagmite cave area
    
- Underwater ruins
    
- Religious site
    
- Mountains face
    

# Similar Games and Inspiration

## Outer Wilds

Talk about places the player hasn’t traveled to yet and build interest.
### Tools breakdown

Tools in Outer Wilds help you gather information about the environment that you need or move around in the environment in unique and interesting ways.

- Sound gun
	- Detects distant noises in the direction you point
- Drone / Camera
	- Takes pictures
	- Can be launched to see into areas you can’t reach yet
	- Allows you to take photos of quantum objects so they don’t disappear
- Flashlight
	- Allows you to see in the dark in front of you
	- Control light objects in DLC
- Translator
	- Translates text as diegetic UI
- Map (Solar System)
	- Allows you to see where objects are in space
- Map (Planet)
	- Tells you where on the planet you in accordance with the planet’s poles
- Jetpack / Space suit
	- Move around in 3d space and allows you to live while exploring
- Ship
	- Allows you to travel around space much more easily
	- Safe place to replenish oxygen and fuel
	- Ship logs allow you to

### Curiosity driven gameplay

Knowledge as a reward for exploration and curiosity.

The main goals in Outer Wilds’s design were to:

- Inspire curiosity
- Facilitate exploration
- Reward exploration

Outer Wilds uses a sprawling mystery composed of several smaller mysteries 

How do we get players to ask questions? -> What questions do we want the player to ask to guide the player’s journey?

Show rather than tell is a much stronger motivator for these types of questions. In Outer Wilds they use big flashy events such as the Nomai statue at the start of the game and the Sun blowing up. Physical processes and locations grab the attention of the player and make them want to investigate. Big initial hooks for mysteries are mostly done with physical things.

![](https://lh6.googleusercontent.com/cI_dWukm9oEeLtFrWcH8O1SEzDmxoRAdZVNQZAiowo9Q7sPnLT9ExiOdqLuQeIMmZ5ECzYy3xEDx1fgFu9M-a3FmRIrT_BtKZMYB6EXTjiMA6F-fMlqK7rKw8NQ5d6biVVwJK7R0-NJzd-8_qeUgX0I)

### Big key moments

Regular payoff to smaller mysteries to keep the player motivated 

## Lidar.exe

### Lidar mechanic

## Over the Garden Wall

### Haunting

### Lost in the woods

## The girl from the other side

### Folklore 

## Gravity Falls

### Symbols

### Hidden meaning

## Obra Dinn

### Perspectives

### Detective and deduction

## Abzu / Journey

### Silent storytelling 

### Importance of environment 

## Hollow Knight

### Progression and discovery

### Overlapping stories and living worlds

## Breath of the wild

### Triangles

Breath of the wild uses triangles to limit the information the player sees and has access to so as not to overwhelm them and they feel like there’s always something to discover around the corner.

### Bread crumb trail of points of interest

![](https://lh4.googleusercontent.com/nP1ron_M_tgaSBjigZnzroMxrksKQT-JzU7P_pEfqXSMYT3ewebgaFag_RT7QzTQpp-sh9eyPmhvw16_L3IeBoI746e0eXtTIHlBCLSBL3l2PVOVTaqka2t3MvPexBGd4ko2hx1qhlPbyIN_M1-VvwQ)

  

# Visual style

## Visual considerations

- Style that is easy to make 3d models
- Should work around the limitations
- Shadows, light, and darkness are very important to a game like this

- Subtractive charcoal drawing
- Grain texture for screen is applied
- This will be the “threshold” of force needed from each pixel to be applied to the screen
- If threshold is reached draw pixel if not draw white
- Use hatching for ocular occlusion
- Use lines or subtraction if area is too dark to create outline for objects in focus
- Use blending for everything outside depth of field (separate pass)
- Get area around objects do a distance transform and use “subtraction” to make objects stand out more

Step by step

1. Basic outline / contour / edge detection shader
2. Apply paper grain noise which will change every X seconds
3. Use depth of field to find areas in focus
4. In focus areas use distance of pixels from edges to subtract some colour around an object
5. Objects out of focus get smudged depending on their distance 
6. Use hashing texture for ocular occlusion

## Visuals references
![](https://lh3.googleusercontent.com/VvrScGTth28C1h0XwVngwxjYj2D6aUnlmAPaydFA4u5lQz83JBm49Pn-pnthMPIsk4Rg2X67oacaAeHehAxG-CmhRh_4uH_W-CTB3XTjJQRvbzv0SQCjIVZEdmvftcT2ey1Tmo59Pzwvs3J6v_Jcgs8)

![](https://lh6.googleusercontent.com/GnI2DbWJ5LQ1G302KSIyIANYOo7nTn2uJwyIicCZzazUROkaJPwITdcIfuQe4OtpCsbE97eOekK7bkQweWDq4XxOAhRgKMnZXD5mgcK-pu3sHjFIw-OYdzOkO5mKchxVStcxFfUyODQ2l3iC25lLYCY)

![](https://lh4.googleusercontent.com/dgllNL2NiMGRgNPAEqKBJBI1QtUrVas5bP6apJ7o1S0_NUdCWKGiY0lXALc9arPUzP3AX4P5hwIl3BHoc43TO2gysdQEQQOmPKr3ItrZgW-PqYlxFLBpp9Ms6gS0rW4w_fFG9i8Jjtspty6hZ-V3H6U)
# Other Considerations

- The game should add information needed to the perceptual field of the player. For example if the player needs to understand that light bends when changing medium then the game should have the player perceive and interact with this in some way beforehand so that the player has this added to their perceptual field beforehand they are expected to apply this information themselves.
- Different shapes for scan?
- Someone who knows things in the darkness
- Storyboard