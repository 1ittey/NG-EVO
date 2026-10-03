![NG-EVO](assets/cover.png)

# Installation

NG-EVO uses **Wabbajack** to automate the installation of the modlist. Before beginning, make sure your system meets the requirements below and that Enderal: Forgotten Stories Special Edition is correctly installed through Steam.

> **Important:** NG-EVO is a large visual overhaul. Installation can take considerable time depending on your internet connection, storage speed, and whether you use Nexus Premium.

---

## System Requirements

### Recommended Hardware

The following configuration represents the hardware used for NG-EVO testing:

| Component | Recommended |
|---|---|
| CPU | AMD Ryzen 5 3600 |
| GPU | NVIDIA GeForce RTX 3060 |
| VRAM | 12 GB |
| RAM | 16 GB |
| Pagefile | 40 GB |

NG-EVO is primarily a visual overhaul, so performance will depend on your GPU, CPU, resolution, graphics settings, and the areas of Enderal being rendered.

Systems below these specifications may still be able to run NG-EVO, but performance may vary.

### Storage

You will need sufficient free space for:

- Your Enderal: Forgotten Stories Special Edition installation
- Wabbajack's downloaded archives
- The completed NG-EVO installation

## 💾 Storage Requirements

NG-EVO requires a significant amount of free storage during installation.

| Requirement | Size |
|---|---:|
| Wabbajack Download Folder | **~135 GB** |
| Installed NG-EVO | **~196 GB** |
| Maximum Space Required During Installation | **~331 GB** |

The **~331 GB** figure represents the combined space required for the Wabbajack download files and the installed NG-EVO modlist.

After the installation has completed successfully, the **Wabbajack download folder can be safely deleted** to free approximately **135 GB** of storage.

This leaves the installed NG-EVO modlist using approximately **196 GB** of storage.

> **Recommended:** Make sure you have at least **331 GB of free space** available before beginning the installation.

An **SSD is strongly recommended** for NG-EVO. Installing the modlist on an SSD will provide faster installation and loading times.

We recommend keeping your Wabbajack download folder separate from your NG-EVO installation folder. The download folder can be reused for future Wabbajack installations.

---

## Prerequisites

Before installing NG-EVO, make sure the following Windows components are installed.

### Microsoft Visual C++ Redistributable

Install the latest supported **Microsoft Visual C++ Redistributable** from Microsoft.

[Download Microsoft Visual C++ Redistributable](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist)

For a typical 64-bit Windows installation, install the **x64** package.

### .NET Framework 4.8

Install **.NET Framework 4.8**.

[Download .NET Framework 4.8](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net48)

### .NET Desktop Runtime 8.0.31

Install **.NET 8.0 Desktop Runtime — version 8.0.31**.

[Download .NET 8.0](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)

For a standard 64-bit Windows installation, use the **Windows x64 Desktop Runtime**.

### Pagefile

NG-EVO requires a **40 GB pagefile**.

If Windows is currently using a smaller pagefile or virtual memory is disabled, configure a pagefile with a size of **40 GB** before installing NG-EVO.

We recommend placing the pagefile on an SSD with sufficient free space.

---

## 1. Install Enderal: Forgotten Stories Special Edition

NG-EVO requires the **Steam version of Enderal: Forgotten Stories Special Edition**.

Install Enderal through Steam before beginning the Wabbajack installation.

### Avoid Windows Protected Folders

