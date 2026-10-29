
# DualPulse DSU

Boot switcher for Android DSU (Dynamic System Updates). Lets you boot into your installed GSI/DSU system using volume keys on startup or via the Magisk Action button.

### Requirements
* Root: Magisk v27.0+ (Magisk only)
* OS: Android 12 – Android 16+
* Setup: Active DSU installation (gsi_tool)

### How it works
1. On Boot: Wait for a short vibration during the boot animation. Press Volume Down (-) within 5 seconds to boot into your DSU Guest OS. Do nothing to boot your primary Host OS.
2. In Magisk: Tap the Action button on the module card to select the next boot target with volume keys and reboot immediately.

### Files
* service.sh — boot key listener and vibration trigger
* action.sh — interactive menu for Magisk Action button
* module.prop — module info
