# Windows dotfiles

Video: https://www.youtube.com/watch?v=5-aK2_WwrmM

After installing all dependencies, you need to refer the config file in your machina
Cloning project in *$USERPROFILE\.config* folder and on terminal run the command

	nvim $PROFILE.CurrentUserCurrentHost

Inside the file write the line
	
	. $env:USERPROFILE\.config\dotfiles-public\windows\powershell\user_profile.ps1

Restart the terminal powershell and watch the magic!
