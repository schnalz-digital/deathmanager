# DOOM I + II Launcher – MS-DOS Style
Relive the nostalgia of 1993 with this classic DOOM I & II Launcher, designed to emulate the authentic MS-DOS experience from id Software's DeathManager—now on Windows 11, macOS 15+ and Linux.

## System Requirements
- [x] Windows 11: Comes with the WebView2 Runtime preinstalled.
- [x] macOS 15: Apple Silicon and Intel support.
- [x] Linux: libwebkit2gtk-4.1-0 required.

## Getting Started
1. Download the [latest release here](https://github.com/schnalz-digital/deathmanager/releases/latest) on GitHub.
2. Extract the contents of the provided `.zip` file, which includes two files, into your DOOM folder.
3. Run the `executable` file to start the Launcher.
4. At the top of the Launcher, click on `Choose DOOM Port` and specify the path to your preferred DOOM Source Port ([Zandronum](https://zandronum.com/download) or [GZDOOM](https://zdoom.org/downloads)).
5. Click on the `+` icon next to `Game WAD` and designate the path to your `.wad` files. Add-ons in `.iwad, .pwad, .pk3, or .deh` format within the `WAD` folder will be automatically detected.
6. Choose a map and press `Go!` to frag demons.

> [!IMPORTANT]
> The `executable` file requires the `resources.neu` file as a dependency to function properly.

## Instructions – macOS
Follow the steps below to allow and run `DM.EXE` on macOS.
> **Note:** Replace `-mac_arm` with `-mac_x64` if you're using an Intel-based Mac.

1. Open the **Terminal** and type the following command:
```bash
sudo xattr -d -r com.apple.quarantine
```
After typing the command, **drag and drop** the `DM.EXE-mac_arm` **file into the Terminal** to append its full path, then press **Enter**.

2. Type the following command to make the file executable:
```bash
chmod +x 
```
Once again, **drag and drop** the `DM.EXE-mac_arm` **file into the Terminal** to complete the path, then press **Enter**. 

3. To run the executable, **drag and drop** `DM.EXE-mac_arm` **into the Terminal** and press **Enter**.

## Instructions – Linux
Launch the Linux shell and execute the following commands to install the necessary `webkit2gtk`:
```bash
sudo apt-get update
```
```bash
sudo apt install libwebkit2gtk-4.1-0
```
Next, execute `DM.EXE-linux_x64` directly from shell:
```bash
./DM.EXE-linux_x64
```


## Screenshots
![DeathLauncher - UI](https://raw.githubusercontent.com/schnalz-digital/deathmanager/refs/heads/main/screenshot1.png)


![DeathLauncher - Adding WADs folder](https://raw.githubusercontent.com/schnalz-digital/deathmanager/refs/heads/main/screenshot2.png)


![DeathLauncher - Choosing a Map](https://raw.githubusercontent.com/schnalz-digital/deathmanager/refs/heads/main/screenshot3.png)
