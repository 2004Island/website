---
title: "My first PCB"
date: 2020-11-21T10:07:47+06:00
draft: false

# post thumb
image: "images/featured-post/post-lasertrip.jpg"

# meta description
description: "this is meta description"

# taxonomies
categories:
  - "Analog Electronics"
tags:
  - "555 timer"
  - "PCB"

# post type
type: "featured"
---


<hr>

The circuit board was a simple laser tripwire that I made when I was 15 years old. It used two NE555 timers and a light dependent resistor with complimentary components to make a buzzer beep when the path between the laser diode and the light dependent resistor. I was very proud of this board and brought the JLCPCB box with all the boards to show to my classmates. It was a very surreal experience seeing something that I designed, become manufactured and delivered to my house. The design was made over the course of about a month since I was paranoid of screwing something up when making the final board. While the board worked exactly how I designed it to, there were 2 main flaws. You can see a demo of it here.

<hr>

{{< youtube dAI8Xn476gI >}}

<hr>

##### The flaws

The two flaws with the design were thankfully inconsequential and easy to get around. The first flaw was a purely cosmetic one, on the silk screen there was a resistor that was connected to an onboard LED that lights up when the tripwire is broken. The resistor was marked with the number 350. Nobody manufactures 350Ω resistors. I don't know what's more surprising about this, my own ignorance to not even check the correct value of the resistor I used in my circuit or the fact that 350Ω resistors aren't even made. The other flaw was a component choice. For the buzzer I chose a default buzzer in the EasyEDA parts library. Apparently EasyEDA decided to choose a buzzer with a footprint that 99% of all through hole piezo buzzers don't even have. I looked at the LCSC listing for the part I chose in my board. There were 250 units. Not 250,000, not 25,000, no. 250. There are more people in my senior and junior classes than there are available stock of this "default" buzzer. To make matters worse I couldn't even find this part on Aliexpress or Amazon. Eventually I found a buzzer with the same pin spacing as the buzzer I chose for the board.

<hr>


##### If you would like to buy one of these as a kit

You can do so on my tindie store [right here]. It's gonna cost you 15 dollars without shipping. The shipping will be done through USPS.

[right here]: https://www.tindie.com/stores/varunsreedharan/

<hr>


##### A completed board

![image](../../images/post/IMG_4348.JPG)

<hr>


