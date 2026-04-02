# Riverfield
Just a GNOME setup guide for Fedora! (because I'll probably need it later)

<img width="1871" height="887" alt="fedora setup2" src="https://github.com/user-attachments/assets/af0568ea-b221-4047-bd69-f6dafe703817" />


# Table of Contents
  bullet points
  1. Introduction
  2. Preview
  3. Appearance


# Appearance
Installation using package manager:

Fedora:
      
      sudo dnf install yaru-theme

Manual Installation:

    git clone https://github.com/ubuntu/yaru.git
    mkdir -p ~/.themes ~/.icons
    cd yaru
    cp -r themes/Yaru* ~/.themes/
    cp -r icons/Yaru* ~/.icons/
    
  To download GNOME tweaks:
  Note: This tool enables advanced customization, including theme changes, font adjustments, and window management settings.  
      Option 1 via command line:
      
      sudo dnf install gnome-tweaks
      
  Via GNOME Software:
      
      Open the Software application.
      Click the search icon and type GNOME Tweaks.
      Click Install
    
  To download Extension manager:
  Option 1 Via Software Center (GUI):
    
    Open the Software app (GNOME Software) on your Fedora workstation.
    Search for Extension Manager.
    Click Install.

  Option 2 Via Terminal (Flatpak):

    flatpak install flathub com.mattjakeman.ExtensionManager

  How to Use:
1.Launch "Extension Manager" from your applications menu.
2.Use the Browse tab to search for extensions.
3.Click Install to add new extensions.
4.Manage installed extensions in the Installed tab. 

 To download clock widget:
 1. Open Extension manager
 2. Go to "Explore" and search for "clock widgets"
 3. Download

To download the audio visualizer(cava):
    
    dnf install cava
    
  To download the neofetch/fastfetch:
  Neofetch is no longer available in the official Fedora repositories as of late 2024.

  To install the modern alternative, run the following command in your terminal: (fedora 41+)

    sudo dnf install fastfetch
