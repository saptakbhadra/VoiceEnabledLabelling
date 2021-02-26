# VoiceEnabledLabelling
This project is made for speeding up the labelling process, as typing labelles for each image is much slower than simply speaking the label name. This project uses voice recognition to label the images. Just say "This is a {label name}" and the labelled image gets stored in you designated target folder.
## This project used Google's voice recognition model for turning speech to text.
### Steps to build this project
1. Git clone <url>
2. Create a folder names `images` and 'images_labelled' inside the project directory.
3. Put the images you want to label inside the `images` folder
4. Open text_speech_google.ipynb in jupyter notebook.
5. Run the commands.
6. Image gets displayed and the `Talk`. Speak the label name as __This is a <label_name>__.
7. After all the images are finished, check the 'images_labelled` folder, with **the labels done**
