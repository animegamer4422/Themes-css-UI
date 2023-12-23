# Guide to Theming Firefox Using Chrome Resources

## Prerequisites

- Ensure Firefox is installed and has no other themes in the Chrome folder to avoid conflicts.
- Prepare to use the Chrome folder available in this current Git repository, which contains the necessary theming resources.

## Steps to Apply the Theme

### 1. Enable Legacy User Profile Customizations

- Open Firefox and type `about:config` in the URL bar to access advanced settings.
- Search for `toolkit.legacyUserProfileCustomizations.stylesheets` in the `about:config` page.
- Double-click on it to toggle its value to `True`. This enables Firefox to use custom stylesheets, essential for applying your theme.

### 2. Locate Your Firefox Profile Folder

- Type `about:support` in the Firefox URL bar to open the Troubleshooting Information page.
- Find the `Profile Folder` section and click `Open Folder` to navigate to your Firefox profile's storage location.

### 3. Import Chrome Resources from the Current Repository

- Within this repository, locate the Firefox folder that contains the Chrome theming resources.
- Copy the entire Chrome folder found here.
- Paste the Chrome folder into your Firefox profile directory, ensuring all contents are correctly transferred.

### 4. Activate Your New Theme

- Restart Firefox to apply the new theme.
- Firefox should now display the custom theme set using the Chrome resources from this repository.

## Additional Tips

- **Customization**: You may need to make specific adjustments based on the contents of the Chrome folder for optimal theming results.
- **Backup**: Consider backing up your original Firefox profile folder before proceeding with these steps.
- **Troubleshooting**: If the theme doesn't appear correctly, ensure `toolkit.legacyUserProfileCustomizations.stylesheets` is set to `True` and that the Chrome folder is correctly placed in your profile directory.