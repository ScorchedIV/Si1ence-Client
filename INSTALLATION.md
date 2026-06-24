# Si1ence Client - Installation Guide

## Quick Start

1. **Download** the latest `Si1ence_Client_Offline_WASM.html` file from the [releases page](https://github.com/ScorchedIV/Si1ence-Client/releases)
2. **Open** the HTML file in your web browser
3. **Play** on any Eaglercraft 1.12 compatible server

## Browser Requirements

- **Chrome 57+** (Recommended)
- **Firefox 52+**
- **Edge 79+**
- **Safari 11+** (with WebAssembly support)

## Operating System Support

- ✅ Windows
- ✅ macOS
- ✅ Linux
- ✅ Android (Chrome Mobile)
- ✅ iOS (Mobile Safari)

## First Run

When you first open Si1ence Client:

1. The client will load the WASM module
2. Game assets will be cached in your browser
3. You may see a loading screen - this is normal
4. Once loaded, you'll see the main menu

## Launching the Game

1. Click **"Play"** on the main menu
2. Enter server details (IP address and port)
3. Enter your username
4. Click **"Join Server"**

## Using Modules

1. Press the **ClickGUI key** (default varies by module)
2. Browse available modules
3. Toggle modules on/off
4. Adjust module settings
5. Changes are automatically saved

## Game Controls

Standard Minecraft 1.12 controls:
- **WASD** - Movement
- **Space** - Jump
- **Shift** - Crouch/Sneak
- **Mouse** - Look around / Click
- **E** - Open inventory
- **Tab** - Player list
- **ESC** - Menu/Pause

## Troubleshooting

### Client Won't Load

**Problem**: Page stays blank or shows error

**Solutions**:
1. Refresh the page (Ctrl+F5 or Cmd+Shift+R)
2. Clear browser cache
3. Try a different browser
4. Check browser console for errors (F12)

### Connection Issues

**Problem**: Can't connect to servers

**Solutions**:
1. Check server address is correct
2. Verify the server is Eaglercraft compatible
3. Try a different relay server
4. Check your internet connection

### Low FPS / Performance Issues

**Solutions**:
1. Lower render distance in Video Settings
2. Disable unnecessary modules
3. Close other browser tabs
4. Update your GPU drivers
5. Try disabling ViaBlocks-heavy modules

### Module Won't Enable

**Solutions**:
1. Check if the module requires a specific server type
2. Verify you're on an Eaglercraft 1.12 server
3. Restart the client
4. Check browser console for errors

## Offline Usage

Si1ence Client is designed to work **offline**:

1. Open the HTML file once while online
2. Assets cache in your browser
3. You can use it offline (single-player worlds only)
4. Online multiplayer requires internet connection

## Saving and Worlds

- Worlds are stored in browser **IndexedDB**
- Clearing browser cache will **delete all worlds**
- Export worlds before clearing cache
- Use multiple browsers to have separate world sets

## Advanced: Hosting as a Website

To host Si1ence Client on your own server:

1. Upload `Si1ence_Client_Offline_WASM.html` to your web server
2. Ensure proper MIME types are set for `.html` files
3. No special server configuration needed
4. Users access via your domain

## FAQs

**Q: Is it safe to play?**
A: Yes! The client is open-source and the code can be inspected.

**Q: Will I get banned?**
A: Depends on the server. Most Eaglercraft servers allow Eaglercraft clients.

**Q: Can I use mods?**
A: Not traditional mods, but Si1ence Client includes built-in modules similar to client mods.

**Q: Do I need Java?**
A: No! Si1ence Client is 100% web-based and runs in your browser.

**Q: Can I play with friends?**
A: Yes! Connect to the same server with the server IP and port.

---

**Need more help?** Check the original repositories:
- [Tuff Client Support](https://github.com/TuffNetwork/Tuff-Client-Builds/issues)
- [Galactic Client Support](https://github.com/GalacticClient/Galactic-Client/issues)