# Macey's Order Verification Demo

This repo contains a clean HTML recreation of a Macey's (Utah grocery) order verification screen, plus a practical checklist for telling real confirmations from fakes.

## Files

- `index.html` — Pixel-accurate recreation of the verification UI
- `README.md` — This file

## How to view the demo

1. Open `index.html` in any browser, **or**
2. Visit the live GitHub Pages version (if enabled) or just double-click the file.

## How to tell if a real verification is fake

Even though the UI can be perfectly recreated with code (as shown here), these methods cannot be faked by outsiders:

### 1. Check your actual Macey's account (best method)
- Open the official Macey's app or go to [shop.maceys.com](https://shop.maceys.com)
- Log in with the account that supposedly placed the order
- Go to **Account → Orders / Order History**
- Search for the exact Receipt ID (e.g. `MAC-20260511-844622`)
- If the order **does not appear** → **Fake**

### 2. Call the store
- Macey's Eagle Mountain: **(801) 789-4440**
- Give them the Receipt ID and ask them to confirm the order exists

### 3. Quick authenticity checklist

```
[ ] Order appears in your official Macey's account with matching Receipt ID?
[ ] Store confirms the order exists when you call?
[ ] Receipt ID starts with MAC-YYYYMMDD- + 6 digits?
[ ] Product is actually sold at that Macey's location?
[ ] You received the message inside the official app (not random SMS/WhatsApp)?

If the first two are NO → treat it as fake.
```

## Context

This demo was created during a conversation about verifying a real-looking order confirmation from Macey's Eagle Mountain, UT for Helados Mexico popsicles.

**Note:** This is for educational / demonstration purposes only. Always verify orders through official channels.

---
Created with Grok