# Project 1: The Elevator Interface

## Requirements for a grade of C:
- Elevator was found in a parking garage in Austin, Texas. Below are some images of the control interface.
<p align="middle">
  <img src="https://user-images.githubusercontent.com/88754586/192710438-092a0d5e-fa06-4ca2-bd80-9a50857be504.jpeg" width="40%">
  <img src="https://user-images.githubusercontent.com/88754586/192710443-014226ec-3761-439a-8135-ec1ee2a77f63.jpeg" width="40%">
</p>

- Here is a gif of the control interface in action.

### Current design issues:
  -	The lobby names are not represented in braille
  -	Not everyone will know what “B” stands for
  -	Door open and close buttons do not light up when pressed
  -	Door open and close buttons do not seem to work, no response when pressed other than the button going in
  -	Very top button may be hard to reach for people in wheelchairs
  -	Current floor screen quite high up, those in wheelchairs may have to strain neck to see it
  -	Random black square below controls, may confuse users into thinking it has functionality (could possibly be a camera)
  -	Current floor can be hard to read since its white text on a bright blue background
  -	Elevator only “dings” when travelling between floors. A voice relaying what floor its currently on would better help those who are visually impaired
  
### What the design does well:
  -	Floor control buttons provide obvious feedback when pressed
  -	Braille is used to help visually impaired use the elevator
  -	Feedback is provided to let you know your current floor location
  -	One simple help button, some elevators have multiple, and this may confuse users
  -	Emergency button is colored red
  -	Information board above controls letting users know what is located on each floor
  -	Some floors have additional labels beyond numbers

## Requirements for a grade of B:
### Common elevator uses:
  -	Travel up to higher floors
  -	Travel down to lower floors
  -	Used by handicapped people so they may easily go up/down floors
  -	Transport large or heavy objects up and down floors
  -	Close doors with close doors button
  -	Open doors with open doors button
  
### Rare:
  -	Using the elevator emergency call button to get assistance if there’s an issue with the elevator
  -	Use the emergency alarm button to alert someone that you are stuck in the elevator
  -	Press emergency stop button to immediately cut power to elevator motors and apply the brakes

### Common action sequences:
  1.	Press elevator call button
  2.	Enter elevator and select desired floor (may read information panel before selecting floor)
  3.	If no one is nearby, press close door button. Otherwise, wait for other users to perform their actions
  4.	Look at current floor screen and wait for elevator to arrive at your floor
  5.	Exit elevator

### How does the elevator support the user to figure out how to make it work?

  This elevator does a pretty good job in helping users understand how to use it by providing a large information panel on which floors have what locations. This will help users understand they need to press the corresponding floor button to get to the location they desire. There is a very limited number of controls, and all of them are labeled with either text or symbols. The emergency button could benefit from some text saying emergency on it, but it does give the impression that the button calls for help due to it being red with a phone icon on it. The floor controls provide useful feedback to let users know a floor has been selected. 
  
### How does the elevator provide feedback to users?

This elevator provides feedback to users in a visual, audible, and tactile manner. When using one of the buttons on the controls users can feel the button going in. A light ring around the button will then activate, letting users know they have selected a floor. While the elevator is traveling, a sound effect will trigger each time it arrives at a new floor, letting visually impaired individuals know that the elevator is moving between floors.

### What are some possible mistakes users could make with the current interface?

With this design you could easily make the mistake that the close door buttons work when they in fact do not do anything at all. Users who do not know what “B” represents may be scared to access those floors and not travel to them. 

### Improvement suggestions and my justification
Since I will be creating a touch screen interface in processing, I decided to make my improvements with a touch screen in mind. Below are some of the improvements I made:
  -	Took advantage of the fact that touch screens can scroll by a user swiping. I made it so the screen could take up less space, saving money and allowing disabled users to easily reach it
  -	I made it obvious that more floor options were available by adding arrows showing that more options are above and below
  -	Side controls such as emergency and door controls are separate from floors so users wont accidentally press them trying to change floors
  -	Floors are labeled with words instead of just letters and numbers which helps users better understand their purpose
  -	Current floor is shown right above the controls, all useful information in one place rather than split
  -	Easy to read font and colors allowing users to quickly gather control information

<p align="middle">
  <img src="https://user-images.githubusercontent.com/88754586/192771443-ee035316-91df-4a0d-9af7-c699589010cc.png" width="60%" align="middle">
</p>

## Requirements for a grade of A:
My elevator touch screen has a size of 650px by 490px. This may seem small but I have good reason for choosing this screen size. I want those in wheel chairs to be 
able to easily use my interface, so I made sure to make it compact, without compromising on the information it provides. I took full advantag of the interface being
touch screen by allowing users to swipe to see all possible floors. Census.gov states that 84% of Americans own a smart device, meaning they have experience using touch screens and would not have to learn how to use my interface. I supply arrows pointing in the direction that more information is available so users will not miss any floors. 

https://user-images.githubusercontent.com/88754586/192776894-03538d5b-ae1e-4698-8184-2e6396ada7bf.mp4
