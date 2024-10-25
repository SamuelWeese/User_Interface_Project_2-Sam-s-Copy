# User_Interface_Project_2 - Lightbulb Simulator 2024

# Helpful Commands
- npm run deploy - This will build and deploy the github page public website
- npm run dev - runs site locally

# Documentation
Group members: Nathan Suer, Sam Weese, William Braun, Owen Richards

## Description the project

The Home Lighting Simulator 2024 is a control interface for multiple wifi lightbulbs used in parallel. It displays to the user individual lightbulbs and their spheres of influence in a home. It allows its users to remotely control lights, either within groups or individually.

## Design Work

### Affordances
- A smart lightbulb would afford providing light when turned on 
- A smart lightbulb would afford remote control via a mobile app
- A smart lightbulb would afford changing color and brightness
- A smart lightbulb would afford integrating with other smart lightbulbs or devices 

### Physical Properties
- The lightbulb itself will be fixed due to being connected to the ceiling 
- It will be the size of a normal lightbulb, so it will not be too large
- The interface will be an app, so its size can vary based on the device it is being used on 

### Interviews
#### Questions
1. If you had a lightbulb app, which tracked color changing lightbulbs, what features would you want?
2. How often would you use the lightbulbs?
3. If you have color changing lightbulbs, what do you currently use to control them?
4.  What features do you like of the current control system?
5. What statistics, if any, do you want tracked with your lightbulb?
6. What options do you want visible upon viewing an individual lightbulb?
7. Is there any way you would like lightbulbs grouped?   

#### Interview 1:
1. If you had a lightbulb app, which tracked color changing lightbulbs, what features would you want?
- Grouping together lightbulbs, notes on lightbulbs, schedule on lightbulb, multiple color patterns on lighbulbs
2. How often would you use the lightbulbs?
- Every day. 
3. If you have color changing lightbulbs, what do you currently use to control them?
- Has color changing lightbulbs, doesn't change them unless necessary. Uses default Lumiman app.
4.  What features do you like of the current control system?
- Color wheel.
5. What statistics, if any, do you want tracked with your lightbulb?
- Days used, time since installation, hours estimated left
6. What options do you want visible upon viewing an individual lightbulb?
- Name, description, color, schedule
7. Is there any way you would like lightbulbs grouped?
- By room and by schedule
#### Interview 2:
1. If you had a lightbulb app, which tracked color changing lightbulbs, what features would you want?
- Grouping together lightbulbs, multiple color patterns on lighbulbs, patterns on lightbulbs by room
2. How often would you use the lightbulbs?
- Every day, probably changing the themes by room by time of day
3. If you have color changing lightbulbs, what do you currently use to control them?
- No color changing lightbulbs.
4.  What features do you like of the current control system?
- N/A
5. What statistics, if any, do you want tracked with your lightbulb?
- Days used, colors used, rooms used
6. What options do you want visible upon viewing an individual lightbulb?
- Name, color, schedule, room
7. Is there any way you would like lightbulbs grouped?
- By schedule
#### Interview 3:
1. If you had a lightbulb app, which tracked color changing lightbulbs, what features would you want?
- Grouping together lightbulbs by room, turning multiple lights on and off, 
2. How often would you use the lightbulbs?
- Every day
3. If you have color changing lightbulbs, what do you currently use to control them?
- No color changing lightbulbs.
4.  What features do you like of the current control system?
- N/A
5. What statistics, if any, do you want tracked with your lightbulb?
- Hours left on lightbulb, time used, how often used, when used
6. What options do you want visible upon viewing an individual lightbulb?
- Name, color, room
7. Is there any way you would like lightbulbs grouped?
- By room, by color, by use amount
#### Interview 4:
1. If you had a lightbulb app, which tracked color changing lightbulbs, what features would you want?
- Grouping together lightbulbs by any means, lightbulbs with individual names, controlling groups, changing colors
2. How often would you use the lightbulbs?
- Only on special occasions, like a party
3. If you have color changing lightbulbs, what do you currently use to control them?
- No color changing lightbulbs.
4.  What features do you like of the current control system?
- N/A
5. What statistics, if any, do you want tracked with your lightbulb?
- User did not think of any
6. What options do you want visible upon viewing an individual lightbulb?
- Name, color, group
7. Is there any way you would like lightbulbs grouped?
- Not really

### Assumptions
- The smart lightbulb will keep track of its current color setting and have functionality for said color to be changed 
- The smart lightbulb will have its location within the house stored, allowing the user to adjust lightbulbs remotely
- The smart lightbulb will have multiple settings, including being on between certain hours and maintaining a certain color

### User Needs
- User needs to be able to group lightbulbs based on schedules and rooms
- User needs to be able to turn multiple lights on and off at once
- User needs to be able to name lightbulbs
- User needs to be able to choose from a selection of colors 
- User needs to be able to set schedules
- User needs to be able to control lightbulbs by groups

### Design Requirements
- Functionality for organizing lightbulbs within the interface based on room or schedule
- Provide the ability to turn multiple lightbulbs on or off simultaneously 
- Make the name of each lightbulb customizable in the interface
- Add customizable colors - could use a color wheel or allow the user to input color codes
- Functionality for creating schedules that can affect multiple lights at once 
- Group lightbulbs by predefined criteria and make these groups controllable 

### Sketching 

#### Sketching design alternatives to 3 design challenges (10-plus-10)
![Design Challenge 1](src/pictures/design-challenge-1.jpg)<br />
Header and navigation positioning.

![Design Challenge 2](src/pictures/design-challenge-2.jpg)<br />
Main body positioning. We think it would be best to have the controls and grid displayed at the same time for the user's convenience. 

![Design Challenge 3](src/pictures/design-challenge-3.jpg)<br />
Navigation and/or controls are toggleable to leave room for the main grid.

#### Sketching the interface ("the vanilla sketch") 
![Main Sketch](src/pictures/main-sketch.jpg)

#### Storyboard sketch
![Storyboard](src/pictures/storyboard.jpg)
1. User reads the header to understand basic concept of the page.
2. User will probably see the grid next.
3. The user will probably be confused by the grid and will then read the controls, located in the box next to it.
4. User can now interact with our device's simulation.

#### Hybrid sketching to illustrate the integration of the interface on a real object
- We are designing a smart lightbulb where the user would want to control the lightbulb via an app.
- Since the lightbulb needs to be physical and would be challenging to digitalize, light switches would be replaced with our interface. The lightbulbs used by our interface would need to be capable of fulfilling smart capabilities.
- For our hybrid sketch, our smart lightbulb interface will replace a light switch.
- This is Nate's puppy, Millie.
![Hybrid Sketch](src/pictures/HybridSketch.jpg)

### User Feedback
- The user feedback we primarily received was that our choice of displaying the grid and controls at the same time was a good idea, as the grid was confusing at first. There was also a 2-1 split between whether or not the grid should be interacted with to turn lights on and off, instead of just displaying the current house's condition. Finally, they all agreed with only needing "Controls" and "Description" menus on the right.

## Describe your interface in detail:
- Explain the features and controls
- Include plenty of screenshots to illustrate your interface and different actions users can perform within it
### Floor Layout

The Home Lighting Simulator uses a floor layout to display each of the bulbs. Each room is a grouping of lightbulbs and can be controlled remotely using the Simulator. 
![Floor Layout](src/pictures/floorplan.jpg)

### Vocal Controls

The Home Lighting Simulator uses a series of vocal controls (not implemented for this project) to allow the user to turn lights on and offbased on the names of the lights. There are a number of options, including disco mode, blinking, and hue shifting!
![Voice Controls](src/pictures/voice-controls.jpg)

### Light Control

