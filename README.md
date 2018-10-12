# Disaster management

Introduction:
   Often at times of natural calamities, in addtion to prediction and forecasting we believe that good planning and proper execution of relief operations is very crucial to save many lives and reduce economic loss. So we decided to work on optimizing the disaster management process and which shall aid ...
 
 Idea:
    Our idea is to design and implement an algorithm which tries to efficiently manage resources and helps in plannning out rescue operations at times of natural calamities given the constraints such as available hot routes, time, measures to be taken, areas under alert, available work force, and people(as far as possible). We plan to use Particle Swarm Optimisation (PSO), minimum spanning tree solutions, and fractals (to match patterns) to find the best possible ways to allocate resources at the correct time, mitigate damage, reduce life loss and maximize the reach under the constraints mentioned above. 
    The key idea is to keep it as abstract as possible to be able to use under any disaster but at the same time keeping in mind that different disasters impose different constraints and different requirements.  
Inputs: Available resources, Work force, Hot routes, Areas and people under concern
Output: A chronological order of steps to be taken and the way the steps to be executed.

Impact: Sometimes when a disaster hits a city the work force is allocated to that city, but if it has hit another city in matter of hours we have no workforce to allocate to it. Also we cannot entirely allocate resources and workforce for evacuation alone, since we need to use some for analysing ways to mitigate the damage. Using the optimization we can arrange these segments of workers to appropriate sectors  
