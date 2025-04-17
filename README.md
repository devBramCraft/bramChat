# BramChat

BramChat is a custom Minecraft plugin for Bukkit/Spigot servers that enhances chat functionality with features like private messaging, reply commands, ignoring players, and more.

## Features

- **Custom Chat Formatting**: Supports placeholders like `%luckperms_prefix%` and `%player%`.
- **Private Messaging**: Send private messages to other players using `/msg` and `/r`.
- **Ignore Players**: Ignore messages from specific players using `/ignore`.
- **Toggle Private Messages**: Enable or disable private messages with `/togglepm`.
- **Anti-Spam**: Prevent players from spamming the chat with a configurable cooldown.
- **Bad Word Filter**: Block inappropriate words from being used in chat.
- **Reload Configuration**: Reload the plugin configuration with `/bramchatreload`.

## Commands

| Command            | Description                              | Permission            |
|--------------------|------------------------------------------|-----------------------|
| `/bramchatreload`  | Reloads the plugin configuration.        | `bramchat.reload`     |
| `/msg <player> <message>` | Sends a private message to a player. | None                  |
| `/r <message>`     | Replies to the last private message.     | None                  |
| `/ignore <player>` | Ignores messages from a specific player. | None                  |
| `/togglepm`        | Toggles private messages on or off.      | None                  |

## Configuration

The plugin's configuration file is located at `src/main/resources/config.yml`. Below are some key settings:

- **Chat Settings**:
    - `chat.enable`: Enable or disable chat globally.
    - `chat.anti-spam`: Enable or disable anti-spam.
    - `chat.cooldown-seconds`: Set the cooldown time for sending messages.
    - `chat.format`: Customize the chat message format.

- **Bad Words**:
    - `badwords`: List of words to block in chat.

- **Messages**:
    - Customize all plugin messages, including private messaging, errors, and notifications.

## Installation

1. Download the plugin JAR file.
2. Place the JAR file in your server's `plugins` folder.
3. Start or restart your server.
4. Edit the `config.yml` file in the `plugins/BramChat` folder to customize the plugin.
5. Use `/bramchatreload` to apply configuration changes without restarting the server.

## Development

### Prerequisites

- Java 17 or higher
- Maven

### Support
For support, please open an issue on the GitHub repository or contact the developer directly.
# https://dsc.gg/smpstore