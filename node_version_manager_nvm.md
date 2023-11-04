# Node Version Manager (NVM)

![NVM Logo](https://github.com/coreybutler/nvm-windows/raw/master/app/nvm_logo.png)

Node Version Manager (NVM) is a powerful tool that allows you to manage multiple Node.js versions on your Windows system. Whether you're a developer working on various projects with different Node.js requirements or simply want to stay up-to-date with the latest Node.js releases, NVM for Windows is a handy solution.

## Getting Started

To begin using NVM for Windows, follow these steps:

1. **Installation:**

   - Visit the [NVM for Windows GitHub repository](https://github.com/coreybutler/nvm-windows) to download the latest release.
   - Download and run `nvm-setup.exe` to install NVM on your system.

2. **Verify Installation:**

   To check if NVM is correctly installed, open your command prompt or terminal and enter the following command:

   ```bash
   nvm --version
   ```

   This should display the version of NVM, confirming the installation was successful.

3. **Debugging:**

   If you encounter any issues or need to troubleshoot NVM, you can use the `debug` command:

   ```bash
   nvm debug
   ```

## Managing Node Versions

With NVM, you can easily manage Node.js versions:

- **Install Node.js:**

  To install a specific Node.js version, use the `install` command. Replace `node_version` with the desired Node.js version number (e.g., `14.17.4`):

  ```bash
  nvm install node_version
  ```

- **List Installed Versions:**

  To see the Node.js versions you've installed, run the following command:

  ```bash
  nvm list
  ```

- **Use a Specific Version:**

  To set a specific Node.js version as the active one, use the `use` command. Replace `node_version` with the version you want to use:

  ```bash
  nvm use node_version
  ```

Now, let's dive into some additional information about NVM:

## Additional Information

1. **Default Version:**

   NVM allows you to set a default Node.js version by using the `nvm alias default` command, ensuring that your preferred version is automatically selected when opening a new terminal.

2. **Global Packages:**

   When you change your active Node.js version, keep in mind that globally installed packages are tied to a specific Node.js version. You may need to reinstall global packages after switching versions.

3. **Upgrading NVM:**

   To update NVM to the latest version, you can use the Windows Installer (nvm-setup.exe) or visit the [NVM for Windows GitHub releases page](https://github.com/coreybutler/nvm-windows/releases) to download the most recent version.

NVM for Windows simplifies the process of managing Node.js versions, making it an invaluable tool for developers who work on projects with varying requirements or want to stay current with the Node.js ecosystem. Explore its features, and enhance your Node.js development experience.