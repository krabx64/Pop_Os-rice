### Pop_Os! Rice
make [pop os](https://support.system76.com/articles/customize-gnome) optimal and simple 

-----

**Pop!_OS Dock Optimizer Script** [`dock.sh`](https://github.com/krabx64/Pop-os-rice/blob/main/dock.sh)

This fork aims to make dock minimal and optimized

- uses  "zenity" tool for guide [temporary]

Required packages: `dbus-x11` `gnome-extensions`

- clone the repo : `https://github.com/krabx64/Pop_Os-rice.git`
-  make the script executable.`dock.sh`
- the script will prompt you to select a color using a color-picker dialog box.
- reload cosmic DE 


<details>
  <summary>
    <a href="https://github.com/Aylur/gnome-extensions">widget-shell-extension</a>
    
  </summary>
  <pre>
  
Battery Bar, Dash Board, DateMenu Mod, Media Player, Power Menu, Workspace Indicator, Notification Indicator, Modified Quick Settings, Background Clock.

</pre>
</details>

<details>
  <summary>
    <a href="https://extensions.gnome.org"> Extension adding-manually </a>

Copy the folder to ~/.local/share/gnome-shell/extensions directory
Once you have the files copied into the correct directory, go inside it and open the metadata.json file. Look for the value of uuid.
Make sure that the name of the extension’s folder is the same as the value of uuid in the metadata.json file. If not, rename the directory to the value of this uuid.
reload gnome shell.

</pre>
</details>
