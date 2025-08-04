

# 📵 Accessibility-Based MDM Filter – *WebNoView*

A lightweight Android accessibility tool that acts like an MDM-based content filter. This app scans the screen for specific **watched words or phrases** and automatically exits the current screen if a match is detected — ideal for blocking undesirable content (e.g., AI-related messages).

---

## 🚀 Features

* 🔍 **Real-time content filtering** using accessibility services
* ✍️ **Custom word/phrase lists** via JSON files
* 💾 **Importable configurations** contributed by the community
* 📱 Optional **basic MDM-style locking** for stricter filtering

---

## 🧠 How It Works

You define a list of words or combinations to "watch for." If any appear on screen, the app automatically navigates away (e.g., to the home screen), helping you enforce stricter device compliance.

---

## 📂 Contribute Your Filters

Got a useful filter list? Help others by sharing!

1. Create a `.json` file containing your word combinations.
2. Name it like this:
   `block_ai_in_messages__by_@yourname.json`
3. Submit a **pull request** to this repo.

Once approved, all users will be able to **import and activate** your filters from the app.


---

## 🛡️ Optional "Kasher Mode" (MDM Functionality)

Enable optional MDM-style controls to **lock down the device** for filtering needs. This is basic for now but will expand with time.

---

## 📥 Download

Grab the latest APK from the [Releases page](https://github.com/TripleU613/WebNoView-Storage/releases).

---

## 🙌 Community

We welcome contributions and filter sets from the broader community. Let’s build a cleaner, smarter experience—together.

---

## 🔒 Disclaimer

This app uses Android's Accessibility Service. Please ensure you use it responsibly and in accordance with platform policies and user consent.

