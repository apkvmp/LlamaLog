# 🦙 LlamaLog

LlamaLog is a root-based Android Logcat viewer that allows capturing logs per app with log level filtering, auto-scroll and save support.

---

## 🚀 Features

- 🔍 Per-app log monitoring
- 🎚 Log level selection (V, D, I, W, E, F)
- 🎨 Color-coded logs
- 🔄 Auto-scroll
- 💾 Save logs to /storage/emulated/0/
- 🧹 Clear logs
- 🔐 Root access detection
- 🔎 App search support

---

## 📱 Requirements

- Rooted Android device
- Android 8.0+
- Superuser access (Magisk / SuperSU)

---

## 📦 How It Works

LlamaLog uses root-level logcat access:

```
su -c logcat
```

It filters logs per selected application package and selected log levels.

---

## 🛠 Built With

- Kotlin
- Jetpack Compose
- Android SDK

---

## ⚠️ Disclaimer

This app requires root access.  
Use responsibly. The developer is not responsible for misuse.

---

## 📜 License

MIT License

Copyright (c) 2026 @haxgray

Permission is hereby granted, free of charge, to any person obtaining a copy...
