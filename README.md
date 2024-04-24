# Black_Space Theme for Windows 11 22H2
I might be switching to a new device soon :), so I made a guide for me to not take a whole day to get my setup back again. The theme is high contrast with pure black and white accents, this theme is based on the game Omori.

# Disclaimer ! ! !
I won't myself recommend this setup much because it has a LOT of third party software running in the background, and I have to wait atleast a minute for a proper startup, but then again my pc is a potato.

This Setup right here was literally made for a laptop screen and is mainly for my own use, you *will* have to use your own knowledge about your own pc and you might have to edit files for different themes/rainmeter skins like I had to. I will take no responsibility if you harm your pc in any way. I might help/answer any questions if I myself knew the answer. Also what lies below is a literal text dump because I was bored, English is not my first language so sorry for grammar mistakes/formatting.

!!! ALWAYS CREATE A SYSTEM RESTORE POINT BEFORE TRYING ANY SETUPS OR THEMES, SAME SHOULD BE DONE HERE !!!
# Preview



https://github.com/ShadeZerox/Pure-Dark-Windows-11-Theme-22h2-/assets/155251572/d821caab-03b7-44cd-b21b-ed480b424828



# 1) Prerequisites-
- I'd recommend resetting your windows for this one, because you need 22h2 for this (Windows won't provide you 22h2 from their site so you gotta find it from somewhere else). Though you can revert back to 22h2 from windows update too, I am not too sure about that. (This is because Theme Patchers don't like updates 23h2 and above)
- After getting Windows 11 22h2 back, Updates can be disabled by -
   - Pause windows updates for 5 weeks from the settings (easiest option and the one I used, just pause it for another 5 weeks after 5 weeks are over)
   - Or use this https://www.easeus.com/knowledge-center/stop-windows-11-update.html
   - This might disable your microsoft store however, Just in case you wanna know
- Also get the main apps done -
    - Firefox (Its better than others cus customizability, I'll put mine below)
    - Spotify
    - Discord
    - Any other apps you might remember (All these apps are ofcourse not neccesary but I'd rather have those, also turn of startup for these for the time being)
 

# 2) BlackisBack by niivu (Windows Explorer/Titlebar Captions/Control Panel)
- Get BlackisBack by Niivu and extract it
- Get 7tsp gui 2019 edition and extract it (rename the .ee to .exe)
- Get SecureUXthemepatcher themetool
- Get StartallBack
- Get OldNewExplorer
- Run the theme tool as admin, tick on hook logon ui and install. (You might tick on rename default colors as an alternative cus they do the same thing according to themetool)
- copy the contents of windows 22h2 themes folder into C:/WINDOWS/RESOURCES/THEMES
- re open theme tool and choose the Black - Dash theme
- Go to the blackisback folder and open the 7tsp extras folder. There, remove the .remove from the .7z
- Open the 7tsp exe that you got earlier, then add a custom pack and choose the blackisback extras. Then click on patch and restart
- Now get the fluent keys icons by niivu and install the night version of those icons similarly (remove the .remove from .7z and patch it with 7tsp)
- Use these settings for OldNewExplorer (also click on install on top right)

  ![image](https://github.com/ShadeZerox/Pure-Dark-Windows-11-Theme-22h2-/assets/155251572/913508ff-6ffc-4354-a523-a2825b7b6196)
- Lastly, install StartAllBack and disable the custom start menu and taskbar (your choice tbh, I am going to hide both of these anyway below) and copy these settings
 ![image](https://github.com/ShadeZerox/Pure-Dark-Windows-11-Theme-22h2-/assets/155251572/04430f4b-c1c6-442a-8882-163f7a1054ca)
- Now your windows explorer should be perfect asf, looks hard but is quite straightforward

# 3) Pure Dark theme tool
- This is a way less known tool and if you are skeptical of it then its your wish, it didn't harm my pc in anyway
- Download the Pure Dark Theme Tool v2
- Click on the dark theme mode and done, all your titlebars, the action center, start menu and some other stuff are now pure black
- You might want to restart after this

# 4) Other Random Stuff for aesthetics
- Get CuteBorders and put it on startup
- Get FancyWM and put it on startup (also set the settings how you want)
  - If you have disabled the Updates then there is a good chance that microsoft store won't work. So instead of getting the zip file from their Github, you should use the .msixbundle
  - the .msixbundle is not signed so sign it yourself - https://beebom.com/how-fix-publisher-could-not-be-verified-error-windows-11/ (Just follow the first guide no need to go to powershell)
  - Also, set the gaps in settings menu to match the gaps in the droptop 4 skin you will install below, just to keep symmetry
- Get Flow Launcher (put on startup)
- Get Lively Wallpaper (put on startup) and get the OMORI wallpaper
- Get Buttery Taskbar but don't install it yet
 
# 5) Designing the Desktop
- Get Rainmeter and the Following skins
  - Droptop 4 (preferably an older version of like Feb or March 2024, for some reason the newer update bugs a lot)
  - WebNowPlaying for rainmeter (Droptop 4 comes with this but using the latest version to update it is better imo)
  - JaxCore (you need it for vallistart)
    - ValliStart
    - YourFlyouts
  -  Kit Clock by vinithkumar (https://www.deviantart.com/vinithkumar/art/Kit-883902985)
  -  My Quotes by ninjaki8
- Now firstly install Droptop 4 and set it up (Turn on always on desktop and size depends on screen (standard for me))
- I use catppuccin 2 community theme (Editted its colors to make it black) and basically no community apps (okay i guess i use the center music one) so get those two
  - You can use the edit version of the catppuccin theme here or change the colors yourself through theme builder
-  Rest of the skins are pretty self explainatory, the kit clock goes in the speech bubble, My quotes skin on the bottom left etc, copy it from the preview video
-  Install Jaxcore and get vallistart, Imma put my settings here
-  Lastly disable dragging

# 6) Setup app themes
## Spotify -
  - Install Spicetify and Spicetify marketplace (use the tutorial given on their site)
  - Install the comfy theme from the marketplace, adblocked from the extensions and change the comfy theme to yami in the drop down menu
 
 ![image](https://github.com/ShadeZerox/Pure-Dark-Windows-11-Theme-22h2-/assets/155251572/e06f46d3-2d13-4053-aae6-935f944dcecf)

## Discord -
  - Install Better Discord, Plugin repo and Theme Repo Plugin (This is against the ToS but I haven't seen anyone getting banned)
  - Install the midnight theme from theme repo and edit the colors

![image](https://github.com/ShadeZerox/Pure-Dark-Windows-11-Theme-22h2-/assets/155251572/7b20c2ce-8ae5-4931-80ee-cfa0bb4d4816)

## Firefox - 
  - https://github.com/soulhotel/FF-ULTIMA (Use Firefox Ultima)
  - Install Firefox colors extension and change colors to black and white carefully

![image](https://github.com/ShadeZerox/Pure-Dark-Windows-11-Theme-22h2-/assets/155251572/b24491c8-d2d4-40fb-8bdc-013ec1a8d719)

  - Install darkreader (optionally use very high constrast for pure black backgrounds)
  - Get webnowplaying extension for integration with rainmeter
  - Install Nighttab, go on its settings and import the config (Credits to Amadeus's hyprland dotfiles, I just made it pure black)
  - Optionally use browser fonts extension for custom fonts all over sites

# 7) Finishing Touches
- Install Nilesoft Shell and dumb the theme.nss given above into its imports folder (imports folder can be accessed Shift + right clicking taskbar, then clicking on shell and directory and then imports)
- Install Buttery Taskbar and put it on startup to disable the taskbar (The windows taskbar is basically of no use to me because kando can host all my shortcuts and I can just click alt - tab to see which apps are open, if you can't work without it then you can atleast hide the taskbar from windows settings, then it would pop up automatically when you bring your mouse below)
  - If you do install buttery taskbar, even then you can easily open the taskbar by right clicking the icon on left side of droptop, this might be usefull)  
- Install Kando https://github.com/kando-menu/kando (Personal Note: Your Kando config is there on your drive) (I won't add my kando config here because its literally for my pc and won't work on yours)
- Install Lightshot, a better screen snip tool
- Install Pulsar and use atom monokai black with one black syntax theme, edit the one black syntax theme to make it pure black
- Get mute.fm
- All of these are optional except hiding the taskbar
- All these above are completely optional

And Done! Thanks for reading till here future me, I hope you don't end up destroying the computer. This was a pretty long and low effort text dump.


