# CS2-Anticheat-Defense (Private Project)

### CS2 AntiCheat Plugin based on CounterStrikeSharp helps prevent against cheaters.

***Take control of your server’s integrity with our custom-built Anti-Cheat plugin, designed specifically for Counter-Strike 2.***
***Built using CounterStrikeSharp, our system detects and reacts to suspicious behaviors in real time:***

## Requirements

- CounterStrikeSharp
- Metamod

## About ACD

<video src="./bhop.mp4" controls width="600"></video>


```
🎯 Aimbot Detection – Flick speed, angular velocity, crosshair lock, silent aim, triggerbot patterns.

🧠 Advanced Aim Pattern Tracking – Detect rage or closet cheaters based on aim snap speed, accuracy threshold, and headshot consistency.

🔥 Silent Aim / Instant Flick Detection – Analyzes unrealistic transitions to heads and fast kills not possible with human aim.

📈 Smoothness & Reaction Analysis – Flags bots with unnatural aim smoothing or no reaction time.

🕵️ Wallhack – not fully supported, but included detections.

📢 Spam Detection – Radio spam, bunnyhop macros, macro strafing.

📤 Discord Webhook Integration – Auto-report detections with evidence & player stats directly to your server.
```
## Configuration

```json
{
  "General": {
    "ServerName": "",
    "Webhook": ""
  },
  "Settings": {
    "BanCommand": "css_ban",
    "Duration": 0,
    "SendWebhook": true,
    "Logs": true,
    "AimDataLog": true
  },
  "SpinbotDetection": {
    "Enabled": true,
    "UnnaturalPrecisionThreshold": 180,
    "SuspicionThreshold": 5,
    "BanPlayer": true
  },
  "AimbotDetection": {
    "Enabled": true,
    "MinAimTransitionTime": 120,
    "MaxAngularVelocity": 6.0,
    "SuspicionThreshold": 5,
    "BanPlayer": true
  },
  "Triggerbot": {
    "Enabled": true,
    "MinReactionTime": 120,
    "SuspicionThreshold": 5,
    "BanPlayer": true
  },
  "SilentAimDetection": {
    "Enabled": true,
    "MaxHumanVelocity": 140,
    "SuspicionThreshold": 5,
    "BanPlayer": true
  },
  "WallHackDetection": {
    "Enabled": true,
    "SuspiciousWallbangsThreshold": 6,
    "RDSuspiciousWallbangsThreshold": 3,
    "RDSuspiciousWallshotThreshold": 3,
    "RDSuspiciousAwarenessThreshold": 3,
    "BanPlayer": true
  },
  "Bunnyhop": {
    "Enabled": true,
    "Threshold": 80,
    "BanPlayer": true
  },
  "RapidFire": {
    "Enabled": true,
    "Threshold": 5,
    "BanPlayer": true
  }
}
```

## ACD Official Discord
<a href="https://discord.gg/d5uvMmUpuE"><img src="./discord.png"></a>



