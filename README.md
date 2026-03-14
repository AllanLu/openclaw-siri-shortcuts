# 🤖️ OpenClaw Siri (Local LAN Version)

Turn Siri into a powerful AI assistant by connecting it to your **locally deployed OpenClaw server**.

This version removes Azure/OpenAI cloud dependency and allows Siri to communicate directly with an OpenClaw instance deployed inside your local network.

All you need is:

- ✅ OpenClaw server address (LAN URL)
- ✅ OpenClaw Token
- ✅ Agent name you want to use

---

# ✨ Features

- Connect Siri to locally deployed OpenClaw
- Tested on iPhone, Mac and HomePod (other devices may work but are not officially tested)

---

# 📥 Shortcut Download

Click the link below to download the shortcut:

### OpenClawSiri

- [Shortcut Link](https://www.icloud.com/shortcuts/5ba35b213c2643678ac0285c5222ae9b)

---

# ⚙️ Configuration

1. Open the **Shortcuts** app
2. Find the downloaded shortcut
3. Long press → **Edit**
4. Fill in the following fields:

### 1️⃣ OpenClaw Token
Your authentication token from your OpenClaw deployment.

### 2️⃣ Server Address (Endpoint)
Your local OpenClaw server address.

Example:
```
http://192.168.1.100:18789
```

⚠️ Do not add a trailing `/`

### 3️⃣ Agent Name
Enter the **agent name** configured in your OpenClaw instance.

Example:
```
openclaw:main
```

---

# 🚀 How to Use

Say:

```
Hey Siri, OpenclawForSiri
```

Then start chatting.

You can rename the shortcut to anything you like.
For example:

```
Hey Siri, My AI
```

Avoid using special characters in the shortcut name.

You can also tap the shortcut manually for text-based interaction.

---

# 💬 Conversation Commands

During chat:

- Say **"Quit"** → Exit and return to default Siri

✅ You can edit these command keywords inside the shortcut to match your personal preference.
For example, you can change "Quit" to "Exit", "Stop", or any custom phrase you like.

---

# 🔐 Notes

- Make sure your iPhone/Homepod is connected to the same LAN as your OpenClaw server.
- Ensure your OpenClaw service is running.
- If connection fails, verify IP address and port.
- It is recommended to use a **fast-response model** (e.g., gemini-3-flash or other low-latency models), especially when using HomePod.
- Siri on HomePod has a timeout limit of approximately **10–15 seconds**. If the model response is too slow, Siri may stop waiting for the reply.

---

Enjoy your fully local, private AI assistant powered by OpenClaw 🚀
