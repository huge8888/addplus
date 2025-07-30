# AddPlus Auto Claim (Self-Modify List) 3000 acc ready

Automatically clicks "Claim" on AddPlus Boost links and navigates through your own custom list of referral links.

✅ 100% Customizable | ✅ No Looping | ✅ Easy Setup

---

## 📦 Features

- Auto-clicks "Claim" on `https://addplus.org/boost/*` pages.
- Automatically moves to the next referral link.
- You can modify the list of links yourself inside the script (`urls` array).
- Built for Tampermonkey (Chrome/Edge/Firefox).

---

## ⚙️ How to Install & Use

### 1. 🧩 Install Tampermonkey Extension

- [Chrome / Edge / Brave](https://tampermonkey.net/?ext=dhdg&browser=chrome)
- [Firefox](https://tampermonkey.net/?ext=dhdg&browser=firefox)

---

### 2. 🧾 Install the Script

#### Option A: Manual Installation

1. Open the Tampermonkey dashboard
2. Click `+ Create a new script`
3. Delete all default content in the editor
4. Copy and paste the entire script from `AddPlus Auto Claim (Self-Modify List)forfree.user.js`
5. Save the script

#### Option B: One-Click Install (GitHub Raw Link)

Coming soon — once the `.user.js` file is uploaded as raw content on GitHub.

---

### 3. 🧠 Customize Your Referral Links

Edit the script and look for this section:

```js
// ✅ ใส่ลิงก์ทั้งหมดของคุณตรงนี้
const urls = [
  "https://addplus.org/boost/your_friend_1",
  "https://addplus.org/boost/your_friend_2",
  ...
];
```

Replace the URLs with your own referral links.

---

## 🧪 How It Works

1. Script runs on any `https://addplus.org/boost/*` page.
2. Waits for the "Claim" button to load.
3. Clicks the button.
4. After 15 seconds, redirects to the next link in the list.
5. Stops when it reaches the last link.

---

## 🛠️ Tips

- You can add as many links as you want.
- Comment out links using `//` if needed.
- To restart, just reload the first URL.

---

## 🚫 Troubleshooting

- ❌ Button not clicking? Ensure you're on a valid boost page.
- ❌ Not moving to next? Check for popup/redirect blockers.
- 🔁 Want to restart? Manually reopen the first link.

---

## 📄 License

This script is for educational & community use only. Use it responsibly.
