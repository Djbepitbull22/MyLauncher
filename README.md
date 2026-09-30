# MyLauncher

A personal, non-commercial launcher for Minecraft: Java Edition, built with .NET 8 (WPF) for Windows.

## Features
- Installs and launches vanilla Minecraft versions (Fabric profiles planned)
- Sign-in with Microsoft account for players who own Java Edition

## Account security
- Sign-in uses only Microsoft's official OAuth device-code flow (microsoft.com/link); the launcher never sees passwords
- Tokens are stored only on the user's PC, encrypted with Windows DPAPI
- Tokens are sent only to Microsoft, Xbox Live and Minecraft Services endpoints
- No offline/cracked account support, no monetization

Source code is currently private. Contact: djgamerkid17@gmail.com
