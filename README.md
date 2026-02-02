# Discord-RPC with Buttons (Prebuilt Win32)
This repository provides a prebuilt version of the discord-rpc library, specifically modified to support Rich Presence Buttons. It is designed for developers who want to implement buttons without the hassle of manual CMake compilation.

Features:
1. Button Support: Includes button1_label, button1_url, button2_label, and button2_url within the DiscordRichPresence struct.
2. Win32 Architecture: Prebuilt for 32-bit applications (perfect for GTA:SA/SAMP modding).
3. Static CRT: Compiled with USE_STATIC_CRT to ensure compatibility without requiring extra Visual C++ Redistributables on the user's end.

# Repository Structure:
1. include/: Contains discord_rpc.h with modified struct definitions.
2. lib/x86/: Contains the static library discord-rpc.lib for linking.

# How to Use:
1. Include: Add the include folder to your project's include directories.

2. Link: Link discord-rpc.lib in your project's linker settings.

3. Deploy: Ensure discord-rpc.dll is placed in the same directory as your application or game executable.

Implementation: Make sure to provide a valid URL (starting with https://) for the buttons to show up correctly.
