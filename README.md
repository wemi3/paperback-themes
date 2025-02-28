# Paperback Themes

## This repository includes all the available Paperback themes, as well as a Python program that allows you to create your own theme

Since the 0.7 release you have the option to use custom themes in the [Paperback app](https://paperback.moe/). These themes change the color of the foreground, background, text and other elements in the app.

---

## List of all the public themes

_(All these themes support both light and dark mode)_
_("**[...]**": All variations of that theme)_

1. **Discord**: Themes based on the standard [Discord](https://discord.com/) theme **[Standard, Dark]** (made by Celarye).
2. **Twitter**: Themes based on the [Twitter](https://twitter.com/) themes **[Dim, Lights Out]** (made by Celarye).
3. **Spotify**: Themes based on the [Spotify](https://www.spotify.com/) theme (original creator: Brandon, remade by Celarye).
4. **MonsterEnergy**: Themes based on the [Monster Energy](https://www.monsterenergy.com/) theme **[Green, Mule]** (made by Celarye).
5. **AniList**: Themes based on the [AniList](https://anilist.co/) themes **[Standard, High Contrast]** (made by Spot and Celarye).
6. **BlackAndWhite**: A theme completely in black and white (made by Spot).
7. **Apple**: A theme based on the official [Apple](https://www.apple.com/) colors **[Midnight Blue]** (made by Celarye).
8. **Minty**: An original theme which includes the colors pink and green (made by Minty and Celarye).
9. **Nord**: A theme based on the official Nord colors (made by borboss).
10. **Request**: Requested themes which might not be for everyone **[Sakura (Naruto)]** (made by Celarye).
11. **Basic themes**: Some basic themes which are currently being reworked into Advanced themes (made by Celarye) **[CelaryeBlue, CherryBlossomPink, Gray, turquoise, Paperback]**.

_Screenshots of how these themes look can be found in the [Github repository](https://github.com/Celarye/Paperback-themes)._

---

## FAQ

### Frequently asked questions regarding themes in the app

**1. How do I install/implement a theme?**

To implement a theme into the app you will have to share the file with the app (the same way you do with a backup) from the device you want to change the theme on. After this restart the app to make sure it is fully implemented.

**2. Can a theme file harm me or my device in any way?**

No, these files are basic JSON files which only change color values in the app.

**3. How do I switch between the light and dark mode theme version?**

The version of the theme that displays depends on the appearance setting of your iPhone/iPad. So if you have your iPhone/iPad in dark mode the app will be in dark mode as well and the other way around for when your iPhone/iPad is in light mode. To change this navigate to the the "Settings" app on your iphone/iPad, go to "Display & Brightness" and switch between dark and light mode under "Appearance". Another way to this to open control center (by swiping down from the right top or up from the center from your iPhone/iPad depending on the version of your operating system), long pressing the brightness bar and switching between dark and light mode with the button which appears on the bottom left.

You can also have your iPhone/iPad automatically change between dark or light mode when entering the app and then switch back when leaving the app using an automation in the "Shortcuts" app. Here is a guide on how to do this:

1. Open the "Shortcuts" app and tap on the tab "Automation".
2. Tap on the plus sign on the top right and select "Create Personal Automation".
3. In the list, find and select "App".
4. In the new window, click the "Choose" button, find the "Paperback" app and click "Done" on the top right corner, then underneath that select "Is Opened" and click "Next" on the top right corner.
5. Click the "Add Action" button and type "appearance" in the search bar, then select "Set Appearance", now choose between dark and light mode by selecting "Dark" and choosing in the pop-up, after that click "Next" on the top right.
6. Now turn off "Ask Before Running" and click "Don't Ask" on the pop-up, after that click "Done" on the top right corner.
7. Now repeat step 2) to 6) but choose "Is Closed" in step 4) and choose the opposite appearance mode in step 5).

**4. Why won't a theme install?**

There are a couple reasons that may cause this. The first one is that your app version is older than version 0.7 (r42), in this case make a backup and update your app. The second one is the possibility that the theme file is broken, if this is the case you may either open an issue on the Paperback themes Github or simply DM Celarye on Discord. And sometimes it is neither one of the above causes and can simply be fixed by restarting your phone.

**5. How do I reset the theme in my app to the standard one?**

The standard theme the app uses is the "**DefaultTheme**" file, share this file with the app to reset your app to the standard theme.

**6. Can I make my own theme?**

You may always make a request for a theme in the Github repository by making a feature request or on Discord by DMing Celarye. However, if you rather make a theme yourself it is recommended to check out "Theme creation" bellow this FAQ.

---

## Theme creation

### Info regarding theme creation for the app

There is a [Python](https://www.python.org/) program in the Github repository which you can use to make your own theme, you will need to [install Python 3](https://www.python.org/downloads/) to run it however. And feel free to DM Celarye on Discord the themes you made so he can add them to the public theme repository and Paperback Discord (if it fits the requirements shown bellow).

> **_DISCLAIMER:_**
>
> _All themes you make and want to be added to the public theme repository and Paperback Discord under your name will have to be made with the Python program from the Github repository, and you will also have to send a list of all the hexes you used (gets made by the program as well)._ > _You will not have to follow the guide in the program for 100% but if you don't you will need to justify it (however, both light and dark mode support is mandatory)._
>
> _These rules are to increase efficiency and quality of the themes._
>
> _Also make sure to not make any themes someone else got planned already (check with Celarye trough a Discord DM for that and let him know which ones you are planning on making so he can prevent duplicates from being made)._

---

**You may always DM Celarye on Discord for any questions regarding Paperback themes.**

---

**References (Discord):**

(Celarye: @Celarye # 0001)
(Brandon: @brandon # 7237)
(Spot: @spot # 1337)
(Minty: @minty # 0688)
(borboss: @borboss # 7877)
