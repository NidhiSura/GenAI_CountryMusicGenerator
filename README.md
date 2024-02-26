# GenAI_CountryMusicGenerator

This is a project in natural language processing for Stevens' CS559 course. Part 1 of this project was genre-based classification of song lyrics using neural networks, performed by my teammate **Nikhil Shah**. This is also my first time delving into the world of GenAI, so if you come across this page as a beginner to generative AI, "Welcome, this is going to be the most exciting journey for you!"

Part 2 involved generative AI to create lyrics for any given genre. The code snippet included in this folder pertains to only country music, since the other files are identical except for the key difference being that they were trained on different subsets of our lyrics dataset. The dataset was obtained from Kaggle, and can be found at https://www.kaggle.com/datasets/deepshah16/song-lyrics-dataset/data

If you are running this code, I would advise that you add checkpoints to save your model between epochs since my VSCode kernel would crash every 2-3 epochs. I also recommend training it for upwards of 20 epochs at the current model complexity, since anything lower than that will lead to absolute gibberish (although, country music is mostly melodic gibberish anyway).

As usual, please use this code only as a reference for academic purposes, since adhering to your university's academic code of integrity is of utmost importance to your academic journey and knowledge gain.
