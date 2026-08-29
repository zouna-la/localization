# 🌍 ZounaLa (走哪啦) · Community Localization Project

> **Help make ZounaLa feel truly native in your language & earn a Free Ultimate Lifetime Membership!** 🎁

---

## 📱 Project Overview

![ZounaLa Multi-Language Localization](localization.png)

**ZounaLa (走哪啦)** is a privacy-first, zero-server iOS lifestyle application designed for memory curators, city flâneurs, and outdoor explorers to capture daily footsteps, idle moments (发呆时光), and intimate shared milestones.

To bring the best possible experience to users worldwide, we want every button, subtitle, prompt, and widget to read naturally and authentically — whether in **Korean (한국어)**, **Japanese (日本語)**, **English**, or other languages.

---

## 🎯 Why We Need Your Help

While automated tools provide an initial baseline, native speakers understand the cultural nuances, tone of voice, and idiomatic phrasing that make an app feel truly warm and human:

- **Idiomatic Expressions**: How native speakers naturally refer to "taking a moment to space out / idle" (发呆), "footprint check-ins" (足迹打卡), and "private intimate space" (亲密空间).
- **Concise & Polished UI Text**: Ensuring translations fit elegantly inside mobile buttons, widgets, notifications, and watch faces.
- **Accurate Permission Contexts**: Explaining camera, photo library, location, and Bluetooth permissions clearly and respectfully.

---

## 🎁 Contributor Reward: Free Ultimate Lifetime Membership

Every quality contribution makes a real difference! To express our gratitude:

✨ **Any contributor whose Pull Request (or well-documented translation improvement) is reviewed and approved will receive a Free ZounaLa Ultimate Lifetime Membership activation code (永久终身会员, $24.99+ value).**

### 🔑 How to Receive Your Activation Code:
1. **Find Your Account ID**:
   - Open the **ZounaLa** app on your iPhone.
   - Go to **Settings (设置)** ➔ **Ultimate Membership (Ultimate 会员激活)**.
   - Tap **Your Account ID** (the 8-character code shown on screen, e.g. `886333C5`) to copy it.
2. **Submit with Your PR / Commit**:
   - When creating your Pull Request, include the following in your **PR description** (or commit message):
     - **Your 8-character Account ID**: (e.g. `Account ID: 886333C5`)
     - **Your Email Address**: (e.g. `Email: yourname@example.com`)
3. **Receive Your Code via Email**:
   - Once our team reviews and approves your submission, we will generate your personalized Ultimate Lifetime activation code and send it directly to your provided email address!

---

## 📂 The File to Edit

The core localization file in this repository is:

- [`Localizable.xcstrings`](Localizable.xcstrings) — Apple's standard **Xcode String Catalog** (JSON format), containing all user-facing strings for **English (`en`)**, **Korean (`ko`)**, **Japanese (`ja`)**, and **Simplified Chinese (`zh-Hans`)**.

---

## 🛠 How to Contribute

### Method 1: Using Xcode (Recommended for Apple Developers)
1. Fork and clone this repository.
2. Open [`Localizable.xcstrings`](Localizable.xcstrings) in **Xcode 15 or later**.
3. Use Xcode's visual String Catalog editor to filter untranslated or stale keys, edit values, and review translations.
4. Commit and push your changes, then submit a Pull Request.

### Method 2: Using Any Code Editor (VS Code, Cursor, Sublime, etc.)
1. Fork and clone this repository.
2. Open [`Localizable.xcstrings`](Localizable.xcstrings) in your favorite text/JSON editor.
3. Locate the language key (`ko`, `ja`, `en`) under the target string entry and update the `"value"` field.
4. Verify JSON syntax validity.
5. Commit and push your changes, then submit a Pull Request.

### Method 3: Submitting an Issue
If you do not use Git/GitHub PRs:
1. Open a new [GitHub Issue](https://github.com/zouna-la/localization/issues).
2. Clearly mention the original text (or English/Chinese key) and your suggested translation in your language.
3. Include your ZounaLa **Account ID** and **Email address** so we can email your Ultimate Lifetime reward!

---

## 💡 Localization Guidelines

- **Preserve Format Specifiers**: Keep all placeholders (e.g. `%@`, `%lld`, `%1$@`, `%2$@`, `%d`) intact so dynamic numbers and dates render correctly.
- **Maintain UI Conciseness**: Mobile screens have limited space. Prefer concise, natural phrasing over literal word-for-word translation.
- **Friendly & Mindful Tone**: ZounaLa is a warm, aesthetic lifestyle companion. Use polite, encouraging, and welcoming language.

---

## 🤝 Questions & Feedback

If you have questions about specific contexts or terms, feel free to open a [GitHub Issue](https://github.com/zouna-la/localization/issues) or reach out. 

Thank you for helping us make ZounaLa better for people around the world! ❤️
