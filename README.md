# mint
guide step-by-step to create a minting website on stargaze</br>


You need Linux or MacOS to follow the official guide: https://docs.stargaze.zone/guides/readme</br>
we'll be going step by step, if you are code savy you can go to the official link above ^</br>
This is mostly for people with no coding expertise that want to deploy their own minting site; note that i am also a newbie at programming. google is your friend if you have questions, as i most likely can't answer them. you can also ask on discord #stargaze-tools if needed!</br>
Also really appreciate if anyone want to contribute to this or point out my mistakes haha...

# Step one:
  Install LINUX or MACOS </br>
  (The guide doesn't work on Windows)</br>
  -You can choose a Virtual Machine, I installed Oracle VM VirtualBox</br>
  -Create a "new" vm, install linux (i chose Ubuntu x64)</br>
  
  
# Install Visual Code:
  -VM created, time to use it! initialize your virtual machine</br>
  -At this point we need to install:</br>
    Visual Studio Code and NodeJS </br>
    Go to visual studio code website - Download - .deb file for linux</br>
  -Go to Terminal (on applications, you can type terminal and click on it)</br></br>
  The package is usually at "/Downloads"</br>
  -Write: </br>
  cd Downloads/ (hit enter, cd is when you want to open a directory)</br>
  - Write: </br>
  ls (hit enter, ls is listing the files)</br>
  - Write: </br>
  sudo dpkg -i cod (hit tab to get the entire namefile) (hit enter)</br>
  - Wait a bit, and the Visual Studio is installed! you can check at your applications.</br>

# Install NodeJS

  sudo apt install npm</br>
  sudo npm install --global yarn</br></br>
  
  (Check this for more explanation of below code: https://stackoverflow.com/a/67300542)</br></br>
  
  sudo apt-get purge --auto-remove nodejs </br></br>

  curl -fsSL https://deb.nodesource.com/setup_17.x | sudo -E bash -</br>
      (if you get an error that you don't have curl use the following:</br>
      sudo snap install curl) after that write the curl command again</br>
      
      sudo apt-get install -y nodejs
      

*Anytime it says you don't have the package, follow the instructions on the terminal to do so, for example, we tried but don't have git. Copy and paste the suggestion from the terminal on how to install it.

    sudo apt install git
    
From this point on, follow the guide at https://docs.stargaze.zone/guides/readme/1.-setup-a-basic-project  
   I'm just going to point out random parts you/I might be stuck here.
  
  use sudo yarn install instead of yarn install
  
  
  On step 2 Configure your project, config.js, you will need visual code to edit your config.js file after creating a copy from config.example.js
  
  
  

