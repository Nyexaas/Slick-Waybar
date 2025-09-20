# Slick-Waybar
A simple design for waybar

> [!WARNING]
> 
> This branch is made for 27 inch screen.
> 
> Other size of screen may have problems with sizes.
>
> For laptops: check the Laptor repo.


<img width="1920" height="1080" alt="FullScreen" src="https://github.com/user-attachments/assets/50e34ddc-a21a-4ab9-b826-f2c03f5ab682" />


<img width="244" height="62" alt="Waybar" src="https://github.com/user-attachments/assets/e7dfbd2f-9faa-4b75-9d25-ee3542103b2d" />



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
>``` // "output": "DP-2", ```
>
>Into :
>``` "output": "Your screen", ```

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
