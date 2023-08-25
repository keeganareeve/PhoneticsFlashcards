# PhoneticsFlaschards 

Notebooks, other related code, and instructions to prepare certain datasets for learning phonetics through a flashcard-like system.  

Accordingly, this github repo contains three folders: PyScripts, Notebooks, and ShellScripts.  

#### Keywords: 
opencv-python, phonetic science communication, computational linguistics, spaced repetition, gamification
  
## Instructions
The first thing to do is prepare a dataset. My scripts and notebooks work best with the Dutch diphones dataset found publicly avaiable at this link (https://www.mpi.nl/world/dcsp/diphones/index.html) or the English diphones dataset found publicly available here (https://dingo.sbs.arizona.edu/~dpl/english_diphones.htm).  

Use the create_pictures.praat script found here (https://github.com/wendyelviragarcia/create_pictures), or some similar script for creating images containing the spectrogram and waveform of each diphone in order to create a directory full of images from the sound files found there.  

Even though only the first sound is used for learning the look of sounds in spectrograms and waveforms, diphones are used in order to show a natural level of variation due to coarticulation.  

You can then use the notebooks (so far, there is only one published: dutchdiphonesflashcards.ipynb)! There are instructions at the top of the notebooks themselves for running them.  

(Once the Python scripts are published, they will also contain instructions for running them at the top.)  
