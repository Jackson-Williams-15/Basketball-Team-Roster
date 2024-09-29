# Basketball Team Roster
This a roster of some of the most famous basketball players with their statistics, injurey status, and their positions. 
## How to run a COBOL program in Visual Studio Code
- Clone the repository to your machine
-  Install WSL and Ubuntu Distribution
    - Follow this [documentation](https://learn.microsoft.com/en-us/windows/wsl/install) for installing WSL on windows
    - This build uses Ubuntu, run the following command to install the distribution
      
        `wsl --install -d Ubuntu`
    - If your default WSL distribution isn't Ubuntu run the following command
      
        `wsl --set-default Ubuntu`
  ### Open Visual Studio Code
  - Install WLS Visual Studio Code Extension
      - <a href="https://github.com/user-attachments/assets/6031d36c-45fc-4c73-97dd-2a561d9158f8">
  <img src="https://github.com/user-attachments/assets/6031d36c-45fc-4c73-97dd-2a561d9158f8" alt="Click me" width="500">
</a>

- Open an Ubuntu WSL session by following these steps
  - Open the command palette by pressing `Ctrl + Shift + P`
  - Type `WSL: Connect To WSL`
- To verify you’re now using Ubuntu in VS Code, open a terminal in VS Code
  - You should see this in the terminal
  
    `user@hostname:~$`
- Now that you're in the Ubuntu WSL environment, you can install GnuCOBOL:
  - run the following commands in the terminal:
  - `sudo apt update`
  - `sudo apt install gnucobol`
- After installing GnuCOBOL, you now compile the COBOL program using:
  - `cobc -x players.cbl`
- you will get a new executable file called `players`
- use the following command to run the executable `players`
  - `./players`
   
