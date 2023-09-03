## Installing Spicetify with Marketplace and Restoring Configurations

### Prerequisites

- **Operating System**: Windows with PowerShell or PowerShell Core.
- **Software**: Spotify Desktop Application installed.

### Steps

1. ### Installing Spicetify and Marketplace

   - **Open PowerShell as Administrator**:
     - Press `Win` + `S`, type `PowerShell`, right-click on it, and select `Run as administrator`.
   - **Execute the Command to Install Spicetify and the Marketplace**:
     ```powershell
     Invoke-WebRequest -UseBasicParsing "https://raw.githubusercontent.com/spicetify/spicetify-marketplace/main/resources/install.ps1" | Invoke-Expression
     ```
   - Wait for the installation script to complete.

2. ### Applying the Default Spicetify Theme
   (Optional but recommended for first-time users):

   ```powershell
   spicetify apply
   ```

3. ### Importing Your Saved Configurations

   - **Open Spotify**.
   - Download the [Backup File](https://github.com/animegamer4422/Themes-css-UI/blob/main/spotify/spicetify-marketplace)
   - Navigate to `Marketplace`.
   - Go to `Extensions`.
   - Click on `Settings`.
   - In the `Backup/Restore` section, click `Open`.
   - Select `Import from File`.

## Modifying the CSS for Spicetify Themes

After importing your settings, themes, and extensions, you may want to modify the CSS to fit your preferences. Here's how you can apply the modified `Bloom` theme CSS from your GitHub repository.

### Steps:

1. ### Accessing the Theme Dev Tools

   - **Open Spotify**.
   - Navigate to `Marketplace`.
   - Go to `Extensions`.
   - Click on `Theme Dev Tools`.

2. ### Applying Modified CSS

   - Open this link in your browser: [Bloom Modified CSS](https://github.com/animegamer4422/Themes-css-UI/blob/main/spotify/bloom-modified-css).
   - Copy all the contents from the above link.
   - Go back to Spotify's `Theme Dev Tools`.
   - Paste the copied contents into the `color.ini` editor.
   - Save the modifications.

4. ### Verification

   - Restart or open your Spotify Desktop Application.
   - Ensure that your Spicetify theme, extensions, and custom apps (if any) are applied and working as intended.

### Note

Always keep backups of your original configurations and themes. Updates to Spotify or Spicetify can sometimes cause conflicts. If you encounter issues, refer to the Spicetify GitHub repository or its community.
