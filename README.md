# CS-230: Operating Platforms

## The Gaming Room Software Design Document

This repository contains my completed Software Design Document for CS-230 at Southern New Hampshire University. The project involved designing a software application for a client, The Gaming Room, and evaluating different operating platforms to determine the best approach for their needs.

### Briefly summarize The Gaming Room client and their software requirements.

The Gaming Room is a client that wanted to expand its existing Android game, Draw It or Lose It, to support multiple platforms. The game involves teams competing to guess images as they are displayed. The client needed a system that could support multiple teams and players, maintain unique game and team names, and ensure only one instance of the game service was running. The application also needed to be scalable, secure, and accessible across different devices.

### What did you do particularly well in developing this documentation?

I think I did a good job comparing different operating platforms and explaining why Linux would be a good choice for the application's server environment. I considered performance, security, scalability, and cost instead of focusing on just one factor. I also think I did well explaining how the different components of the application would work together.

### What about the process of working through a design document did you find helpful when developing the code?

Creating the design document helped me understand how important planning is before writing code. Breaking down the requirements and creating a UML diagram made it easier to understand how the classes should interact. It also helped me see how design patterns, such as the singleton pattern, could be used to meet specific requirements.

### If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I could revise one part of my work, I would expand the system architecture section to include more details about how the application would handle increasing numbers of users. I would also include additional diagrams showing how the server, database, and clients communicate. I think this would make the document easier for another developer to follow.

### How did you interpret the user's needs and implement them into your software design? Why is it important to consider the user's needs when designing?

I started by identifying the client's main requirements and considering how each one would affect the application's design. For example, the requirement for unique game instances led to using the singleton design pattern, while the need to support multiple devices influenced my recommendation for a web-based application. Understanding user needs is important because even well-written software won't be successful if it doesn't solve the problems users actually have.

### How did you approach designing software? What techniques or strategies would you use in the future?

I approached the project by reviewing the requirements, identifying potential constraints, and comparing different solutions before making recommendations. I used object-oriented design principles, UML diagrams, and research into operating platforms to guide my decisions. In future projects, I would continue using these techniques while also putting more emphasis on scalability, security, and testing earlier in the design process. This project helped me understand how important it is to think about the overall system rather than just the code.
