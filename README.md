> [!CAUTION]
> # ⚠️ **Disclaimer**  
> This is **not my original project**.  
> It is a **fork** of [visual-refresh-compact-title-bar](https://github.com/surgedevs/visual-refresh-compact-title-bar) with personal customizations.  
> All credit goes to the original creator(s).


# Visual Refresh Compact Title Bar

The new Discord theme (also called, and from now on referred to as Visual Refresh) changed the window title bar to be more fat, now also including your inbox, help, and the update button.
This theme aims to move the buttons from the title bar down into the channel header and remove the title in the middle, but still give you a small bar that you can grab the discord window on to move it around (people had issues with that):

Before:
![image](https://github.com/user-attachments/assets/4fd945aa-b31f-4f56-9e67-099efc8b8630)

After:
![image](https://github.com/user-attachments/assets/1a0a3718-dc30-411f-9404-579f5ed65509)

Install:
Use [Vencord](https://github.com/Vendicated/Vencord) or an equivalent client mod that allows you to install themes.

Paste the following link into your online theme links:
```
https://raw.githubusercontent.com/MEWPASCO/visual-refresh-compact-title-bar-fork/refs/heads/main/desktop.css
```

**If you are on a browser, Vesktop, or a client which does not come with window controls, this fork is not aimed at you**

Alternatively if your client does not support online themes you can download one of the theme files found in this repository and put them into your theme folder.

## Config
Put this into your QuickCSS (Or any non-Vencord equivalent) to configure some behavior of this theme:
```css
:root {
    /* controls the vertical position of the window buttons */
    --vr-header-snippet-top: 0px !important;
    /* controls the space above the server list */
    --vr-header-snippet-server-padding: 0px !important;
    /* controls the space the window buttons get on the channel header, experiment around with this if you get gaps or the buttons overlap! */
    --vr-header-snippet-space: 230px !important;
    /* controls the space to the right of the window buttons, good if you are using themes like midnight which add padding to the bar */
    --vr-header-snippet-button-padding: 0 !important;
    /* controls the space that you'd like to have on the top bar - increase/decrease bar size and move windows controls with it at the same time */
    --vr-top-spacing: 20px !important;
}
```
### --vr-header-snippet-space cheat sheet
Try these if you dont want to find out the spacing yourself!

- Desktop Default: 180px
- Desktop Spacious UI Scaling: 200px
- Browser: 85px
