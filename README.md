
## CASE BACKGROUND
Sensor networks hold the promise of truly intelligent buildings: buildings that adapt to the behavior of their occupants to improve productivity, efficiency, safety, and security. Over the last decade, there has been a growing interest in human behavior analysis, motivated by societal needs such as security, natural interfaces, effective computing, and efficient functioning. 
Mitsubishi Electric Research Laboratories (MERL), with the foresight of understanding the operational and functional advancements that the residential and office buildings might need, conducted an analysis with their own facility, studded with motion sensors.
As large-scale data collections on human behavior become more readily available, the need for effective methods and mathematical models for analysis becomes crucial in order to make good use of the sources. In machine learning, algorithms have been developed to recognize complex patterns and make intelligent decisions based on data. Traditional machine learning models have been used in the domain of human behavior analysis, though their limitations with new types of data and human-centric questions become apparent.
For example, many of the traditional machine learning models are supervised, requiring training data which is often impossible or illegal to collect on human subjects. 
In this project we choose to investigate probabilistic topic models as the basic tool. Topic models are chosen first and foremost for their unsupervised nature.

## BUSINESS CASE
With an intention of understanding human behavior, a dataset having the residual traces of spatio-temporal structure from people working in their laboratory has been provided.
The MERL sensor network is composed of passive infrared motion detectors. These sensors only detect presence and movement of heat sources, so they preserve much of the privacy of the occupants. The sensors are ceiling mounted at approximately two-meter intervals along hallways and in grids covering public spaces such as lobbies and meeting rooms. There are no sensors in individual offices. The sensors are installed with the intention of covering the floor area completely with little or no overlap between sensor fields of view. An understanding needs to be created so as to analyze and dissect the different behavioral patterns exhibited in the research facility. 
These different distinct behaviors can be further used to fulfil the operational and functional upgrades that the MERL facility plans on resorting to.

## OBJECTIVE
•	To find the routine of employee activity in office environments over sensor network data
•	To find the active engagement of employees in any organization thereby helping us to measure efficiency and effectiveness
•	To accurately detect the components of human behavior in a building. Develop a model that does not require individuals to be tracked before behavior is recognized, which will allow the system to be built with cheaper sensors, and eliminates much of the high-fidelity tracking
•	To examine the occupancy pattern of various spaces in the building
