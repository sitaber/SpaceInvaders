# Space Invaders
The classic arcade game [Space Invaders](https://en.wikipedia.org/wiki/Space_Invaders) recreated using `Pygame` and `python`. 

Information from [computerarcheology.com](https://www.computerarcheology.com/Arcade/SpaceInvaders/) was used to make the mechanics closely match the arcade version 

|![Screen shot of game play](./images/gameplay.png "Gameplay")|
|-------------------------------------------------------------|

## How to Play
1. Press <kbd>SPACE</kbd> to start play
2. Use the keyboard to control the player

| Control      | Button              |
|--------------|---------------------|
| Move Left    | <kbd>A</kbd>        |
| Move right   | <kbd>D</kbd>        |
| Fire laser   | <kbd>spacebar</kbd> |

3. Try for the high score!

## Installation
### For `Windows` 64 bit

- :arrow_down: [Download](https://github.com/sitaber/SpaceInvaders/releases) `SpaceInvaders-v1.0.0_windows_x64.zip` and unzip it.
- Run the executable named `spaceinvaders.exe` inside the extracted folder.

### `Linux/Debian` 64 bit based systems

#### Option 1: Download the zipped executable file

- :arrow_down: [Download](https://github.com/sitaber/SpaceInvaders/releases) `SpaceInvaders-v1.0.0_linux_x64.zip` and unzip
    - For example, if your download was saved to the `~/Downloads` folder:
    - Press <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>T</kbd> to open the shell if you are on `GNU/Linux` based systems and type
    ```bash
    $ unzip ~/Downloads/SpaceInvaders-v1.0.0_linux_x64.zip -d ~/Desktop
    ```
    This will unzip the folder on your `Desktop`
- Navigate to the unzipped folder, change the file permissions for the executable and run it
    ```bash
    $ cd ~/Desktop/SpaceInvaders-v1.0.0_linux_x64
    $ chmod +x spaceinvaders
    $ ./spaceinvaders
    ```
    
#### Option 2: Run as a script

You need to have `pygame` and _(obviously)_ `python` installed for this option. 

### For `Ubuntu/Debian`
- Install `python`, `pygame`, and all the necessary dependencies. The following is the easiest method:
    ```bash
    $ sudo apt-get install python3-pygame
    ```
- Clone or Download the repo
    - __Clone__
    ```bash
    git clone https://github.com/sitaber/SpaceInvaders.git
    cd SpaceInvaders/ 
    python3 spaceinvaders.py
    ```
    - __Download__
        - :arrow_down: [Download](https://github.com/sitaber/SpaceInvaders/archive/refs/heads/main.zip) the repo and unzip
        ```bash
        $ unzip ~/Downloads/SpaceInvaders-main.zip -d ~/Desktop
        $ cd ~/Desktop
        $ ## navigate to the unzipped folder
        $ cd SpaceInvaders-main
        $ python3 spaceinvaders.py
        ```

### For `MacOS` 
I don't have an `macOS` system to build the executable or test installing `python` and `pygame`.

You can follow these [instructions](https://webcache.googleusercontent.com/search?q=cache:kyThG2mLWUsJ:https://www.pygame.org/wiki/MacCompile+&cd=1&hl=en&ct=clnk&gl=us&client=ubuntu) from the `pygame` website, or do an internet search for them.

## Known Issues/Bugs

Running the `Linux` executable on an [ext4](https://en.wikipedia.org/wiki/Ext4) formated file system results in the incorrect scores being displayed. This behavior does not occur when running from [NTFS](https://en.wikipedia.org/wiki/NTFS) formatted partions, and therefore has no impact on the `Windows` executable.

This is fixed in `spaceinvaders.py` and will be included in the next "release" (whenever I package the executable again)

# ENJOY!
