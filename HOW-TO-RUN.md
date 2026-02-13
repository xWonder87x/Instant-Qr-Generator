# How to run the QR Generator

You don't need Node or Python. Use **one** of these:

---

## Option 1: Open the file directly (try this first)

1. Open **File Explorer** and go to:
   ```
   C:\Users\odiss\OneDrive\Documents\GitHub\Qr-Generator
   ```
2. **Double-click `index.html`**  
   It should open in your default browser (Edge, Chrome, etc.).

If the page loads and you see "QR Generator" and a text box, it works. Type a URL, see the QR code, and use the buttons.

**If the page is blank or shows an error:** use Option 2 or 3 below.

---

## Option 2: Use Live Server in Cursor

1. In Cursor, press **Ctrl+Shift+X** to open the Extensions panel.
2. Search for **Live Server** and install it (by Ritwick Dey).
3. In the file list, **right-click `index.html`** → **Open with Live Server**.  
   A browser tab will open with the app.

---

## Option 3: Install Python (then use a small server)

1. Open **Microsoft Store**, search for **Python 3.12** (or latest), and install it.
2. **Close and reopen** PowerShell.
3. Run:
   ```powershell
   cd "C:\Users\odiss\OneDrive\Documents\GitHub\Qr-Generator"
   python -m http.server 8080
   ```
4. In your browser, open **http://localhost:8080/index.html**.

---

**Summary:** Try **Option 1** (double-click `index.html`). If it doesn't work, use **Option 2** (Live Server) or Python (**Option 3**).
