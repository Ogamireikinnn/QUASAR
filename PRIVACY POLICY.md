# Privacy Policy for QuasarBot

**Last Updated: July 8, 2026**

## 1. Introduction

This Privacy Policy explains how QuasarBot ("the Bot", "we", "our") collects, uses, and protects information when you use our Discord bot. By using QuasarBot, you agree to the data practices described in this policy.

## 2. Information We Collect

### 2.1 Automatically Collected Data
When you interact with QuasarBot, we automatically collect:
- **Discord User ID** - Used to identify your account for alliance and representative tracking
- **Discord Server (Guild) ID** - Used to store server-specific settings
- **Message IDs** - Used for advertisement tracking and leaderboard features
- **Channel IDs** - Used for ad channel, log channel, and welcome channel configuration
- **Role IDs** - Used for representative role and bypass role configuration
- **Command Usage** - Which commands you use for cooldown management

### 2.2 Data You Provide
- **Custom Prefixes** - Server administrators can set custom command prefixes
- **Auto Responder Triggers/Responses** - Configured by server administrators
- **Welcome Messages** - Custom welcome messages configured by server administrators
- **Server Configuration** - Ad categories, rep actions, bypass roles, and other settings

## 3. How We Use Your Information

We use collected data for:
- **Bot Functionality** - Alliance management, auto responders, welcome messages, and server management
- **Server Configuration** - Storing your server's custom settings and preferences
- **Advertisement Tracking** - Tracking representative mentions and managing rep roles in ad channels
- **Leaderboard System** - Tracking ad post statistics for premium servers (daily, weekly, monthly, total)
- **Auto-Moderation** - J2L (Join-to-Leave) system for auto-banning users who leave within 24 hours
- **Rep Management** - Automatic role assignment and removal for representatives

## 4. Data Storage

### 4.1 Database Storage
All data is stored in a secure PostgreSQL/SQLite database. Data includes:
- Server configurations (prefix, channels, roles, settings)
- Advertisement tracking records (user mentions, message tracking)
- Auto responder configurations (triggers, responses, category restrictions)
- Ad leaderboard data (premium servers only - post counts and points)
- Welcome message configurations

### 4.2 Data Retention
- **Permanent Data**: Server configurations, auto responder settings, welcome configurations
- **Leaderboard Data**: Stored permanently for premium servers, can be reset by server admins
- **Advertisement Mentions**: Stored until the representative leaves the server or ad is deleted
- **Command Cooldowns**: Automatically managed by the system

## 5. Data Sharing

We do NOT:
- Sell your data to third parties
- Share your data with advertisers
- Use your data for purposes outside bot functionality
- Export personal data without owner authorization

## 6. User Rights

Server administrators have the right to:
- **View Configuration** - Check all server settings using config command
- **Modify Settings** - Change any server configuration at any time
- **Delete Data** - Reset all server data using resetguild command
- **Remove Bot** - Kick the bot to remove all server data

Bot owner has the right to:
- **Export Data** - Create database backups using exportdb command
- **Import Data** - Restore data using importdb command
- **Delete All Data** - Use nukedb command for complete data wipe

## 7. Security

We implement security measures including:
- Database connection encryption
- Secure environment variables for sensitive tokens
- Input validation to prevent injection attacks
- Rate limiting to prevent abuse
- Permission checks for administrative commands

## 8. Data Collected by Command

| Command/Feature | Data Collected |
|----------------|----------------|
| Auto Responders | Trigger words, response messages, category restrictions |
| Welcome Messages | Channel ID, custom message template, embed color |
| Ad System | User mentions, message IDs, channel IDs, role assignments |
| Leaderboard | User IDs, message IDs, post timestamps, point counts |
| Server Config | Prefix, channel IDs, role IDs, action preferences |
| J2L System | User join/leave timestamps for auto-ban detection |

## 9. Contact Information

If you have questions about this Privacy Policy, you can:
- Contact the bot owner through Discord: quasar (ID: 956902107355689061)
- Use the about command for bot information

---

**By using QuasarBot, you acknowledge that you have read and understood this Privacy Policy.**
