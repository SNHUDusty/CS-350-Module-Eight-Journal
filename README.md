# CS-350-Module-Eight-Journal

This portfolio includes two key artifacts from CS 350: Milestone Three (Button Integration) and the Final Thermostat Project. Together, these projects illustrate the progression from basic hardware input handling to a fully integrated embedded system. The main objective was to design and implement a smart thermostat prototype capable of reading environmental data, responding to user input, displaying system status, and simulating communication with a backend server. The final solution utilized a Raspberry Pi to integrate GPIO buttons, LEDs, an LCD display, an I2C temperature sensor, UART output, and a state machine to manage system behavior.

What I Did Particularly Well

One of my strengths was successfully integrating multiple hardware peripherals into a single cohesive system. I effectively employed a state machine to manage the thermostat modes (off, heating, cooling), ensuring that the LEDs, buttons, sensor readings, and display outputs worked together reliably. I also excelled in incremental testing and debugging, validating each component independently before full integration. This approach helped prevent cascading failures and made troubleshooting more efficient.

Areas for Improvement

An area where I could improve is early planning for edge cases and user interaction timing, particularly for button presses and long-press behavior. While the system functions correctly, spending more time upfront on the interaction flow could reduce the need for later adjustments. I also aim to enhance my documentation with more diagrams and inline comments to assist future collaborators.

Tools and Resources Added to My Support Network

Throughout this project, I added several valuable tools and resources to my support network, including the GPIOZero library documentation, Adafruit sensor libraries, hardware component datasheets, and serial debugging tools such as Minicom. I also gained experience using GitHub as a version-control and portfolio platform, which I intend to use in future courses and projects.

Transferable Skills Gained

The skills developed in this project are highly transferable to other coursework and professional endeavors. These include embedded systems programming, hardware-software integration, state machine design, debugging physical systems, and working with communication protocols such as I2C and UART. Additionally, designing with maintainability and scalability in mind is a skill that is broadly applicable across software and systems engineering roles.

Maintainability, Readability, and Adaptability

I ensured this project was maintainable and readable by using consistent formatting, descriptive variable and function names, modular design, and clear comments explaining system behavior. The implementation of a state machine makes the system easy to extend with new modes or behaviors, and separating hardware interactions into logical sections allows the code to be adapted for different hardware platforms in the future.
