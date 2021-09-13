# emojiland
Landscapes generated using emojis and Python. There are two files in this project. 
The generate_land file contains the functions that generate the landscape, using 
a user input of columns and rows to define the size.

The save_to_file file uses the generate_land functions and saves the outputs as .txt files
in an outputs folder.

The patterns use the Perlin noise library for texturing. 
The Termcolor library is used for simple (quick and dirty) colouring of the inputs for better usability. 

# Installing / Getting started

This project uses the latest version of Python (3.9.7). Follow instructions for download at https://www.python.org/downloads/ 

# Developing

Run the following on your terminal:

git clone https://github.com/BethThayne/emojiland
cd emojiland

Open the code on your code editor - you can do this from your terminal if you have shell commands set up.

The following libraries need to be installed

python3 -m pip install termcolor
python3 -m pip install noise

