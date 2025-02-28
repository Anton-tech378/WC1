## Опишіть набір базових дій в встановленому Вами гіпервізорі
### Створення нової віртуальної машини;
1. Click *"Create"* in the tool window.
2. Enter the name of the virtual machine.
3. Select the type and version of the OS to be installed. In our case, it is Linux with GNOME GUI.
4. Specify the amount of RAM that will be allocated for the virtual machine *(at least 2 GB is recommended)*. To make the virtual machine not too heavy, it is better to allocate 50% of the memory that is available on the main PC.
1. Specify the hard disk parameters and select the file type of the virtual disk of the machine. In *"Expert mode"* you can find more hard disk settings if necessary.
2. Select the storage format *(in our case it is "dynamic")*.
3. Click *"Create"*.

### Вибір/додавання доступного для віртуальної машини обладнання;
In the settings window, you can change the settings in the *"System"*, *"Media"*, *"Network"* and *"USB"* sections. For example, to add an optical drive, go to *"Media"*, click the add device icon, select 
*"Add optical drive"* and specify an ISO file or a physical drive. In the *"Network"* section, you can enable the adapter and select the connection type *(NAT or network bridge)*. After saving the changes, click *"OK"* and start the virtual machine.

### Налаштування мережі та підключення до точок Wi-Fi;
First, you need to open the virtual machine settings and go to the "Network" section, where you need to activate the adapter. In the "Connected to" field, you need to select the appropriate network mode. Most often, for simple access to the Internet, NAT mode is used, which allows the guest operating system to use the host connection without additional settings. In this case, in the "Name" field, you need to select the Wi-Fi adapter of the host computer *(for example, "Wi-Fi" or "wlan0")*. After saving the changes, first, to check the operability, start the virtual machine and check the Internet connection using the ping command in the command line terminal.

### Можливість роботи з зовнішніми носіями (flash-пам’ять);
First, download and install the latest version of the *VirtualBox Extension Pack*. This will add support for *USB 2.0* and *3.0*. 
Then you need to restart the system for the changes to take effect. After restarting VirtualBox, click *"Settings"* - *"USB"*. Enable the *USB 2.0 or 3.0* controller, add a new USB filter so that VirtualBox automatically connects the device to the virtual machine. In the *"Devices"* menu, select "USB" and click on the desired flash drive to connect it to the virtual machine.

## Практична частина

