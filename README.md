# live-wallpaper
Live Wallpaper For Gnu/Linux in Rust With Gui App

# Requirements
```
Opencv
Vtk
```

# Compile And Install
```
git clone https://github.com/Walker-00/live-wallpaper
cd live-wallpaper
cargo run
```

# Arch
```
#I use paru as my aur helper replace with your
paru -S opencv
paru -S vtk
wget https://github.com/Walker-00/live-wallpaper/releases/download/v0.1.0/rust-live-gui-0.1.0-1-x86_64.pkg.tar.zst
sudo pacman -U rust-live-gui-0.1.0-1-x86_64.pkg.tar.zst
rust-live-gui
```

# Debian
```
#Install opencv and vtk First
wget https://github.com/Walker-00/live-wallpaper/releases/download/v0.1.0/rust-live-gui_0.1.0_amd64.deb
sudo dpkg -i rust-live-gui_0.1.0_amd64.deb
rust-live-gui
```
