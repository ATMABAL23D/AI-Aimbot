# Base Undetectable Aimbot
Watch the video! - Coming Soon

Join teh Discord - https://discord.gg/rootkit

## Current Stats
This bot's speed is VERY dependent on your hardware. We will update the model it uses for detection later with a faster one.

Bot was tested on a:
- AMD Ryzen 7 2700
- 64 GB DDR4
- Nvidia RTX 2080

We got anywhere from 5-15 corrections per second which is pretty slow. All games were ran at 1280x720 or close to it.
The main slow down is the model's prediction speed averaging anywhere from .09-.29s.
The second biggest slow down is the garbage collection. It runs only once per second and takes about .05 seconds to run in generation 0.

ANYTHING dealing with Machine Learning can be funky with your computer. So if you keep getting CUDA errors, you may want to restart your PC in order to make sure everything resets properly.

### REQUIREMENTS
- Nvidia RTX 2080/3070 or higher
- Nvidia CUDA Toolkit 11.3 (https://developer.nvidia.com/cuda-11.3.0-download-archive)

### Pre-setup
1. Unzip the file and place the folder somewhere easy to access

2. Make sure you have a pet Python (aka install python) - https://www.python.org/

3. (Windows Users) Open up either `PowerShell` or `Command Prompt`. This can be done by pressing the Windows Key and searching for one of those applications.

4. To install `PyTorch` go to this website, https://pytorch.org/get-started/locally/, and Select the stable build, your OS, Pip, Python and CUDA 11.3. Then select the text that is generated and run that command.

5. To install `detectron2` go to this website, https://detectron2.readthedocs.io/en/latest/tutorials/install.html and follow the instructions. They don't officially support Windows but it will work on Windows.

6. Copy and past the commands below into your terminal. This will install the Open Source packages needed to run the program.
```
pip install PyAutoGUI
pip install PyDirectInput
pip install Pillow
pip install opencv-python
pip install mss
pip install numpy
```
***IF YOU GET THE FOLLOWING ERROR `pip is not recognized as an internal or external command, operable program, or batch file` Ask someone in the discord to help you out. We will be releasing a video about this soon since all the videos available for it are garbage.***

### Run
If you have python and the packages you are good to go. Load up any game on your MAIN monitor and load into a game.

1. (Windows Users) Open up either `PowerShell` or `Command Prompt`. This can be done by pressing the Windows Key and searching for one of those applications.

2. Type `cd ` (make sure you add the space after the cd or else I will call you a monkey)

3. Drag and drop the folder that has the bot code onto the terminal

4. Press the enter key

5. Type `python main.py`, press enter and that is it!

**We are always looking for new Volunteers to join our Champions!
If you have any ideas for videos or programs, let us know!**
