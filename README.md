# PowerTools for PowerShell

## Introduction
Welcome to PowerTools, a comprehensive collection of custom commands designed to enhance your PowerShell experience. PowerTools simplifies various tasks, ranging from file and directory management to system utilities, making your PowerShell interface more powerful and user-friendly.

## Features
PowerTools includes a variety of custom commands, organized into intuitive categories:

### File and Directory Traversal Search Utility
- **SniffSearch (ss)**: Search directories and files with customizable depth and filters.
- **CreateDirectoryIfNotExists (cdd)**: Create a directory if it doesn't exist, with confirmation.

### Custom Command Utilities
- **ShowCommandList (lcc)**: List or search custom commands.
- **SearchCustomCommand (scc)**: Search for a specific custom command.

### Conda Environment Management
- **CondaCreateEnv (cce)**: Create a new Conda environment with optional Python version.
- **CondaUpdateEnv (cue)**: Update packages in a Conda environment.
- **CondaRemoveEnv (cre)**: Delete a specified Conda environment.
- **CondaListShortcuts (ccon)**: List or search Conda shortcuts.

### Network and System Utilities
- **ListConnectedIPs (lci)**: List all connected IP addresses.
- **LaunchAdminPS (psadmin)**: Open PowerShell as Administrator.
- **LaunchDebloater (debloat)**: Launch a PowerShell debloater script.

### Profile and Environment Customization
- **EditProfileInNP (epin)**: Edit profile commands in Notepad++.
- **ReloadThisProfile (reload)**: Reload the profile.ps1 without restarting PowerShell.
- **ReStylePrompt (rsp)**: Customize the PowerShell prompt.

### General Aliases
Includes shortcuts for common tasks like updating Conda, activating environments, listing files, and more.

## Installation
To install PowerTools, download the `Microsoft.PowerShell_profile.ps1` file and place it in your PowerShell profile directory. Ensure that you backup your existing PowerShell profile before proceeding.

## Usage
To use a command, simply type the command or its alias in the PowerShell prompt, followed by any necessary arguments or options. For example:
```powershell
SniffSearch -firstParam 2 -secondParam "*.txt"
```

## Important Note
Before using any commands, it's crucial to understand their functionality and arguments to avoid unintended actions. Always refer to the most recent version of the PowerTools documentation for accurate information.

## Contributing
Contributions to PowerTools are welcome! If you have ideas for new features or improvements, feel free to submit a pull request or open an issue.
