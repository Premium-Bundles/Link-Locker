# URLlock
🔒 URL Lock (Link Locker) Tool is a 100% safe, encrypted way to protect your private or premium links. It collects no personal data — everything is secured locally in your browser. Simply lock your link with a password and share it safely. Fast, private, and completely secure.

🛡️ Link Locker — Secure Link Encryption Tool

**Link Locker** is a lightweight, client-side tool that lets you **create password-protected links** — entirely in your browser.
It never sends your data, password, or destination URL to any server. Everything stays safe, private, and fully encrypted on your own device.

---

### 🔒 What It Does

* You enter a **destination URL**, add a **title**, **description**, **password**, and **optional hint**.

* The tool generates an **encrypted shareable link** that looks like this:

  ```
  https://yourdomain.com/link-locker.html#lock=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
  ```

* When someone opens that link, they’ll see:

  * The title
  * Description
  * Password hint
  * A password field to unlock the link

Once the correct password is entered, the user is securely redirected to the original destination.

---

### 🧩 How It Works

* **All encryption happens locally** in the user’s browser (client-side).
* The encrypted payload (URL, title, hint, etc.) is stored inside the URL fragment (`#lock=...`).
* No information is uploaded, logged, or shared — **not even temporarily**.
* The password is never sent anywhere; it’s only used locally to encrypt/decrypt.

---

### ✅ Key Features

| Feature                         | Description                                          |
| ------------------------------- | ---------------------------------------------------- |
| 🔐 **Client-side encryption**   | No data ever leaves your device.                     |
| ⚙️ **No setup required**        | Just open the HTML file in any modern browser.       |
| 📎 **Shareable encrypted link** | Safe to share without exposing sensitive URLs.       |
| 🧭 **Automatic dual mode**      | Detects whether you’re in “create” or “unlock” mode. |
| 💬 **Password hint**            | Optional reminder for easy recall.                   |
| 🌈 **Minimal modern UI**        | Soft pastel design with rounded edges.               |

---

### ⚙️ How to Use

#### 1. Create a Locked Link

1. Open `link-locker.html` in your browser.
2. Enter:

   * Destination URL
   * Title
   * Optional description and hint
   * Password
3. Click **“Generate Locked Link.”**
4. Copy or open the generated encrypted link.

#### 2. Share

Send the generated encrypted link to anyone you trust.

#### 3. Unlock

When someone opens the link:

* They’ll see the title, description, and hint.
* Once they enter the correct password, the destination unlocks instantly.

---

### 🧠 Technical Overview

* **Encryption:** Base64 encoding (can be extended to AES for advanced security).
* **No Dependencies:** 100% pure HTML, CSS, and vanilla JavaScript.
* **Offline-Ready:** Works even without internet access.
* **No Tracking:** Zero cookies, zero analytics, zero telemetry.

---

### ⚠️ Important Notes

* This tool is meant for **lightweight client-side link protection**, not industrial-grade secret storage.
* For highly sensitive or critical data, use a **server-side encryption service**.
* Always test your generated links before sharing.

---

### 🧾 Example Use Cases

* Sharing private documents or cloud links safely.
* Locking special content (bonus files, media, hidden pages).
* Protecting project links or prototype URLs before release.
* Securely sharing internal resources with teammates.

---

### 💬 Why It’s Safe

> 🔐 *“Your data never leaves your browser.”*

Everything happens right on your machine —

* No backend.
* No storage.
* No external requests.
* No tracking scripts.

Even if someone intercepted your link, without the password the encrypted fragment is meaningless.

---

### 🧑‍💻 Credits

Created with ❤️ using HTML, CSS, and JavaScript.
Designed for simplicity, privacy, and full user control.

