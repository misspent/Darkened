![0 2 Banner Centered Main](https://user-images.githubusercontent.com/78914154/157298545-a87dedea-61ce-4221-b78d-84d58123388b.gif)

<h1 align="center">Preview</h1>
<p align="center">
        <img src="https://img.shields.io/github/license/misspent/Darkened?color=green&label=License%3A&style=for-the-badge" /></a>
        <img src="https://img.shields.io/github/issues/misspent/Darkened?label=Issues%3A&style=for-the-badge" /></a>
        <img src="https://img.shields.io/github/issues-pr/misspent/Darkened?label=Pull%20Requests%3A&style=for-the-badge" /></a>
</p>

### Main window + User popout
![1  Darkened Discord Theme Main Window version 3  Edited](https://user-images.githubusercontent.com/78914154/157456517-99410bc6-ff1a-45e1-b55a-6c2401fcdced.png)

<h1 align="center">📌 Information</h1>

### 📢 Installation
- Go into discord's settings
- Go to your `"Themes"`
- Click on `"Open Themes Folder"` button (Above the search bar)
- Move the `.theme.css` file into that folder (It should load it)
- Click the checkbox in the top-right corner of the theme in discord to enable it
### ✅ Features
* ✔️ Good ol' darkness
* ✔️ Optional Scrollbars
* ✔️ Optional Codeblocks
* ✔️ Optional Radial Status
* ✔️ Optional Channel Icons
* ✔️ Support for some plugins
* ❌ Light mode not supported
* ⭕ Will change button colour if requested.
* ⭕ Possibly change the Date-Month-Year separator if requested
* ⭕ All Imports in main.css I deem a requirement with my theme (may change)
### ℹ️ Credits
* **[xcruxiex](https://github.com/xcruxiex)**'s Friend Grid.
* **[CreArts](https://github.com/CreArts-Community)**'s Context Icons.
* **[LyGhT1337](https://github.com/LyGhT1337)**'s CodeBlocks.
* **[mwittrien](https://github.com/mwittrien)**'s Setting Icons.
* **[XYZenix](https://github.com/XYZenix)**'s DragNDrop Modals.
* **[Gibbu & Tropix126](https://github.com/DiscordStyles)**'s Radial Status.
* **[Xhylo](https://github.com/Xhylo/ChannelIcons)**'s Channel Icons -> Ported + additions & fixes.
* **[Nyria](https://github.com/NYRI4)**'s Discolored & no-scrollbars Imports + Used Comfy theme as a base.
* A friend who shall not be named.
* Used, took inspiration and or edited some snippets from other themes/servers; thanks Gibbu, ClearVision, Couve & others. 

<h1 align="center", margin= "0">📷 More Screenshots</h1>

(Previews/screenshots may become out-of-date at some point)
### User Settings
![2  Darkened Discord Theme Settings Version 3  Edited](https://user-images.githubusercontent.com/78914154/157456598-6bf81d10-398d-45e6-b85f-2758c368b2ac.png)

### Home + Friends section
![4  Darkened Discord Theme Friends Version 4  Edited](https://user-images.githubusercontent.com/78914154/157456612-56c42085-6a3f-42e4-84f9-53db0c8ee0e1.png)


<details>
  <summary align="center">☰ User Settings, Server Actions and Message Actions Menus</summary>
  <br>

| User Settings Menu | Server Actions Menu | Message Actions Menu |
| :---------: | :---------: | :---------: |
| <img width=300 src="https://user-images.githubusercontent.com/78914154/157084219-f549d866-dbe3-4bed-abd8-8fd15b9f0031.gif"></img>  | <img width=300 src="https://user-images.githubusercontent.com/78914154/157084265-cd1ed748-64cd-41dd-9b7d-0e3b619002a0.gif"></img>  | <img width=300 src="https://user-images.githubusercontent.com/78914154/157084308-4f320b91-5004-44b7-9fd3-4d8726188048.gif"></img>  |

</details>

<h1 align="center">📦 Channel Icons</h1>

I got my SVG Icons from the links below; it's in order from best to worst (in my opinion). I'm not the original creator of the import, meaning I have no idea where he got his from; however, if I find out, I will update this.
* 1st: https://icons.getbootstrap.com
* 2nd: https://heroicons.com
* 3rd: https://primer.style/octicons/
* Useful: https://superdevresources.com/free-svg-icons/

| Channel Icons | + Channel Icons | ++ Channel Icons |
| :---------: | :---------: | :---------: |
| <img width=300 src="https://user-images.githubusercontent.com/78914154/156762493-2becb9ee-c980-4fc8-b4b0-8667bab82151.png"></img>  | <img width=300 src="https://user-images.githubusercontent.com/78914154/156760708-4b77f747-8ef2-402b-8ecb-33409478a516.png"></img>  | <img width=300 src="https://user-images.githubusercontent.com/78914154/156760827-a29306c5-738e-4beb-b805-8b5c3b102888.png"></img>  |

<h1 align="center">📜 Extra(s)</h1>

→ Make sure Dark is selected in the appearance settings, or it'll look like someone dropkicked discord.  
→ The pictures don't fully show it, so I'll tell you here. There are borders around the essential containers; however, you can remove them by changing its variable to "none"

<details>
  <summary align="center">⌨ Variables</summary>
  <br>
        
```css
\==================================================================================\
\                                 Optional Variables                               \
\==================================================================================\
*/

:root {
  /* -- Others settings -- */

  /* Roundness of the fun stuff */
  --avatar-radius: 0px; /* Avatar roundness | Radial Status roundness */
  --status-radius: 8px; /* Status roundness */
  --server-radius: 0px; /* Server icons, borders, images and other containers roundness */
  --role-circle: 5px; /* Circles next to role names (Size not roundness) */

  /* Home Icon Image */
  --Home-Image-Icon: url("https://i.ibb.co/k4mXsGW/Mary-Shaw.png"); /* Default: https://i.ibb.co/k4mXsGW/Mary-Shaw.png | Free Upload Site: https://imgbb.com */

  /* Mention color */
  --mention-color: #0fffff; /* Default: #0fffff */
  --unread-color: rgb(0, 195, 209); /* Default: rgb(0, 195, 209) */
  --accent: 0, 195, 209; /* This works in conjunction with "--unread-color" | Default: 0, 195, 209 */

  /* Mention color in chat */
  --mention-color-bar: #00b0f4; /* Default: #00b0f4 */
  --mention-color-background: #00b0f41f; /* Default: #00b0f41f */
  --mention-color-hover: #00b0f41f; /* Default: #00b0f41f */

  /* Spotify plugin seek bar */
  --spotify-color: #1edc62; /* Default: #1edc62 */

  /* Tooltips */
  --tooltips: block; /* Set it to "none" if you don't want it | Default: block */

  /* Other */
  --roleslist-columns: 3; /* Amount of columns for roles in popout | Default: 3 */
  --dark: #151515; /* Codeblocks Import | Default: #151515 */

  /* Toggleable variables */
  --Discord-Watermark: flex; /* flex = ON, none = OFF */
  --Chat-GIF-Button: none; /* flex = ON, none = OFF */
  --Chat-Gift-Button: none; /* flex = ON, none = OFF */
  --Chat-Sticker-Button: none; /* flex = ON, none = OFF */
  --Home-Nitro-Channel: flex; /* flex = ON, none = OFF */
  --Home-Discovery-Channel: flex; /* flex = ON, none = OFF */
  --Context-Menu-Emoji-Toolbar: none; /* flex = ON, none = OFF */
  --Text-Channels-Capital-Letter: capitalize; /* capitalize, none */

  /* Radial Status */
  --rs-small-spacing: 0px;
  --rs-medium-spacing: 0px;
  --rs-large-spacing: 0px;
  --rs-small-width: 1.5px;
  --rs-medium-width: 1.5px;
  --rs-large-width: 1.5px;
  --rs-avatar-shape: var(--avatar-radius);
  --rs-online-color: #43b581;
  --rs-idle-color: #faa61a;
  --rs-dnd-color: #f04747;
  --rs-offline-color: #636b75;
  --rs-streaming-color: #643da7;
  --rs-invisible-color: #747f8d;
  --rs-phone-color: var(--rs-online-color);
  --rs-phone-visible: block;
  --rs-version: "2.0.6";
}
```
</details>

<details>
  <summary align="center">⌛ Write-up</summary>
  <br>

> =========================================================================================  
**This is my first discord theme. I’m still "new" to all this CSS stuff; I only jumped into it late last year and have slowly been changing my theme over the past few months. I gradually got more comfortable with CSS and updated + fixed my theme for public use/testing. Nyria's themes gave me a lot of inspiration, and you'll 100% see what I mean if you use this.**  
=========================================================================================  
> **The people in the screenshots are not me, and I've blurred stuff as I don't want friends to get spammed and or added. moreover, I'd prefer it if people didn't know what server(s) I'm in for obvious reasons, and I'm a relatively private person cause I am clapped.**  
=========================================================================================  
> **I'll update this as often as I can; however, I do not use canary version of discord, nor am I some mastermind that can instantly fix/add stuff, so the updates may take a while to push if they change containers etc. on that note, I hope you enjoy the theme, and if you encounter any issues, bugs or want me to attempt to add support for a plugin you use, please tell me. Trying to learn basic CSS to the best of my ability.**  
=========================================================================================  

</details>