We strongly recommend keeping Enderal and your NG-EVO installation outside Windows-protected directories such as `C:\Program Files\` and `C:\Program Files (x86)\`.

A separate Steam library or game directory is recommended.

For example:

`D:\SteamLibrary\`

or:

`D:\Games\`

This helps prevent Windows permission and file-access issues with modding tools.

### Launch Enderal Once

After installing Enderal:

1. Launch Enderal through Steam.
2. Allow the initial setup to complete.
3. Reach the main menu.
4. Exit the game.

If you have previously modified your Enderal installation, verify the game files through Steam before beginning the NG-EVO installation.

---

## 2. Install Wabbajack

Download the latest version of Wabbajack from the official website.

[Download Wabbajack](https://www.wabbajack.org/)

Create a dedicated folder for Wabbajack itself.

For example:

`D:\Wabbajack\`

Avoid placing Wabbajack inside your Desktop, Downloads, or Program Files folders.

---

## 3. Prepare Your Wabbajack Folders

Keep your Wabbajack downloads and NG-EVO installation in separate folders.

For example:

`D:\WJDownloads\`

`D:\NG-EVO\`

### Download Location

Set Wabbajack's **Download Location** to:

`D:\WJDownloads\`

This folder stores the downloaded mod archives and can be reused for future Wabbajack installations.

### Installation Location

Set Wabbajack's **Installation Location** to:

`D:\NG-EVO\`

Use a dedicated folder for the NG-EVO installation.

> **Do not install NG-EVO inside your Enderal Steam directory.**

---

## 4. Log in to Nexus Mods

Open Wabbajack and log in to your **Nexus Mods** account.

A **Nexus Premium** membership is recommended because it allows Wabbajack to automate Nexus downloads. Without Premium, you may need to manually interact with Nexus download prompts during installation.

---

## 5. Install NG-EVO

Once NG-EVO is officially available through Wabbajack:

1. Open Wabbajack.
2. Select **Browse Lists**.
3. Find **NG-EVO — Next Generation Enderal Visual Overhaul**.
4. Select **Install**.
5. Choose your dedicated NG-EVO installation folder.
6. Choose your Wabbajack download folder.
7. Start the installation.
8. Allow Wabbajack to download and install the required files.

The installation may take some time depending on your hardware, storage, internet connection, and Nexus download speed.

> **Do not close Wabbajack while the installation is in progress.**

If Wabbajack reports a failed download, try running the installation again using the same folders before beginning troubleshooting.

---

## 6. First Launch

After Wabbajack reports that the installation has completed successfully:

1. Open your NG-EVO installation folder.
2. Launch **Mod Organizer 2** using the executable provided with the installation.
3. Make sure the NG-EVO profile is selected.
4. Do not add or remove mods before your first launch.
5. Launch Enderal through the configured MO2 executable.
6. Allow the game to reach the main menu.

> **Important:** NG-EVO has been built and tested around a specific configuration. Adding, removing, or changing mods can introduce compatibility problems and make troubleshooting more difficult.

---

## 7. Before Starting Your Playthrough

After successfully reaching the main menu:

- Confirm that your display resolution is correct.
- Confirm that your graphics settings are appropriate for your hardware.
- Make sure the NG-EVO visual components have loaded correctly.
- Start a new game unless the current NG-EVO release notes explicitly state that existing saves are compatible.

NG-EVO is a **visual overhaul**. Gameplay systems, quests, progression, and combat remain outside the project's scope.

---

## Updating NG-EVO

When a new NG-EVO version is released, **read the changelog before updating**.

Some updates may require a fresh installation or may contain specific instructions regarding save compatibility.

When updating through Wabbajack:

1. Read the NG-EVO changelog.
2. Back up your saves if required.
3. Install the new NG-EVO version through Wabbajack.
4. Use the same installation and download locations where possible.
5. Allow Wabbajack to complete the update.
6. Follow any additional instructions provided with the release.

> **Important:** Wabbajack manages the contents of the modlist installation. Files manually added to the installation may be overwritten or removed during an update.

---

## Troubleshooting

### Wabbajack Installation Failed

First, try running the installation again using the same installation and download locations.

Temporary network or download issues can cause individual files to fail.

### Insufficient Storage

Make sure both your **download drive** and **installation drive** have sufficient free space.

Remember that Wabbajack downloads and the completed installation require separate storage.

### Windows Security Software

Antivirus or other security software can sometimes interfere with Wabbajack, Mod Organizer 2, or other modding tools.

If a program is being blocked, check your security software and create an appropriate exception rather than disabling system protection unnecessarily.

### Wabbajack Logs

If the problem persists, locate the Wabbajack log and provide it when requesting support.

For NG-EVO support, join the **[NG-EVO Discord](https://discord.gg/VqYdkDz44)** and provide the relevant Wabbajack log together with a description of the problem.

---

## Important Notes

**Do not manually modify the NG-EVO installation before completing your first successful launch.**

If you want to customize NG-EVO after installation, check the documentation and compatibility information first. Removing or replacing components can cause conflicts with the configured visual setup.

For support, provide as much relevant information as possible, including:

- NG-EVO version
- Windows version
- Hardware specifications
- Wabbajack log
- Crash log, if applicable
- A description of what happened immediately before the problem occurred

---

## Support

For questions, troubleshooting, and community support, join the **[NG-EVO Discord](https://discord.gg/VqYdkDz44)**.

You can also find the NG-EVO project, changelog, resources, and mod list through the links provided on the main repository.
