# `node_modules` Cleaner

A Bash script to find and delete all `node_modules` directories within a specified path.

## Features

- **Recursive Search**: The script recursively searches for all `node_modules` directories within the specified directory, excluding nested searches within any `node_modules` folder.
- **Real-Time Updates**: Displays live increments of the count of `node_modules` directories found and their total size in MB.
- **User Confirmation**: Prompts the user to confirm deletion of the found `node_modules` directories before proceeding.
- **Cross-Platform Compatibility**: The script is designed to work on Linux, macOS, and Windows environments.

## Requirements

- **Bash Shell**: This script is written in Bash and requires a Bash shell to execute.

## Running the Script

### On Linux and macOS

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/sharifmrahat/node-modules-cleaner.git
    cd node-modules-cleaner
    ```

2. **Make the Script Executable**:
    ```bash
    chmod +x node_modules_cleaner.sh
    ```

3. **Run the Script**:
    ```bash
    ./node_modules_cleaner.sh "/path/to/your/directory"
    ```

### On Windows

1. **Install Git Bash**:
   - Download and install [Git Bash](https://gitforwindows.org/).

2. **Clone the Repository**:
    ```bash
    git clone https://github.com/sharifmrahat/node-modules-cleaner.git
    cd node-modules-cleaner
    ```

3. **Make the Script Executable** (Optional):
    ```bash
    chmod +x delete_node_modules.sh
    ```

4. **Run the Script**:
    ```bash
    ./node_modules_cleaner.sh "/path/to/your/directory"
    ```

## Contributions

Contributions are welcome! Please feel free to submit a Pull Request.

## Contact

For any issues, questions, or suggestions, please contact <a href="mailto:sharifmrahat@gmail.com">Sharif</a>