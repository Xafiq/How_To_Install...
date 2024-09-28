# How to Install NVM 🛠️

**Requirements:**
- Windows or Linux (Debian) operating system.
- Internet access.

### On Windows

- **Download NVM:**
  - Go to the [NVM for Windows page](https://github.com/coreybutler/nvm-windows/releases) and download the latest `nvm-setup.zip` or directly the `nvm-setup.exe`.

- **Install NVM:**
  - Run `nvm-setup.exe` as an administrator and follow the instructions.

- **Verify Installation:**
  - Open Command Prompt and run:
    ```bash
    nvm --version
    ```

### On Linux (Debian)

- **Download and Install NVM:**
  - Run this command in the terminal:
    ```bash
    curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash
    ```

- **Activate NVM:**
  - Add this to your `~/.bashrc`:
    ```bash
    export NVM_DIR="$HOME/.nvm"
    [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
    ```

- **Apply Changes:**
  - Run:
    ```bash
    source ~/.bashrc
    ```

- **Verify Installation:**
  ```bash
  nvm --version
