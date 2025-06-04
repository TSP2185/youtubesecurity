YouTube channel takeovers — especially those that result in crypto scams being hosted on the compromised channels — often happen through social engineering and malicious file delivery, particularly exploiting **YouTube's "collaboration" or "brand account" settings**. Here’s a breakdown of how these attacks typically happen:

---

### 1. **Initial Social Engineering / Fake Sponsorship**

Attackers pose as legitimate companies (e.g., software developers, crypto startups, gaming brands) and reach out with:

* A fake sponsorship deal
* A collaboration proposal
* An offer to try a product in exchange for review

These messages usually come from spoofed emails or cloned websites and look very convincing.

---

### 2. **Delivery of Malicious Files**

Victims are asked to download a file to preview the "software" or "demo" — often through:

* Google Drive, Dropbox, or WeTransfer links
* An installer (.exe, .dmg), screensaver, or media preview (.scr, .zip, .rar)

The file contains **stealer malware**, such as:

* RedLine Stealer
* Vidar
* Raccoon
* Lumma Stealer

These tools are designed to extract stored browser cookies, tokens, saved passwords, and session data.

---

### 3. **Session Hijacking (No Need for Passwords)**

Once installed:

* The malware pulls session tokens from the victim's browser (Chrome/Edge/Firefox)
* These tokens are enough to hijack a **YouTube/Google session** without needing 2FA or login credentials
* The attacker immediately gains access to YouTube Studio or Google Brand Account settings

---

### 4. **Takeover via Brand Account Delegation**

For YouTube channels linked to a **Google Brand Account**, the attacker can:

* Assign themselves as the **Owner** or **Manager**
* Remove the original account as an Owner (after a 7-day delay for transfer)
* Bypass password/2FA using the session token
* Sometimes, simply change recovery settings to lock out the original creator

---

### 5. **Rebranding to Crypto Scam**

With control of the channel, attackers:

* Rename it to mimic known brands (e.g., Tesla, SpaceX, Ripple)
* Delete existing content or hide it
* Upload pre-recorded livestreams of crypto scams promising giveaways
* Add links to fake crypto airdrop sites or wallet drainers in the description

---

### 6. **Monetization and Spread**

* The channel often has a verified badge and large subscriber base, making it more believable
* YouTube ads or external promotion may be used to amplify the scam
* The goal is to trick users into sending crypto or entering wallet seed phrases

---

### Prevention Tips for Creators

* **Don’t install unverified software** from sponsorship emails
* **Use a dedicated browser** or profile for managing YouTube (limits cookie theft)
* Enable **2FA on all Google accounts** (though session tokens can still bypass this)
* Regularly **review and remove unrecognized account access** in Google Account > Security
* Prefer **signed contracts** and **video calls** to verify sponsors
* Use **hardware keys** (like YubiKey) for higher protection of Google sessions

---
