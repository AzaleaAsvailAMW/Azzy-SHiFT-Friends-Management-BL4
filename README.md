by Azalea Asvail

Azzy SHiFT Management is a Borderlands 4 SHiFT utility mod that adds tools for managing friends, invites, and SHiFT settings more quickly.

Features include:

- Mass remove friends
- Remove offline friends
- Protect specific players from bulk removal
- Add, search, and remove protected players
- Automatically accept, decline, or ignore friend requests
- Automatically accept, decline, or ignore game invites
- Adjustable polling/check interval
- Adjustable removal batch size
- Optional confirmation for bulk removal
- Custom platform/icon styles
- Floating/shrunk SHiFT menu
- Persistent settings through the SDK companion
- Automatic PAK install/update through the SDK mod
- Session-only fallback if the SDK companion is not installed

Azzy SHiFT Management automatically installs or updates the included SHiFT Management PAK for Borderlands 4. When the SDK mod is enabled, it checks for pakchunk90-Windows_90_P.pak. If the PAK is missing, it installs it automatically. If the installed PAK is different from the bundled version, it updates it. If the same version is already installed, it leaves it alone. When a new PAK is installed or updated, a small native in-game message appears telling you to restart Borderlands 4 so the new PAK can load. The SDK also runs the local settings bridge used by the SHiFT menu for persistent settings and protected-player saves. If automatic installation or the bridge does not work, you can use the commands below.

Commands: azzy_shift_install_pak installs or updates the bundled PAK if needed. azzy_shift_force_install_pak forces the bundled PAK to reinstall and overwrite the current one. azzy_shift_pak_status shows whether the bundled PAK and installed PAK were found and displays their hashes. azzy_shift_test_notice tests the native install/update notification without changing the PAK. azzy_shift_storage_status shows whether the local SHiFT settings bridge is running, along with its endpoint and settings file location. azzy_shift_storage_reset resets the saved SHiFT Management settings and protected-player list back to defaults. azzy_shift_bridge_restart restarts the local settings bridge if the SHiFT menu cannot connect or save settings.
