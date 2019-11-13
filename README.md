# Project 3 Generative Audio 
# Guitar Fingerstyle Reform

Jiaye Wang, jiw609@ucsd.edu

## Abstract
Fingerstyle guitar is the technique of playing the guitar by plucking the strings directly with the fingertips, fingernails, or picks attached to fingers, as opposed to flatpicking (plucking individual notes with a single plectrum, commonly called a "pick"). The term "fingerstyle" is something of a misnomer, since it is present in several different genres and styles of music—but mostly, because it involves a completely different technique, not just a "style" of playing, especially for the guitarist's picking/plucking hand. 

For many musicians, guitar is like a small band. By hitting the guitar’s body, guitarists can mimic the sound of drum. By hitting the string in different angle, guitarists can also mimic the sound of different percussion instruments. Guitar fingerstyle develop this feature to a greater level. Hence, It will be interesting to figure out by combining machine learning and fingerstyle together, what kind of music are we going to produce. 

This project will using guitar pro 5 software/ github code to convert guitar tabs in to midi file. Then the midi file will be sent into Music Transformer to generate new music sequence. After this, the new formed midi file will be sent into Gansynth to replace guitar timbre to other timbre. 

In this project, I am going to Conny Berghäll - Revolution as an example. 



## Model/Data

Briefly describe the files that are included with your repository:
- trained models
- training data (or link to training data)

## Code

Your code for generating your project:
- Python: generative_code.py
- Jupyter notebooks: generative_code.ipynb

## Results

Documentation of your results in an appropriate format, both links to files and a brief description of their contents:
- `.wav` files or `.mp4`
- `.midi` files
- musical scores
- ... some other form

## Technical Notes

Any implementation details or notes we need to repeat your work. 
- Does this code require other pip packages, software, etc?
- Does it run on some other (non-datahub) platform? (CoLab, etc.)

## Reference

References to any papers, techniques, repositories you used:

- Papers
- Repositories
- Blog posts
Music Transformer: https://magenta.tensorflow.org/piano-transformer
• colab: https://colab.research.google.com/notebooks/magenta/piano_transformer/piano_transformer.ipynb

GANSynth: https://magenta.tensorflow.org/gansynth
• colab: https://colab.research.google.com/notebooks/magenta/gansynth/gansynth_demo.ipynb

https://en.wikipedia.org/wiki/Fingerstyle_guitar
https://www.youtube.com/watch?v=9r9ghRna95I
