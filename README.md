# Minecraft Bedrock Server for Coolify

Simple Minecraft Bedrock Dedicated Server deployment for Coolify.

## 🚀 Deploy to Coolify

1. **Create new Application** in Coolify
2. **Repository**: `https://github.com/AltFl0w/OnlineZooCopy.git`
3. **Branch**: `master`
4. **Build Pack**: Docker Compose
5. **Exposed Port**: `19133` (UDP)

## 📋 Server Settings

- **Port**: 19133 (UDP)
- **Game Mode**: Creative
- **Difficulty**: Easy
- **Cheats**: Enabled
- **Max Players**: 10

## 🎮 Connect to Server

**Server Address**: `your-server-ip:19133`

Use Minecraft Bedrock Edition (Mobile, Console, Windows 10)

## 🌍 Upload Your Zoo World

After the server is running:

1. Stop the server in Coolify
2. Access container file system
3. Replace world files in `/bedrock/worlds/`
4. Restart server

Your zoo world files are in the original repository's `worlds/` directory. 