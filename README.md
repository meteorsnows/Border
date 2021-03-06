# Border
Border is a simple overlay for RTS games (such as Age of Empires 2) for displaying build orders on top of the game. It is mainly intended for new players or getting help playing new maps. This will help you to learn the strategies that are used online. You might find features that are tailored to Age of Empires 2, since it was the reason for my to build this. For Starcraft 2 there is a widely used [commercial app](https://lotv.spawningtool.com/build/).

If you have no idea what a Build Order is or don't know what the app means with something, check out [this](https://github.com/abductedPlatypus/border/wiki/build-orders) for a short read.

__Important:__ Not all build orders have been tested by multiple people, so I'd be happy if you comment on the default Build Orders. You leave your comments [on this issue](https://github.com/abductedPlatypus/Border/issues/1).

![sample](https://github.com/abductedPlatypus/Border/raw/gh-pages/Border-Sample.jpg)

## Features
- Show Build Orders on top of your game  
- Quickly cycle through build orders  
- Highlight your current task  
- Click through the overlay and control it with hotkeys  
- Default Build Orders included (AoE2)  
- Create and share your own Build Orders  

## Getting Started
1. [Download the latest version of the app](https://github.com/abductedPlatypus/border/releases/latest)
2. Launch the app
3. `Right-click` the to see all the options.
4. Press `Alt + \` or `right-click` and press `Click Through Window`
4. Start the Game and play versus AI
5. Select a Build Order (Alt+ArrowUp/ArrowDown)
7. Press `Alt + Space` to Highlight the first step
8. Execute the highlighted step
8. Repeat step 7 until done
8. Win the game
9. Press `Alt + \`
10. `Right-click` -> `Quit`
11. Be happy

## FAQ

### Can I use this online?
It's up to you. The current version of this overlay does not communicate with the game so I doubt they will detect it.  
I think it's okay, I used to have my tablet up with a couple of Build Orders. But I always lost track. But one could argue that it removes the skill of game knowledge. 

### Why did you make this tool?
I wanted to learn a new programming thing and I was really into learning Age of Empires 2.

### Can I add my own Build Orders?
Yes, it does require a bit (straightforward) of editing a textfile (e.g. Notepad) though. See [this page](https://github.com/abductedPlatypus/border/wiki/add-build-orders) for details.  

If you made great build orders you and would like to donate them to this app [open an issue](https://github.com/abductedPlatypus/Border/issues/new).

### I want to change some hotkeys and some colours. How do I do that?
You can edit the settings.json file with a text editor. Which will allow you to modify the values. You can get the key codes [from this page](https://msdn.microsoft.com/en-us/library/windows/desktop/dd375731(v=vs.85).aspx), use the codes that look like `0x01`.

### How do I know if there is a new version?
The app will bug you about it.

### Your Build Orders Suck
[FeelsDautMan.](https://github.com/abductedPlatypus/border/wiki/add-build-orders)  

### All Hail King DauT!
_Amen_

### Is there a Forest Nothing Build Order included?
1
### Can I help with the app?
Try out the app, and test the default Build Orders. Want to do some programming? Sure, fork & play around with the code for a bit, then check out the [issues](https://github.com/abductedPlatypus/Border/issues). 

### How do I compile the code?
Fork the code, then open it in Visual Studio with the latest C# and Windows Presentation Foundation (WPF) installed.

### Can I ask you something else?
Si, either on [twitter](https://www.twitter.com/abductypus) or by creating an [issue](https://github.com/abductedPlatypus/Border/issues/new).
## Possible Future Features
If people want these features I might add:
- A settings window
- Timer - automatically advandce through the steps, or keep track of your speed records.
- Variants - quickly update the build order based on the situation.
- In-App Build Order Designer
- Share Build Orders with others