Clicking on a light opens up the light control menu. This menu allows individual control of each light, from changing the room group to color, schedule, and brightness. 

![Light Menu](src/pictures/light-menu.jpg)

## Explanation of implementation

We have 3 main components of the UI: the map, the light control menu, and the vocal/group control menu. 

### The Map

The map is a grid which contains 4 types of tiles; lights, background, doors, and walls. Clicking on a square allows the user to modify the light options. We used a svelte generated array for columns and rows, with each cell being a square in the room. We chose this approach as it is both intuitive and provides a good visual for the user.


The pop-up with controls is a modal, which gives the user the ability to modify each light individually or add them to groups. This feature provides the modulatrity requested by our users.


Fake voice commands were implemented as an additional panel. Shipping real time vocal processing is a processing-expensive task and would have taken longer than the project would allow. The panel adds on/off options for groups, multiple pre-programmed modes, and a scheduler for day or night time. 

## AI Use
- Nate used the following prompt "Using svelte and js, make me a component that will allow me to design floorplans for houses. All floorplans are one floor. Have options for doors, lights, and walls" to get the basic room maker. It was functional. This was useful but only will be used as a basis for future work. Here is an image of what was made:
![Room Maker](src/pictures/basicRoomMaker.png)
- ChatGPT was used to make the svg icons for the power button and the mic button
- GitHub Copilot's autocomplete feature was used to speed up the coding process

## Future work
- No project is ever fully done. What would you do next?  This is also a place to discuss the work you attempted but could not fully complete before the project deadline- include screenshots to illustrate and document your progress. 
### User Interface

For the user interface, there are a couple of things we would like to overhaul. First, the vocal commands should have a UI to accompany them. There should also be a way to allow the user to use non-vocal commands to access functionality such as disco mode, rainbow, etc.

### Volumetric Lighting Simulation

Our lighting simulation is completely grid based. This feature lacks the definite detail we would like to have for light rays to go arounds walls. We currently only check in the x/y direction, casting a ray in the positive and negative xy directions. Instead, we should cast rays from each light and then use that calculation to draw our lights. This would be a new canvas object which would be shipped as web assembly for the speed increases.

### Firmware Controllers

It would be way cooler if this worked with real lightbulbs... Well we could make this happen! A number of wifi lightbulbs do have their own APIs. We also have the option of writing a controller for any open source software!

### Vocal Interface
Real time vocal analysis and word parsing is extremely expensive. Realistically, we would need to ship this as web assembly. It simply has too many performance issues currently.

## Demo Video
- The easiest way to record this is with a screen capture tool, which also captures audio- such as Quicktime.  Use a voiceover to explain your application.  Include the name of the project, your name, the project components, and how your application works.  You can present it on your webpage or on youtube, but it must be linked on your webpage. 

You can see our video [here!](https://uc.mediaspace.kaltura.com/media/t/1_o38sgpyv)

## Link to source code and public hosted application
- https://github.com/NSuer/User_Interface_Project_2
- https://nsuer.github.io/User_Interface_Project_2/

# Project 2 check-in- collaboration plan

Group members: Nathan Suer, Sam Weese, William Braun, Owen Richards

- What will you do to make sure your team is successful. 
    - We will ensure that we have thoughful and efficient communication. We will make sure that everyone in the team is collaborating. We will foster a team of diverse thinkers in order to come up with the best solutions.
- How will you communicate? 
    - Discord Groupchat.
- How will you coordinate work? 
    - We will use a github repo and each person will have parts of the project they are in charge of.
- Do you plan to have regular meetings? 
    - Wednesday in-person after class or on discord if that doesn't work one week.
- Have you discussed team conflicts or obligations during the project time-frame? 
    - There are no conflicts we know of.
- How will you divide the work? 
    - For now, we will divide work based on skillsets due to not knowing the full extent of our project. As the project goes on, we will attempt to keep the workloads balanced while providing support to those who need it. 
        







