# Box Game
Box Game was my first ever project, completed way back during my junior year of high school in 2019. At the time I had barely coded anything in my life, just the basic Hello World projects like printing "Hello World" to the scree, making "Hello World" show on an HTML site, making a 3d object move in Unity, and being trapped in an endless YouTube tutorial loop. I got bored (and stressed) very quickly and wanted to do something unique. After talking to a friend's parents about what I should do next, they suggested I learned how to use a Raspberry Pi and make something with it. That day after school I walked to MicroCenter and bought myself a raspberry pi. For about a week I messed around writing random lines of code, editing the built-in Minecraft world and gained a basic understanding of how the device worked. During this time, I decided my first project would be to figure out how to light up a single LED. 

I got to work and bought the many parts I'd need, including buttons, a breadboard, wires, LED's, resistors, and a soldering iron. After many epic fails and little progress, I couldn't get the LED to glow. I was doing everything right, all the ports were properly connected, the code was running perfectly, but still nothing. It was only then I realized that the resisters I had bought were rated 25x more than what I needed, talk about overkill. I went back to microcenter and bought 250v OHM resisters and woala, the LED shined brighter than ever before.

# Inspiration
I had recently gone to Dave & Buster's with my dad and had played the -*extremely rigged*- arcade game "Cyclone". I wondered how hard it would be to make my own version of the game and quickly got to start with research and required parts.

**[Cyclone Arcade Game](https://www.betson.com/amusement-products/cyclone/)**

<img src="https://user-images.githubusercontent.com/75161978/150029734-cc76dd88-059a-4117-aa4b-8dcea232e890.gif" width="380">

# Blueprint
I thought for a while and settled on a model of the game I'd create
- Two players sit across from each other and hover their hand over the button on their side
- The players take turns watching the light bounce from one side of the box to the other and try to stop the light on the big green LED opposite of them to earn a point
- If a player stops the light on a red LED or the green LED on their side, they are not awarded a point, and it becomes the other players turn
- If a player does successfully earn a point, the green LED flashes an amount equivalent to that player's point total
- The game ends when a player reaches five points, which triggers a short light show for their enjoyment

To get started I had to go out and get the following parts:
- Shoebox
- Buttons
- Breadboard
- Wires
- LEDs
- Resistors
- Soldering Iron


# Creation
- I took apart the existing system I had built to light up a single LED
- Figured out what each pin on the Raspberry Pi represented
- Connected one end of each wire to the Raspberry Pi, and the other to the breadboard
- Placed down resistors in between the wires and where the LEDs would go to control the flow of OHMs
- Soldered another set of wires to the LEDs so they could reach the holes I'd cut into the top of the box
- Completely fail and have to reconfigure the number assigned to each pin on the Raspberry Pi
- Code a loop to have the light travel from one LED to the next in timed intervals
- Code a point system, which also added light shows/reactions

**What I took out of the project:**
- I gained a lot of valuable electrical engineering skills and coding knowledge that I didn't have before
- Introduced me to the Raspberry Pi and Python
- How resistors, the pins on the Raspberry Pi, and breadboards work
- A sense of accomplishment through finishing my first project, and acted as my motivation to go to college for Computer Science

**Final Product:**

![boxgame10frames](https://user-images.githubusercontent.com/75161978/150026568-e0e3128b-62fe-46e0-8622-36bca743b56f.gif)
