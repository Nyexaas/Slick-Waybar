# Slick-Waybar
A simple design for waybar

> [!WARNING]
> 
> This branch is made for 14 inch screen laptop.
> 
> Other size of screen may have problems with sizes.

<img width="1366" height="768" alt="Full-screen" src="https://github.com/user-attachments/assets/28a5cc21-dd91-45b9-91a3-c6fe7a0715a9" />


<img width="209" height="55" alt="Icons" src="https://github.com/user-attachments/assets/c9cba585-eefc-429f-bb50-3bd204cdbefd" />




## " Requirements "

**Pipewire-pulse / pulse audio and wireplumber**

**Waybar**

**Fonts used** : " JetBrainsMono Nerd Font " and " JetBrains Mono NL Medium "

**icons** :  otf-font-awesome

>[!NOTE]
>Do not forget to change your timezone in the .jsonc
>
>If you use multiple screen but want waybar on only one of them change :
>
>``` // "output": "", ```
>
>Into :
>``` "output": "Your screen", ```
>
>waybar has an issue of the battery icon doen't update on it's own, only clicking on it or restart waybar make it update.

## Wallpaper
**Wallpaper source:** https://www.reddit.com/r/battlestations/comments/1f9sjpw/how_do_we_like_this_set_up/

**Direct link:** ( By u/YesButConsiderThis ) https://i.imgur.com/03tKTvr.jpeg


## Installation
Check if you have waybar installed, if not : install it.

>Yay command : ``` yay -S waybar ```
>
>Pacman command : ``` pacman -S waybar ```
>
>(Pacman may require to sudo or/and change to -Sy)

Download and extract the Waybar file containing the config.json and style.css .

Move the config and style files of this git to the waybar file. 

> You might need to use the command ``` sudo mv ```

Launch waybar and enjoy.
