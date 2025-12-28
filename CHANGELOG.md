# Changelog

## Version 1.3.3.0 - 2025-01-01

### API 14 Update (Dawntrail 7.4)

This version updates EasyEyes to be compatible with Dalamud API Level 14 (FFXIV Patch 7.4).

#### Changes
- **Updated Dalamud API Level**: Upgraded from API 13 to API 14
- **Updated Dalamud.NET.Sdk**: Upgraded from 13.0.0 to 14.1.0
- **ImGui Migration**: Migrated from `Dalamud.Bindings.ImGui` to `ImGuiNET` namespace
- **Version Bump**: Updated assembly version from 1.3.2.0 to 1.3.3.0

#### Files Modified
- `EasyEyes/EasyEyes.json` - Updated DalamudApiLevel and AssemblyVersion
- `EasyEyes/EasyEyes.csproj` - Updated Dalamud.NET.Sdk version
- `EasyEyes/UI/MainInterface.cs` - Updated ImGui imports
- `EasyEyes/UI/VfxTab.cs` - Updated ImGui imports
- `EasyEyes/UI/LogTab.cs` - Updated ImGui imports
- `README.md` - Added version information

#### Compatibility
- **Game Version**: FFXIV Dawntrail 7.4+
- **Dalamud API**: Level 14
- **XIVLauncher**: Required

#### Technical Details
The update aligns EasyEyes with the latest Dalamud API changes, primarily focusing on:
1. ImGui namespace migration (breaking change in API 14)
2. SDK version updates
3. Maintained backward compatibility where possible

All existing functionality remains unchanged. The plugin should work identically to version 1.3.2.0 but with support for the latest game version.
