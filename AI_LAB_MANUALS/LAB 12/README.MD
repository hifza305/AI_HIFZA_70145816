LAB No 12
Implementation of Reinforcement Learning 

🔹 Task 1: Increase Episodes
Modify the code to run 50 episodes instead of 20.
Observe the score trend across episodes.
________________________________________
🔹 Task 2: Display State Values
Print the state array in each step and identify:
•	Car position
•	Car velocity
________________________________________
🔹 Task 3: Change Text Color & Location
•	Change score color from red to blue
•	Display text at position (200, 20)
________________________________________
🔹 Task 4: Track Best Performance
•	Store the score of each episode
•	Print the best (highest) score at the end
________________________________________
🔹 Task 5: Slow Down Visualization
Add the following line inside the loop:
pygame.time.delay(20)
Observe the change in animation speed.
________________________________________
🔹 Task 6: Compare with CartPole
Replace the environment with:
env = gym.make("CartPole-v1", render_mode="human")
Compare:
•	Reward behavior
•	Episode termination
•	Learning difficulty
________________________________________
🔹 Task 7: Simple Rule-Based Policy (Intermediate)
Replace random actions with:
if state[1] > 0:
    action = 2
else:
    action = 0
Observe whether the agent reaches the hilltop.
________________________________________
🔹 Task 8 (Advanced): Episode Length Analysis
Print the number of steps per episode and analyze:
•	Why some episodes last longer
•	Relation between steps and score
