<div algin="center"
  <img src="" alt="" width="195" height="90"/>

   # Dmenu 

   ### A ***simple*** and ***centered*** Dmenu for launching anything you want!

   ![Preview] (/.github/preview.gif)

</div>

This is my personal fork of Dmenu. It' a very simple centered bar to launch programs. 

<details>
  <summary> Click to see patches applied </summary>

  - Alpha
  - Center

</details>


## Prerequisites
You will need dev tools for compiling:

<details>
  <summary>Arch</summary>

  ```sh
  sudo pacman -S base base-devel 
  ```
</details>

<details>
  <summary>Debian/ubuntu</summary>

  ```sh
  sudo apt install build-essential 
  ```
  
</details>

<details>
  <summary>RedHat/Fedora</summary>

  ```sh
  sudo dnf groupinstall "Development Tools" "Development Libraries"
  ```
</details>


## Installation

```sh
git clone https://github.com/CarlosR759/dmenu-rice.git && cd dmenu-rice
```

```sh
sudo make clean install
```

>[!NOTE]
> - If you are using my dwm setup, then you can launch dmenu with <kbd>Super/Windows</kbd> + <kbd>d</kbd>
