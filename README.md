# CS2-Anticheat-Defense (Private Project)

Advanced anti-cheat plugin for Counter-Strike 2, built on top of CounterStrikeSharp.

ACD is designed to detect both blatant rage cheats and advanced closet cheats through layered behavioral analysis, real-time monitoring, and engine-level detection systems. Instead of relying on simple pattern checks or signature-based scans alone, ACD continuously analyzes player behavior, command input, aiming consistency, movement anomalies, and engine interaction patterns to identify suspicious activity with high accuracy.

The system combines multiple independent detection layers. This allows ACD to detect everything from aggressive spinbots and aimbots to subtle aim assistance, silent aim manipulation, anti-aim exploits, bhop scripting and nickname manipulation techniques.

<p align="center">
  <img src="./acdd.png" width="1000">
</p>

---

## Requirements

- CounterStrikeSharp
- Metamod:Source

---

The detection architecture is built around evidence accumulation and long-term behavioral analysis rather than relying on a single suspicious action for instant detection. This approach allows the anticheat to identify advanced closet cheaters attempting to conceal their assistance through humanized settings, smoothing, randomized behavior, or subtle aim correction techniques.

https://github.com/user-attachments/assets/dff8d23b-5c58-4f4f-a8f8-7f0bacc48103

---

## Features

### 🎯 Aimbot Detection
Detects flick speed, angular velocity, crosshair snapping, target locking and triggerbot behavior.

### 🧠 Aim Pattern Analysis
Tracks aiming consistency, reaction timing, accuracy anomalies and unnatural aim corrections over time.

### 🔥 Silent Aim & Instant Flick Detection
Detects unrealistic instant transitions, impossible flick consistency and suspicious shot manipulation behavior.

### 🌀 Anti-Aim & Spinbot Detection
Monitors abnormal view-angle + body movement behavior, fake angles and rapid spinning.

### ⚡ Aim Assist Detection
Identifies subtle aim assistance, smoothing behavior, micro-corrections and hidden assistance scripts.

### 🏃 Movement Exploit Detection
Detects bunnyhop scripts, macro strafing, movement manipulation and unnatural acceleration patterns.

### 🎯 No-Spread & Rapid Fire Detection
Identifies weapon spread manipulation, unrealistic firing consistency and rapid weapon action abuse.

### 📢 Spam & Abuse Prevention
Protects against chat spam, radio spam, command abuse and disruptive player behavior.

### 📤 Discord Webhook Integration
Sends detailed detection logs, player statistics and evidence reports directly to your moderation Discord server.

---

https://github.com/user-attachments/assets/75a93e58-e2c5-4bc6-8dc6-bc915a585ef7

## Detection Comparison

```text
┌────────────────────┬──────────────────────┬────────────────────────┐
│        VAC         │  Other Anti-Cheats   │          ACD           │
├────────────────────┼──────────────────────┼────────────────────────┤
│ Signature Based    │ Mostly Event Driven  │ Layered Detection      │
│ Delayed Enforcement│ Basic Heuristics     │ Real-Time Analysis     │
│ Limited Monitoring │ Partial Tracking     │ Deep Behavior Tracking │
│ Predictable Logic  │ Easily Bypassed      │ Multi-Layer Security   │
├────────────────────┼──────────────────────┼────────────────────────┤
│ Passive Detection  │ Reactive Systems     │ Active Monitoring      │
│ Slower Response    │ Moderate Response    │ Fast Detection Engine  │
│                    │ Simple Validation    │ Adaptive Analysis      │
│                    │ Short-Term Checks    │ Long-Term Analysis     │
└────────────────────┴──────────────────────┴────────────────────────┘
```

## Detection Philosophy

ACD does not rely on a single detection method or simple signature checks.

The system combines multiple detection layers, including aim analysis, movement validation, behavioral consistency tracking, timing analysis and statistical monitoring over time.

Even if one detection layer is avoided, other systems continue analyzing player behavior simultaneously, making bypassing more difficult and unreliable compared to traditional event-based anti-cheat plugins.

## ACD Official Discord
<a href="https://discord.gg/d5uvMmUpuE"><img src="./discord.png"></a>