![alt text](https://cdn.discordapp.com/attachments/1317092536866570261/1344980742148718693/IMG_2253.jpg?ex=67c2e26d&is=67c190ed&hm=a6d87095f9c384487224373e2d6678eceb8440d26658d98fdc844b6993a02aa6&)

![alt text](https://cdn.discordapp.com/attachments/1317092536866570261/1344980743272796221/IMG_2254.jpg?ex=67c2e26d&is=67c190ed&hm=9ad2edceca41e48563cdfaf359d65e520abf36a19e142790bdf12e2e33328354&)

![alt text](https://cdn.discordapp.com/attachments/1317092536866570261/1344980744422031360/IMG_2255.jpg?ex=67c2e26e&is=67c190ee&hm=9975153ebf4fbbfb4a143f945ad555d8b0c4344492f23a9714bd7dbf257e3392&)

![alt text](https://cdn.discordapp.com/attachments/1317092536866570261/1344980750944047145/IMG_2256.jpg?ex=67c2e26f&is=67c190ef&hm=c8a68a950e7c231ba47292c19a6d8d5e08a7d1dc76df4c5f640e747b754d83ba&)

![alt text](https://cdn.discordapp.com/attachments/1317092536866570261/1344980752290414622/IMG_2257.jpg?ex=67c2e26f&is=67c190ef&hm=b14098a25b7e0c825e34702fcd244c985251ee0b4efdbce0836cf5c1cec2f2ed&)

![alt text](https://cdn.discordapp.com/attachments/1317092536866570261/1344980753490116731/IMG_2258.jpg?ex=67c2e270&is=67c190f0&hm=ee29344ec9c80676348796cac68ce03b5e667096edf71212cbe51c4e766ebc46&)

![alt text](https://cdn.discordapp.com/attachments/1317092536866570261/1344980754672783390/IMG_2259.jpg?ex=67c2e270&is=67c190f0&hm=990df883781af0352678562ebcdf8b10db97395b1ed5a365c2523cbdfa3ea947&)

![alt text](https://cdn.discordapp.com/attachments/1317092536866570261/1344980755947720774/IMG_2260.jpg?ex=67c2e270&is=67c190f0&hm=c8a20a8ef39ddfdb0700bec7484ffdb50ad90182b1554ef3a563a5156597b135&)

![alt text](https://cdn.discordapp.com/attachments/1317092536866570261/1344980757185302608/IMG_2261.jpg?ex=67c2e271&is=67c190f1&hm=a7026ecc06d422dca21e141244886b3b6571d5e5cce0c50dd91209f0f04b0d5b&)

![alt text](https://cdn.discordapp.com/attachments/1317092536866570261/1344980758133084191/camphoto_684387517.jpg?ex=67c2e271&is=67c190f1&hm=86137509718b22f969909c8ef26562130ead6cb455d7112396a76fdffbcc5133&)

![alt text](https://cdn.discordapp.com/attachments/1317092536866570261/1344983134348775424/IMG_2264.jpg?ex=67c2e4a7&is=67c19327&hm=9d581d4f1e0167e45eb7b9795247949c009f63912a01300d800359e70eb615e3&)

## Порівняння Xfce з Gnome

### Загальні відомості

**Xfce** - is a lightweight desktop environment for UNIX-based operating systems. Xfce aims to be fast and light on system resources, while remaining visually appealing and easy to use.
- Initial Release: 1996  
- Key Principle: A classic desktop with panels, menus, and minimal effects  
- Architecture: Built on GTK+ (version 2, later 3, partially supports GTK4)  
- Default Look: Similar to Windows 95/XP, with a classic menu and taskbar  
- Components:  
  - xfwm – Built-in window manager  
  - Thunar – Lightweight file manager  
  - Xfce Panel – Customizable panel for menus, tray icons, and window switching  
  - Xfce Settings – Set of configuration utilities
     
**Gnome** - focuses on creating a completely free environment accessible to all users regardless of technical skill level, physical limitations, or language. Within GNOME, both native applications for end users are developed, as well as a set of tools for creating new applications that integrate tightly with the desktop environment.
- Initial Release: 1999  
- Key Principle: Minimalist design with a focus on simplicity and gesture-based interaction  
- Architecture: GTK4, full Wayland support  
- Default Look: No traditional menu, replaced by "Activities Overview"  
- Components:  
  - Mutter – Window manager  
  - Nautilus – File manager  
  - GNOME Shell – Main shell with gesture navigation  
  - GNOME Control Center – Centralized settings panel

### Основні відмінності

| Feature            | Xfce                        | GNOME                      |
|--------------------|----------------------------|----------------------------|
| **Resource Usage** | 200-500MB RAM, low CPU load | 600+MB RAM, higher CPU usage |
| **Speed**         | Fast, works well on older PCs | Moderate, requires modern hardware |
| **Simplicity**    | Classic, familiar interface | Minimalist, takes time to adapt |
| **Customization** | High, can tweak panels, buttons | Lower, requires extensions |
| **Functionality** | Basic but extendable | Wide application ecosystem |
| **Wayland Support** | No support | Full support |
| **Stability**     | Very stable, rare breaking updates | Some changes may break compatibility |
| **Best For**      | Older PCs, users who prefer a classic style | New devices, users who prefer modern aesthetics |

## Плюси та мінуси

### Xfce
**Pros:**
Lightweight, fast, perfect for low-end machines  
Classic, convenient interface without unnecessary effects  
Flexible customization of panels, menus, and hotkeys  

**Cons:**
Fewer visual effects, outdated look  
Slow development cycle, rare updates  
No Wayland suppor

### GNOME
**Pros:**
Modern, minimalist design  
Supports gestures, Wayland, and new technologies  
Rich ecosystem of integrated applications    

**Cons:**
High resource usage  
Limited out-of-the-box customization without extensions  
