# Transfer Learning Between Different Games via Generative Models
Train 11 good policies for 11 Atari games. Generate 10,000 trajectories of 1,000 steps each from the policy for each game.
Fit a generative model (such as the Transformer) to the trajectories produced by 10 of the games.
Then fine-tune that model on the 11th game.
Your goal is to quantify the benefit from pre-training on the 10 games. How large does the model need to be for the pre-training to be useful? How does the size of the effect change when the amount of data from the 11th game is reduced by 10x? By 100x?
