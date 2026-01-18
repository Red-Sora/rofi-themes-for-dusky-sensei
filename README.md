change the keybind of ALT, SPACE to acess the new app menu 
bind = ALT, SPACE, exec, pkill rofi; rofi -show drun -theme ~/.config/rofi/launchers/type-6/style-7.rasi -run-command "uwsm app -- {cmd}"


Step 1: Open the terminal in the folder

## Navigate to the directory where u have the fonts folder.    [note this]
here the folder contains the fonts folder 

cd /path/to/the/downloaded/folder

## Step 2: Run these commands


### 1. Create the local fonts directory (if it doesn't exist)
mkdir -p ~/.local/share/fonts

### 2. Copy the fonts from the folder to your system
cp -rf ./fonts/* ~/.local/share/fonts/

### 3. Update the font cache so the system sees them
fc-cache -fv
