# CS370-ProjectTwo

### •	**Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?**


For Project Two, I was given some starter code which included the environment (TreasureMaze.py) and an experience replay system (GameExperience.py). Both of these files served to define the maze structure as well as store episodes in order to help the intelligent agent (pirate) learn through reinforcement learning. I was also provided with a Jupyter Notebook that contained a skeleton of an implementation of deep Q-learning. This is where I needed to create my own code. I had to complete the missing logic for training the intelligent agent (pirate). 

The code that I created focused on implementing the deep Q-learning algorithm as well as train the neural network model by retrieving and updating its state-action values using experience replay, adjusting hyperparameters such as epochs and batch size in order to optimize training performance, and evaluating the performance of the intelligent agent in order to determine if it had reached a 200% win rate. In the end it took multiple iterations where I tested different hyperparameters in order to balance efficiency and accuracy. I am happy to report that I ultimately found an optimal setting where the runtime was reduced, and a strong learning performance was maintained as well.


### •	**Connect your learning from throughout this course to the larger field of computer science:**

## o	What do computer scientists do and why does it matter?

Computer scientists solve complex problems by designing and building both software and hardware, developing algorithms, designing intelligent systems, and optimizing computational efficiency. They make sure that the software optimizes processes, manages data, and also enhances the user’s experience. They are also in charge of performing much research and analysis about theories that they can develop and test in order to help address the main problems they are trying to solve. This matters because computer scientists enable companies to focus more on their mission and less on manual data processing, which in the end improves the overall efficiency of the software and as a result the productivity of its users/clients and the company’s team as a whole as well.

## o	How do I approach a problem as a computer scientist?

I approach a problem as a computer scientist by first breaking down the requirements, taking the time to plan adequately based on the requirements breakdown, and finally moving on to the iteration. In this project for example, these were the steps I followed to approach the problem:
1.	Understand the problem – I first proceeded to identify what the goal is. In this case it was that the intelligent agent (pirate) had to reach the treasure.
2.	Analyze Constraints – Then I went ahead and identified what the constraints were. In this case the intelligent agent (pirate) moves in a maze but can only take valid actions and needs to maximize its long-term rewards.
3.	Select an algorithm – In this step I chose to use a deep Q-learning algorithm due to its ability to handle complex state-action spaces.
4.	Implement and train – Here a neural network was built, the hyperparameters were adjusted and the agent was trained using experience replay.
5.	Optimize and evaluate – This is where I adjusted epochs and batch size in order to improve efficiency.

## o	What are my ethical responsibilities to the end user and the organization?

I consider that my ethical responsibilities to the end user and the organization are the following:
- Bias and fairness – I need to ensure that reinforcement learning models are trained on diverse scenarios in order to prevent bias in its decision-making.
- Transparency and explainability – I need to ensure that the decisions that the AI makes are understandable to humans. This means that the intelligent agent’s state-action values need to be interpretable so that humans can understand why it makes its choices.
- User data and privacy – This one is what the end user tends to worry about the most which of course we need to ensure that data protection is properly set in place. This is essential and cannot be ignored.
- Safety considerations – I need to ensure that reinforcement learning intelligent agents that are used in critical applications such as healthcare or self-driving cars are properly tested out in order to prevent any harmful or unintended behaviors.

Overall, my ethical responsibilities to the end user and the organization falls in that I need to ensure that the AI systems that are built not only benefit society but also minimize its risks.
