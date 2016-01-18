# Visual interfaces basics
A review and report of the course [_Visual interfaces basics_](https://fhp.incom.org/workspace/6272/1) given by [Prof. Constanze Langer](http://www.fh-potsdam.de/person/person-action/constanze-langer/show/Person/) [@FH-Potsdam](fh-potsdam.de) in the winter semester 2015/1. By [Lucas Vogel](http://www.vogelino.com).

## The course
> “In Interface design, a good visual perception is still very important. Even if many innovation has happened in the multi-modal interaction fields, the main interface between humans and machines remains the screen - in all sizes and characteristics. This field of expertise presents graphic and semiotic questions based for instance on time or interaction, situating formal-aesthetics interactive systems in the focal point.”

— Constanze Langer. Traduced from german by Lucas Vogel


In this course we did…

- …get an overview of the human perception basics, especially the visual perception
- …get an overview of the multiple presentation possibilities of interface elements, data, relations and processes
- …analyze the existing communication systems, sorting and structuring methods
- …develop our personal design approach, both analog and digital
- …become aware of the multiple aspects that are to be considered when designing for screen
- …exercises-based practice, achieve results, use processes and make decisions which we were able to warrant and to logically and comprehensively explain

## The interface
To investigate the theoretical concepts and basics of Interface design practically, every student chose one product with a display. We analyzed its streghts and weaknesses and aimed to understand its structure and its interactions. Finally, we could propose a design improvement. This could be:
- A redesign of the whole product
- A proposal for a better information structure
- A redesign of the iconography
- An improvemnt of the user interactions
- etc.

I chose my home thermostat from Junkers, which controls my flat's heater, which is nice. However, many interactions and particulary the configuration is quite confusing. Before taking part of this course, I barely understood how it works and how set it up. I was rather pressing every button until the temperature in my flat became at some point convenient than master it. I ended up changing blindly the configuration every day when actually, the purpose of the thermostat itself should have been to handle the heating for me once configured.

<img width="49%" src="https://raw.githubusercontent.com/vogelino/visual-interfaces-basics/master/information-architecture/images/junkers-thermostat-front-closed.jpg" alt="Junkers thermostat closed" />
<img width="49%" src="https://raw.githubusercontent.com/vogelino/visual-interfaces-basics/master/information-architecture/images/junkers-thermostat-front-closed-open.jpg" alt="Junkers thermostat opened" />
<img width="98.5%" src="https://raw.githubusercontent.com/vogelino/visual-interfaces-basics/master/information-architecture/images/all-screens.jpg" alt="Junkers thermostat - all screens" />

### The confusing parts
The three modes of the thermostat were not really clear to me as to switch between them, a combination of many different physical inputs are necessary:

- **The off mode:** The off mode is actually an anti-freeze mode that heats only when the room temperature goes under 5°c. It is activated when the circular switch is oriented on the ![snowflake-icon] icon. For any user having few knowledge about heating system, it would take a while util realizing that this symbol represents the thermostat's _"off"_ state.
- **The heating program:** The thermostat gives the user the possibility to configure two phases of heat during the day: The day phase and the night phase. When the user sets up the day phase, he can choose at what time the heating begins and at which temperature. The day phase is represented by a ![sun-icon] icon and marks the end of the night phase. The night phase is represented by a ![moon-icon] and marks the end of the day phase. The confusing part here is:
	- that in the night phase it cannot be heated at higher temperature than in the day phase.
	- that the day phase can be configured to heat during the night and the night phase during the day.
	- that the text shown when configuring the day phase is _"heat"_ when in the night phase it is _"save"_. _Why save if it is still heating?_

	To let the heating program run, the circular switch needs to be oriented on the ![radiator-icon]. It is important that the _"auto"_ text appears on the screen. To toggle the _"auto"_ text, the auto button has to be pressed.

- **The manual mode:** This mode lets the user override the temperature of the actual heating phase. To do so, the auto button hast to be pressed until it disappears from the screen. Then, by rotating the central knob the user can set the wished temperature. Because you can easily miss the information, it happens often to heat for many days without a break which is not really economic.

## The information architecture
As a first investigation process, before ever improving the design of the product, the whole information architecture had to be presented in a visual way. Doing so, it is made sure that the product is understood, that all its options are listed distinguished, listed and that no shadows remains.

In the case of my thermostat, I opted to show the home screen as a base. Starting from the home, I show all interactions that lead to another screen and finally lead back to the home screen. I chose to represent paths that we can visually follow and indicate though symbols where interaction happens. On the multiple screens, I also labeled the different actions that are to be made in a specific order.

<a href="https://raw.githubusercontent.com/vogelino/visual-interfaces-basics/master/information-architecture/exports/termostat-informations-achritechture-hd.jpg" target="_blank" title="Junkers thermostat - information architecture">
	<img width="98.5%" src="https://raw.githubusercontent.com/vogelino/visual-interfaces-basics/master/information-architecture/exports/termostat-informations-achritechture-lq.jpg" alt="Junkers thermostat - information architecture" />
</a>

## The redesign
coming soon

## Conclusion
coming soon

[sun-icon]: https://raw.githubusercontent.com/vogelino/visual-interfaces-basics/master/information-architecture/icons/sun.png
[moon-icon]: https://raw.githubusercontent.com/vogelino/visual-interfaces-basics/master/information-architecture/icons/moon.png
[snowflake-icon]: https://raw.githubusercontent.com/vogelino/visual-interfaces-basics/master/information-architecture/icons/snowflake.png
[radiator-icon]: https://raw.githubusercontent.com/vogelino/visual-interfaces-basics/master/information-architecture/icons/radiator.png
