# ComputerGeigerCounter

Tracks how long you've had your computer unlocked (and therefore, presumeably, working). Encourages you to take a break for at least 5 minutes by gradually changing colour from green to red. 

## Run on startup

I find it super valuable to run the app on startup because then I don't have to remember to run the app. If you want the app to run on startup:

1. Open the solution in your preferred Visual Studio. 
2. Change the drop down from Debug to Release

![image](https://user-images.githubusercontent.com/29092573/177966781-89f255c1-4522-49b6-a8e7-e35b9e6f8a7c.png)

3. Build the solution
4. Go to the solution bin folder
5. Go to Release -> netcoreapp3.1
6. Right click on the `.exe` file
7. Click Send to -> Desktop (create shortcut)
8. Find the shortcut on your desktop and move it to `C:\Users\<<< your name >>>\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup`
