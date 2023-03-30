![dotfiles](https://user-images.githubusercontent.com/109595809/228862367-4c1792a3-893e-46ce-81a3-8b68a95b714b.png) <br />
![rice](https://user-images.githubusercontent.com/109595809/228884088-c60b07d1-4114-467a-b173-8066846ede6d.png)


# Installation
What you need before installation my gruvbox rice <br />
>Arch user 
>```
>yay -S i3-gaps dunst dmenu ttf-font-awesome polybar light 
>```

<br />

>Ubuntu user
>```
>sudo add-apt-repository ppa:regolith-linux/unstable
>```
 > ```
 > sudo apt update
 > ```
 > ```
 > sudo apt upgrade
 > ```
 > ```
 > sudo apt install build-essential git cmake cmake-data pkg-config libcairo2-dev libxcb1-dev libxcb-util0-dev libxcb-randr0-dev libxcb-composite0-dev python3-xcbgen xcb-proto libxcb-image0-dev libxcb-ewmh-dev libxcb-icccm4-dev dmenu i3-gaps dunst fonts-font-awesome light libjsoncpp1 libjsoncpp-dev libuv1-dev libuv1 lua-luv
 > ```
 > [Install lates polybar version in this repo](https://github.com/polybar/polybar/releases)
 > 
 >`(1)$ cd polybar/`
 >`(2)$ mkdir build`
 >`(3)$ cd build`
 >`(4)$ cmake ..`
 >`(5)$ make -j$(nproc)`
 >`(6)$ sudo make install` <br />
If you get an error, make sure you have installed the dependencies.
