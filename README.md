# 🛡️ SilentGuard — Protection That Never Sleeps

> **Hackwarts 2026 · Law & Enforcement Track · RKGIT Ghaziabad**

SilentGuard is an AI-powered passive distress detection system that triggers emergency response **automatically** — no button press, no voice command, no unlocking required.

---

## 🚨 The Problem

Every emergency system today requires you to make a call, press a button, or unlock your phone.  
But real emergencies happen **exactly when that's impossible** — when you're being followed, when you can't speak, when you're unconscious.

---

## 💡 Our Solution

SilentGuard monitors for distress in the background using three passive signals:
- **Voice keywords** — "help", "bachao", "chodo", "stop it" (Hindi + English)
- **Accelerometer patterns** — violent shaking, fall detection, prolonged stillness
- **Volume button trigger** — triple-press from pocket, no unlocking needed

When danger is detected, it automatically:
1. Sends live GPS location to 3 emergency contacts via SMS
2. Starts a 10-second countdown then auto-dials 112
3. Begins silent audio/video recording (screen stays dark)
4. Uploads evidence to cloud **in real time** — survives phone destruction

---

## ✨ Features

| Feature | Description |
|--------|-------------|
| 🎙️ Voice Keyword Detection | Hindi + English distress keywords, no continuous recording |
| 📳 Accelerometer Trigger | Violent shake, fall + stillness = emergency |
| 📍 Live GPS SMS | Google Maps link sent to 3 saved contacts |
| ☁️ Real-Time Cloud Upload | Evidence uploaded during event — destruction-proof |
| 📞 Fake Call Shield | Instant fake incoming call — custom caller name |
| ⏱️ Dead Man's Switch | Set a check-in timer — miss it, contacts are alerted |
| 🔕 Dark Screen Recording | Records while screen stays completely black |
| 🆘 Auto 112 Dialling | 10-second countdown then auto-dials emergency services |

---

## 📱 Tech Stack

**App (Android)**
- MIT App Inventor
- AccelerometerSensor, SpeechRecognizer, LocationSensor
- Texting, PhoneCall, SoundRecorder components
- TinyDB (local storage), Web component (cloud upload)

---

## 🆚 Why Not Just Call 112?

| Feature | 112 | SilentGuard |
|---------|-----|-------------|
| Requires you to call | ✗ Yes | ✓ No |
| Works if you can't speak | ✗ No | ✓ Yes |
| Auto-sends location | ✗ No | ✓ Yes |
| Evidence preserved | ✗ No | ✓ Yes |
| Evidence survives phone destruction | ✗ No | ✓ Yes |
| Passive monitoring | ✗ No | ✓ Yes |

---

## 🏗️ Project Structure

```
silentguard/
├── index.html          # Landing page (website prototype)
├── README.md           # This file
├── app/
│   └── SilentGuard.aia # MIT App Inventor project file
├── docs/
│   └── SilentGuard_Presentation.pptx
└── demo/
    └── demo_video.mp4  # Demo recording
```

---

## 🚀 How to Run

**App:**
1. Download `SilentGuard.aia` from the `app/` folder
2. Go to [appinventor.mit.edu](https://appinventor.mit.edu)
3. Projects → Import project (.aia) → Upload the file
4. Connect → AI Companion → Scan QR with MIT AI2 Companion app on your phone

Or install the APK directly on any Android device (link in Releases).



