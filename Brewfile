#############################################################
# ~/.Brewfile - Software Installs for MacOS                 #
#                                                           #
# List of packages to be installed / updated via Homebrew   #
# Apps are sorted by category, and arranged alphabetically  #
# Be sure to delete / comment out anything you do not need  #
# Usage, run: $ brew bundle --global --file $HOME/.Brewfile #
# Source GH repository: https://github.com/adsiddiq/Brewfile #
# See brew docs for more info: https://docs.brew.sh/Manpage #
#                                                           #
# License: MIT © Alicia Sykes 2022 <https://aliciasykes.com>#
#############################################################

# Options
cask_args appdir: '~/Applications', require_sha: true

# Taps (Repositories)
tap 'homebrew/bundle'
tap 'homebrew/core'
tap 'homebrew/services'
tap homebrew/cask-fonts  

#############################################################
# Command Line                                              #
#############################################################

# CLI Essentials
brew 'git'          # Version controll

# CLI Basics
brew 'rsync'        # Fast incremental file transfer

# CLI Monitoring and Performance Apps
brew 'htop'         # Cross-platform interactive process viewer 
brew 'speedtest-cli'# Command line speed test utility

# CLI Productivity Apps
brew 'task'         # Todo + task management

# CLI Fun
brew 'neofetch'     # Show system data and ditstro info

#############################################################
# Software Development                                      #
#############################################################

# Development Apps
cask 'visual-studio-code' # Code editor

# DevOps
brew 'docker'         # Containers

# Development Utils
brew 'gh'             # Interact with GitHub PRs, issues, repos
brew 'git-extras'     # Extra git commands for common tasks
brew 'scrcpy'         # Display and control Android devices
brew 'terminal-notifier' # Trigger Mac notifications from terminal
brew 'tig'            # Text-mode interface for git
brew 'ttygif'         # Generate GIF from terminal commands + output
brew 'watchman'       # Watch for changes and reload dev server

# Network and Security Testing
brew 'bettercap'      # Network, scanning and monitoring
brew 'nmap'           # Port scanning
brew 'wrk'            # HTTP benchmarking
cask 'burp-suite'     # Web security testing
cask 'owasp-zap'      # Web app security scanner
cask 'wireshark'      # Network analyzer + packet capture

# Security Utilities and Data Encryption
brew 'bcrypt'         # Encryption utility, using blowfish
brew 'borgbackup'     # Encrypted, deduplicated backups
brew 'clamav'         # Open source virus scanning suite
brew 'dnscrypt-proxy' # Proxy for using encrypted DNS
cask 'gpg-suite'      # PGP encryption for emails and files
brew 'git-crypt'      # Transparent encryption for git repos
brew 'lynis'          # Scan system for common security issues
brew 'openssl'        # Cryptography and SSL/TLS Toolkit
brew 'rkhunter'       # Search / detect potential root kits
cask 'veracrypt'      # File and volume encryption

#############################################################
# Desktop Applications                                      #
#############################################################

# Creativity
cask 'audacity'     # Audio editor / recorder
cask 'gimp'         # Photo editor
brew 'handbrake'    # Video transcoder
cask 'inkscape'     # Vector editor
cask 'obs'          # Screencasting / recording
cask 'shotcut'      # Video editor

# Media
cask 'calibre'      # E-Book reader
cask 'spotify', args: { require_sha: false } # Propietary music streaming
cask 'transmission' # Torrent client
cask 'vlc'          # Media player
brew 'pandoc'       # Universal file converter
brew 'youtube-dl'   # YouTube video downloader

# Personal Applications
cask '1password'      # Password manager (proprietary)
cask 'tresorit'       # Encrypted file backup (proprietary)
cask 'standard-notes' # Encrypted synced notes
cask 'signal'         # Link to encrypted mobile messenger
cask 'ledger-live'    # Crypto hardware wallet manager
cask 'mountain-duck'  # Mount remote storage locations
cask 'protonmail-bridge' # Decrypt ProtonMail emails
cask 'protonvpn'      # Client app for ProtonVPN
cask 'vorta'          # GUI for BorgBackup

# Browsers
cask 'firefox'
cask 'chromium'
cask 'orion'

#############################################################
# MacOS-Specific Stuff                                      #
#############################################################

# Fonts
tap 'homebrew/cask-fonts'
cask 'font-fira-code'
cask 'font-hack'
cask 'font-inconsolata'
cask 'font-meslo-lg-nerd-font'

# Mac OS Quick-Look Plugins
cask 'qlcolorcode'    # QL for code with highlighting
cask 'qlimagesize'    # QL for size info for images
cask 'qlmarkdown'     # QL for markdown files
cask 'qlprettypatch'  # QL for patch / diff files
cask 'qlstephen'      # QL for dev text files
cask 'qlvideo'        # QL for video formats
cask 'quicklook-csv'  # QL for tables in CSV format
cask 'quicklook-json', args: { require_sha: false } # QL for JSON, with trees
cask 'quicklookapk',   args: { require_sha: false } # QL for Android APKs
cask 'webpquicklook',  args: { require_sha: false } # QL for WebP image files

# Mac OS Utility Apps
cask 'coteditor'      # Just a simple plain-text editor
cask 'the-unarchiver' # File archiver and extractor

