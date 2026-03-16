## 📦 OAuth2Client - Seamless OAuth2 Integration for Velocity and Paper

**OAuth2Client** is a lightweight, modern plugin that provides seamless, real-time integration between your Velocity Minecraft server and your OIDC provider.

With OAuth2Client, players can securely link their Minecraft accounts with your OIDC provider using OAuth2 — no need to manually enter codes.

---

### ✨ Key Features

- 🔗 **Account Linking via OAuth2**
  Players can easily and securely link their accounts through a simple OIDC authorization flow — no code entry required.

- ⚙️ **Highly Configurable**
  Easily adjust settings and customize the integration to fit your server's needs.

- 🚀 **Optimized for Performance**
  Designed specifically for Velocity to ensure minimal resource usage and fast response times.

- 🧩 **PlaceholderAPI Support (only on Paper)**
  Feel free to use placeholders from PlaceholderAPI. OAuth2Client itself provides placeholders for OIDC provider account name and id.

- 🤖 **Event based commands**
  You can define your own commands when someone links / unlinks their account. You can also use placeholders.

---

### 🔧 Requirements

- Velocity or Paper Server
- [LuckPerms](https://modrinth.com/plugin/luckperms) plugin on your server
- Java 17 or newer
- MySQL or MariaDB database
- Open port for web server
- An OIDC provider that supports OAuth2

---

### 🚀 Installation

1. Download the latest release JAR from the [releases page](../../releases).
2. Place the JAR file into your Velocity server's `plugins/` folder.
3. Start (or restart) your server once to generate the default configuration file.
4. Stop the server, then edit the generated `plugins/OAuth2Client/config.json` file (see [Configuration](#%EF%B8%8F-configuration) below).
5. Start the server again. The plugin is now active.

> **Note:** Make sure the web server port you configure is open and reachable from the internet, as players will be redirected to it during the OAuth2 flow.

---

### 🎮 Usage (for players)

Once the plugin is installed and configured, players can link their accounts using the following in-game command:

