# mint
guide step-by-step to create a minting website on stargaze


You need Linux or MacOS to follow the official guide: https://docs.stargaze.zone/guides/readme
we'll be going step by step, if you are code savy you can go to the official link above ^
note that i am also not, by any means, an expert or anything like that. google is your friend if you have questions, as i most likely can't answer them.

# Step one:
  Install LINUX or MACOS
  (The guide doesn't work on Windows)
  -You can choose a Virtual Machine, I installed Oracle VM VirtualBox
  -Create a "new" vm, install linux (i chose Ubuntu x64)
  
  
# Install Visual Code:
  -VM created, time to use it! initialize your virtual machine
  -At this point we need to install:
    Visual Studio Code and NodeJS 
    Go to visual studio code website - Download - .deb file for linux
  -Go to Terminal (on applications, you can type terminal and click on it)
    The package is usually at "/Downloads"
  -Write: 
  cd Downloads/ (hit enter, cd is when you want to open a directory)
  - Write: 
  ls (hit enter, ls is listing the files)
  - Write: 
  sudo dpkg -i cod (hit tab to get the entire namefile) (hit enter)
  - Wait a bit, and the Visual Studio is installed! you can check at your applications.

# Install NodeJS

  sudo apt install npm
  sudo npm install --global yarn
  
  (Check this for more explanation of below code: https://stackoverflow.com/a/67300542)
  
  sudo apt-get purge --auto-remove nodejs 
  curl -fsSL https://deb.nodesource.com/setup_17.x | sudo -E bash -
      (if you get an error that you don't have curl use the following:
      sudo snap install curl) after that write the curl command again
  sudo apt-get install -y nodejs
  
  
  
  
  
  

