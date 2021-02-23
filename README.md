# AWS Self Driving Car submission in AWS DeepRace-2019

In 2019 I participated in Amazon Web Services Deep Race Competition in Re:Invent event held every year. I had selected the Toronto Turnpipe Roadmap for simulating my DeepRacer Bot. 

### Resources and Packages Used

**Environment:** AWS Sage Maker and EC2

**Language:** Python 3.8

### About AWS DeepRace
- AWS DeepRacer is a car that is the best way to demonstrate Reinforcement Learning. It is a fully autonomous 1/18th scale race car driven by reinforcement learning. It lets you train your model on AWS. It also helps you to provide a Reward Function to your model that indicates to the agent (DeepRacer Car) whether the action performed resulted in a good, bad or neutral outcome.
- It is the world’s first global autonomous racing league, where you can load your model onto a DeepRacer Car and participate in the race.

### Reinforcement Learning
- It is a machine learning method that is focused on “autonomous decision making” by an agent(Car) to achieve specified goals through interactions with the environment(Race Track). Reinforcement learning is achieved through ‘trial & error’ and training does not require labeled input, but relies on the reward hypothesis. The better-crafted rewards function, the better the agent can decide what actions to take to reach the goal.
- Reinforcement learning differs from the supervised learning in a way that in supervised learning the training data has the answer key with it so the model is trained with the correct answer itself whereas in reinforcement learning, there is no answer but the reinforcement agent decides what to do to perform the given task.
- In the absence of training data set, it is bound to learn from its experience.

### Training the Model

![actionspace](https://github.com/ShrishtiHore/AWS_Self_Driving-Car-AWS_DeepRace_2019/blob/master/actionspace.png)

![tabledegree](https://github.com/ShrishtiHore/AWS_Self_Driving-Car-AWS_DeepRace_2019/blob/master/table.png)

### Hyperparameter Tuning

![hyperparameter](https://github.com/ShrishtiHore/AWS_Self_Driving-Car-AWS_DeepRace_2019/blob/master/hyper.jpeg)

### Results
- Submission was successful clearling all the required test cases with a time of 42 secs. Thus getting in the leaderboard of the event !
