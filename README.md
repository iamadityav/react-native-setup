# React-Native-Setup-CLI ( For IOS )
 FOR REACT NATIVE CLI (  in new System MAC  )
 
  1-( Optional ) Install iTerm2 .
	
    * Go to Iterm2.com and download it ( https://iterm2.com/ )
    https://iterm2.com/
    * It also uses default zsh shell for shell scripting.
    
          // I personally use iTerm2 over normal terminal as of it's different THEMES and Features and color combination which comes soothing to eyes.
        
  2-Install HOMEBREW ( Mandatory )
  
       // The work of Homebrew is that it simplifies the installation of software on MACOS as well as LINUX
       https://brew.sh/
    * Go to brew.sh and copy the command on the screen (   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"    )
    * Run the command on the iTerm2 or default shell in the main window .

	
 <img width="669" alt="Screenshot 2023-09-13 at 12 52 32 PM" src="https://github.com/iamadityav/react-native-setup/assets/70755876/5654b396-611d-4bc3-986a-d8fd25ce1af1">

		*After running the command copy the two codes shown at the end of the line to run it again in command

<img width="534" alt="Screenshot 2023-09-13 at 1 01 41 PM" src="https://github.com/iamadityav/react-native-setup/assets/70755876/3416c1d2-01d6-4f77-ae5c-398185fc10d6">

		* 1-echo 'eval'....... run this in command terminal
		* 2-eval "$(/opt/........)"
		* Check for Homebrew version to verify if it's installed or not brew --version

 3-Install git
 		
	 * brew install git
		// It helps for the source code management program

 4-Install node

	 * brew install node
	 * node --version
	 * npm  --version
		//npm is the world's largest Software Registry.
		//As it is free to use we can download all npm public software packages without any registration.


 5-Install watch

	 * brew install watchman

 6- Install X-Code ( For IOS )

	 * Head to Appstore and download and install Xcode in your system .
	 * You can manage your react native application for native IOS from XCODE only
	 * Check for Xcode version in the Command Line Tools under Locations tab inside XCODE according the below code 
	 * Under Components Tab Download your desired Simulator

 <img width="534" alt="Screenshot 2023-09-13 at 2 45 53 PM" src="https://github.com/iamadityav/react-native-setup/assets/70755876/ce992aed-ba12-4113-810f-f8b26b7af894">

   6.1- Install Ruby ( For IOS )

	     * brew install ruby
 	     // Ruby itself isn't directly used in React Native app development, it plays a role in the backend, automation, deployment, or integration aspects of react native project.

   6.2- Install Cocoapods ( For IOS )

	     * sudo gem install -n /usr/local/bin cocoapods
 	     // This command will install cocoapods , which help in install dependencies in your project for the IOS part of the project.


	


 ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------



 

 		
	

 
