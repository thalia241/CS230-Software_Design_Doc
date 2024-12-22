# CS230-Software_Design_Doc

## Reflection Questions and Answers

### 1. Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
The Gaming Room is a client that developed the game Draw It or Lose It, inspired by the classic TV show "Win, Lose, or Draw." Initially designed for Android, the client wanted to expand the game into a multi-platform, web-based environment. Their key requirements included enabling multiple teams with unique identifiers, scalability for concurrent sessions, and ensuring platform independence.

#### 2. What did you do particularly well in developing this documentation?
One strength of the documentation was the clear identification and breakdown of requirements, such as platform independence, session management, and data uniqueness. The focus on modularity in the design allowed me to create a scalable and efficient solution that can accommodate multiple platforms while meeting the client’s specifications.

##### 3. What about the process of working through a design document did you find helpful when developing the code?
The design document served as a roadmap for aligning the technical architecture with the client’s needs. By addressing requirements like security and scalability upfront, it ensured that the code could be implemented with minimal rework. The structured sections also helped organize ideas, making it easier to prioritize features during development. 

###### 4. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
I would revise the evaluation of operating platforms to include more details about real-world cost implications and user experience on each platform. Adding case studies or performance benchmarks could provide stronger justification for the platform recommendations. 

###### 5. How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
The user's needs were interpreted through a combination of analyzing the game’s intended functionality and creating user stories that highlighted key interactions, such as joining teams and starting sessions. This guided the creation of unique identifiers and platform-independent designs. Considering user needs is crucial because it ensures that the software delivers a seamless experience, ultimately driving user satisfaction and engagement. 

###### 6. How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
The design focused on modularity, using principles like abstraction and encapsulation to simplify complex game logic. Techniques such as creating a domain model and evaluating architectural constraints helped align the software with client goals. In the future, I would incorporate more prototyping to gather user feedback earlier and apply iterative design to refine features during development. 
