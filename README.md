# Python-Cleaner
Mac Cleanup Removal Script
This Bash script is a comprehensive system cleanup tool designed for macOS. It clears system caches, logs, and unnecessary files from a wide variety of applications, helping you free up space and keep your system optimized. The script supports a dry-run mode, verbose output, and color-coded messages to make the cleaning process more transparent.

Features
System Cleanup: Removes caches, logs, and temporary files from various locations on macOS, including user directories, application caches, and system-level directories.
Application Support: Targets cache and log files from popular applications such as:
Adobe Creative Cloud
Google Chrome
XCode
Docker
Homebrew
npm, yarn, and pnpm
Microsoft Teams
Minecraft, Lunar Client, Steam
JetBrains IDEs
iOS Backup Cleanup: Cleans up iOS backups stored on your machine.
Simulated Cleanup (Dry Run): Estimate how much space can be freed without actually deleting files.
Brew Integration: Optionally updates and cleans up outdated Homebrew packages and caches.
Memory and DNS Cache Purge: Optionally purges inactive memory and flushes the DNS cache for performance improvements.
Logging and Verbose Output: Includes an option for verbose output and detailed logging of actions.

-h, --help: Show help message and exit.
-v, --verbose: Print detailed script debug information.
-d, --dry-run: Simulate the cleanup process, showing what would be deleted.
-u, --update: Run brew update to update Homebrew recipes.

To run a basic cleanup: sudo ./mac-cleanup.sh

To perform a dry-run and see how much space will be freed: sudo ./mac-cleanup.sh --dry-run

