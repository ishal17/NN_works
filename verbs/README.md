# Spoken Verbs Dataset

## Inspiration

Sound classification and speech recognition are some of the most complex areas of computer science. These problems are very important in the domain of human-computer interaction. What seemed to be the technology of the future is turning into reality before our very eyes. Today, you can find intelligent digital assistants everywhere. Siri, Google Assistant, Cortana, and others, all of these services are using their own implementation of speech and sound recognition systems. But why are these tasks hard to solve? The main difficulties, among many others, are: 
* Background noise. It is usually a complex task to separate speech from the background noise - especially when the sound is recorded in the street or at a cocktail party, where the noise is a similar speech from other conversations.
* Word separating. Another problem might be a quick talk. How a speech recognition system should know when one word ends and the next one begins. 
* Voice differences. Everyone's voice is different, it's like a fingerprint, and most importantly, that it can change from moment to moment. How should a system recognise what is said by a 40-year old man as good as by a 10-year old girl?
* Homonyms and homophones. What did a person say, "read", "red" or "rad"? 
This particular dataset can be used as an entry point into the world of artificial intelligence that not only can hear you but also understand you.

## About this dataset

This dataset consists of the recordings of different single-syllable English verb ("chase", "fetch", "sit" and "walk") converted into the 24x24 frequency-vs-time images (spectrograms). The labels are converted into integers from 0 to 3. The spectrograms are re-scaled to the 0-255 range. There's a total of 7920 examples, 1980 per each class. 

## Example models

Both CNNs and Fully-Connected Deep Neural Networks give great results.

## Metadata
Features: 1 image  
Rows: 7920  
Size: 4.01 MB  
Categories: Image, Classification  
License: https://creativecommons.org/licenses/by-sa/4.0/
