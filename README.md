# EE488_AI_Convergence_Capstone_Design
used Pytorch and Stable-Baseline3

## Volleyball
Midterm project where agents playing Slime-Vollyball(https://github.com/hardmaru/slimevolleygym) is trained
Few techniques used to train the best agent

1) Extensive hyperparameter tuning
2) Environment wrapper for action space, reward clipping, etc
3) opponent scheduling for various experiences

ranked #1 overall in the class for three diffenrent tasks(train with A2C, train with PPO, desing custom network)

## Football
Final project where agents playing Google Research Football

(https://blog.research.google/2019/06/introducing-google-research-football.html?m=1) is trained

Various techniques used to train proper football-playing agent(PPO algrotihm used)

1) Custom feature extractor: Created custom feature extractor based on the architecture of Google Research team
2) Action shaping: Induce the agent to perform necessary action among large pool of actions
3) Reward shaping: Proper rewards for the agent to feed from
4) Training method: Exceptional training method to induce strategical movement from the agent(sequential reward + sequential training environment)


