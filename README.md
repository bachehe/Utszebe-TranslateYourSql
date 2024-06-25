# Utszebe

utszebe

#Instalation 
To run Angular start from 
1. Change Execution Policy:
To change the execution policy, you can use the following command in POWERSHELL:
  Set-ExecutionPolicy RemoteSigned
This allows locally created scripts to run, but requires downloaded scripts to be signed by a trusted publisher.
If you are on a highly secure system and trust the scripts you're running, you can set the execution policy to "Unrestricted." However, this is generally not recommended for security reasons.
  Set-ExecutionPolicy Unrestricted
You will need Node.js LTS version that u can download from: https://nodejs.org/en/download
Then in console client opened project from new terminal run below commands
  npm install -g @angular/cli
  npm install
  
