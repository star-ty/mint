# mint
guide step-by-step to create a minting website on stargaze</br>


You need Linux or MacOS to follow the official guide: https://docs.stargaze.zone/guides/readme</br>
we'll be going step by step, if you are code savy you can go to the official link above ^</br>
note that i am also not, by any means, an expert or anything like that. google is your friend if you have questions, as i most likely can't answer them.</br>

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
      
  
  
  
  
  
  

