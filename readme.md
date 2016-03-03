# Visual interfaces basics
A review and report of my works within the course [_Visual interfaces basics_](https://fhp.incom.org/workspace/6272/1) supervised by [Prof. Constanze Langer](http://www.fh-potsdam.de/person/person-action/constanze-langer/show/Person/) [@FH-Potsdam](fh-potsdam.de) in the winter semester 2015/1. By [Lucas Vogel](http://www.vogelino.com).

## The course
> “In Interface design, a good visual perception is still very important. Even if a great innovation has happened in the multi-modal interaction fields, the main interface between humans and machines remains the screen - in all sizes and characteristics. This field of expertise presents graphic and semiotic questions based for instance on time or interaction, situating formal-aesthetics interactive systems in the focal point.”

— Constanze Langer. Traduced from german by Lucas Vogel

The course _Visual interfaces basics_ is an introduction to the fundamentals of interface- and screen- design. It offers a theoretical, reflectional and practical approach the digital screen world, although most investigated concepts are equally relevant in most derivations of Design.

The course covered:

- An overview of the human perception basics, especially the visual perception
- An overview of the multiple presentation possibilities of interface elements, data, relations and processes
- An analysis of the existing communication systems, sorting and structuring methods
- An introduction to the multiple aspects to consider when designing for screen
- A development of a personal design approach, for both analog and digital environments
- An exercises-based practice
- An introduction to information architecture and application structure
- An introduction to the use of space, typography, form, iconography and major visual dimension in visual interfaces
- An introduction to important UI/UX principles and patterns
- Critics and support while creating the course's projects

## The interface
To learn in a theoretical and practical way the basics of Interface design, every student of the course chose one product that has a screen display. We analyzed its strengths and weaknesses and aimed to understand its structure and how users are supposed to interact with it. This investigation could be made in one of the following forms:
- A redesign of the whole product
- A proposal for a better information structure
- A redesign of the iconography
- An improvement of the user interactions
- A personal approach to the interface's improvement.

My personal product choice was my home thermostat made by Junkers, which controls my flat's heater. This system allows me to decide whenever I want my flat to be heated or not, however, many interactions and in particular the configuration are quite confusing. Before taking part of this course, I barely understood how it works and didn't know how set it up. I was rather pressing every button until the temperature in my flat became at some point convenient. Finally, I ended up changing blindly the configuration every day even though the purpose of the thermostat itself is to handle the heating for me independently once configured.

This is how the device looks like:

<img width="49%" src="https://raw.githubusercontent.com/vogelino/visual-interfaces-basics/master/information-architecture/images/junkers-thermostat-front-closed.jpg" alt="Junkers thermostat closed" />
<img width="49%" src="https://raw.githubusercontent.com/vogelino/visual-interfaces-basics/master/information-architecture/images/junkers-thermostat-front-closed-open.jpg" alt="Junkers thermostat opened" />
<img width="98.5%" src="https://raw.githubusercontent.com/vogelino/visual-interfaces-basics/master/information-architecture/images/all-screens.jpg" alt="Junkers thermostat - all screens" />

### The confusing parts
The three modes of the thermostat were not really clear to me. How do I switch between them? To do so, a combination of many different physical inputs are necessary:

- **The off mode:** The off mode is actually an anti-freeze mode that heats only when the room temperature goes under 5°c. It is activated when the circular switch is oriented on the ![snowflake-icon] icon. For any user having few knowledge about heating system, it would take a while until realizing that this symbol represents the thermostat's _"off"_ state.
- **The heating program:** The thermostat gives the user the possibility to configure two phases of heat during the day: The day phase and the night phase. When the user sets up the day phase, he can choose at what time the heating begins and at which temperature. The day phase is represented by a ![sun-icon] icon and marks the end of the night phase. The night phase is represented by a ![moon-icon] and marks the end of the day phase. The confusing part here is:
	- that in the night phase it cannot be heated at higher temperature than in the day phase.
	- that the day phase can be configured to heat during the night and the night phase during the day.
	- that the text shown when configuring the day phase is _"heat"_ when in the night phase it is _"save"_. _Why save if it is still heating?_

	To let the heating program run, the circular switch needs to be oriented on the ![radiator-icon]. It is important that the _"auto"_ text appears on the screen. To toggle the _"auto"_ text, the auto button has to be pressed.

- **The manual mode:** This mode lets the user override the temperature of the actual heating phase. To do so, the auto button hast to be pressed until it disappears from the screen. Then, by rotating the central knob the user can set the wished temperature. Because you can easily miss the information, it happens often to heat for many days without a break which is not really economic.

## The information architecture
As a first investigation process, before ever improving the design of the product, the whole information architecture had to be presented in a visual way. Doing so, I made sure that the product was understood, that all its options were listed and distinguished.

In the case of my thermostat, I opted to show the home screen as a base as it is there where all interactions begin. Starting from the home, I showed where any interaction leaded. Most of them bring the user to another screen and finally lead back to the home screen, when the setup is done. I chose to represent paths that can be visually followed and to indicate with symbols where interaction happens physically. On the multiple screens, I also labeled the different actions inputs that should be modified in a specific order.

<a href="https://raw.githubusercontent.com/vogelino/visual-interfaces-basics/master/information-architecture/exports/termostat-informations-achritechture-hd.jpg" target="_blank" title="Junkers thermostat - information architecture">
	<img width="98.5%" src="https://raw.githubusercontent.com/vogelino/visual-interfaces-basics/master/information-architecture/exports/termostat-informations-achritechture-lq.jpg" alt="Junkers thermostat - information architecture" />
</a>

## The redesign
The second iteration of the project was about offering a redesign improving the original interface. Instead of keeping the same interface and making it more understandable or beautifully designed, I choose to create mock-ups of an alternative to this thermostat. The idea was to make a smart-phone app called __H°me__ intended for planing and organizing time spans in which you wish to heat your home.

<img width="100%" src="https://raw.githubusercontent.com/vogelino/visual-interfaces-basics/master/redesign/exports/all-views.jpg" alt="Alternative heating app" />

I intentionally inspired the visual style of the visual elements to the original one to remain consistent and to 

#### Introduction
Nowadays, few are the ones which do not carry a smart-phone or a tablet with them on a daily basis. These devices became powerful tools that overcame many physical limits. The time has long become for old and complex home-heating systems to be replaced by a simple and dynamic app, that can be used anytime and anywhere.
Say hallo to __H°me__, your pocket heat planner.

##### 1. Overview
The overview is the screen where you see the actual temperature of your home, when and how warm it will be heating up.
This view is split in three presentation layers:
- The day lane, where you can see and control the temperature hourly
- Your weekly overview
- Your monthly synopsis

##### 2. Edit an event
__H°me__ works similar as a calendar. Each time you want your home to be heating up at a special time and temperature, you create an event.
To each event, you can assign a category, define a timespan, choose whether you want this event to be repeated and whether you want to be notified at start and/or at the end of the process.

##### 3. Assign a category
To be able to recognize your events and to situate them in the overview, you can assign them any temperature-category.
Give your categories fancy names to get quickly custom to them. The nameless ones are shown in a pale blue until you use and name them.
In this screen, the event‘s selected category is Weightlessness.

##### 4. Create a new category
Let‘s say you feel huggy at 18.5° and want this temperature to be associated with this mood. Call this warmth huggy and all events set to 18.5° will be shown with this color and this name.
A category is always a combination of:
- Name
- Temperature
- Color

### The poster
To present the redesign, I created a A1 poster that displays the views and explains the app. This poster was presented at the end of the course, along with the posters of other students.

<img width="100%" src="https://raw.githubusercontent.com/vogelino/visual-interfaces-basics/master/redesign/exports/poster.jpg" alt="The final presentation poster of H°ome" />


[sun-icon]: https://raw.githubusercontent.com/vogelino/visual-interfaces-basics/master/information-architecture/icons/sun.png
[moon-icon]: https://raw.githubusercontent.com/vogelino/visual-interfaces-basics/master/information-architecture/icons/moon.png
[snowflake-icon]: https://raw.githubusercontent.com/vogelino/visual-interfaces-basics/master/information-architecture/icons/snowflake.png
[radiator-icon]: https://raw.githubusercontent.com/vogelino/visual-interfaces-basics/master/information-architecture/icons/radiator.png
