This code was written as an exploration and playful experimentation with Markovify. The aim was to generate imaginative and random captions, spice them up with randomly selected emojis, and include a touch of social media appeal by adding hashtags based on specific words.

The Markovify folder contains the work on generating random Instagram captions using Markovify.
  - Captions.txt - data used for training.
  - emoji.txt - list of emojis for training.
  - markovify.html - contains Code and Results which are saved in html format.
  - markovify.ipynb - contains py code for the task.

### Code : 
- **DataSet:**
  - A dataset was compiled by conducting Google searches, extracting information from various websites, and consolidating the gathered details into a single file.
    
- **Markov Chain Model:**
  - Utilizes the Markovify library to create a Markov chain model.
  - Trains the model using a text file named "Captions.txt."

- **Caption Generation:**
  - Generates a random caption using the Markov chain model.
  - The maximum length of the generated caption is set to 100 characters.
  - The process allows multiple attempts to generate a valid sentence.

- **Emoji Selection:**
  - Reads a file named "emoji.txt" containing a list of emojis.
  - Randomly selects an emoji from the list and appends it to the caption.

- **Hashtag Creation:**
  - Defines a list of words to be excluded from hashtags (common prepositions, pronouns, etc.).
  - Iterates through words in the generated caption.
  - Converts words to lowercase and creates hashtags for each word (excluding specified words).
  - Appends the hashtags to a string.

- **Printing the Final Caption:**
  - Combines the original caption, emojis, and hashtags.
  - Prints the final caption, including line breaks between the original caption and hashtags.

This code essentially generates a creative and random caption, enhances it with a randomly chosen emoji, and adds hashtags based on certain words, creating a more engaging and social media-friendly output.
