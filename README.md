
# 🧠 ChatGPT Response Manager

A lightweight yet powerful Chrome Extension that helps manage ChatGPT conversations more efficiently by **collapsing long responses**, offering **quick previews**, and letting you **save important responses for later**.

Perfect for power users who regularly work with long conversations and want a cleaner, faster, and more focused experience.

---

## ✨ Features

- ✅ Automatically **collapses lengthy ChatGPT responses**
- 🔄 **Toggle expand/collapse** with “Show More” / “Show Less” buttons
- 🧩 **Preview** of user messages (first 5 words shown)
- 📌 **Add important responses to a “Card” list** for quick access later
- 🚀 Detects and processes **new messages in real time**
- 💾 Saves state with `localStorage` so your preferences persist
- ⚙️ Configurable thresholds for collapsing (lines, characters, etc.)
- 🧠 Optimized for minimal DOM manipulation and better performance

---

## 📷 Demo

![Demo](https://res.cloudinary.com/dza2t1htw/image/upload/v1747201710/awnvsqamixgiujfdsopk.png)


---

## 🧰 Installation & Build Instructions

This project uses **HTML**, **CSS**, and **JavaScript** for building the Chrome extension.

### 🔨 Build Steps

1. **Clone the repository**  
   ```bash
   git clone https://github.com/shax26/chatgpt-rm.git
   cd chatgpt-response-manager
   ```
2. **Load in Chrome**

- Visit `chrome://extensions/`
- Enable **Developer Mode**
- Click **Load Unpacked**
- Select the project folder containing the `manifest.json`

---

## 🗂️ Project Structure

```
chatgpt-response-manager/
├── src/
│   ├── assets/
│   │   ├── content/
│   │   │   ├── contentScript.js     # JavaScript for modifying web page content
│   │   │   └── popup.js             # Script for popup functionality
│   │   └── icons/
│   │       └── icon128.png          # Extension icon
├── index.html                       # Main HTML page for the extension
├── manifest.json                    # Chrome Extension manifest file
└── README.md                        # Project documentation
```

---

## ⚙️ How It Works

The extension enhances your ChatGPT experience through:

- **Message Collapse**  
  Automatically collapses assistant responses and previews user messages for quick scanning.

- **Interactive Controls**  
  Each message gets a **"Show More" / "Show Less"** toggle, making long threads manageable.

- **Add to Card**  
  Important responses can be **saved into a persistent “Card” section**—great for bookmarking key info or reusable prompts.

- **Real-Time Monitoring**  
  A `MutationObserver` tracks updates to the conversation and dynamically applies all functionality.

- **Performance Friendly**  
  Designed to minimize DOM updates and keep the page smooth, even during large conversations.

---

## ✅ Browser Support

| Browser        | Supported |
|----------------|-----------|
| Chrome         | ✅         |
| Microsoft Edge | 🔜 Coming Soon         |
| Firefox        | 🔜 Coming Soon |

---

## 🧪 Contributing

We welcome PRs and contributions from the community!

### Steps to Contribute

1. Fork the repo  
2. Create a feature branch  
   ```bash
   git checkout -b feature-name
   ```
3. Make changes and commit  
4. Push and open a PR  
   ```bash
   git push origin feature-name
   ```

Clone and set up the project:

```bash
git clone https://github.com/shax26/chatgpt-rm.git
cd chatgpt-response-manager
```

---

## 📄 License

Licensed under the [MIT License](LICENSE).

Feel free to modify and use for personal or professional use.

---

## 🙌 Acknowledgments

Built to improve real-world productivity and focus while working with ChatGPT.  
Special thanks to the open-source community for providing tools, inspiration, and guidance.

> *“Sometimes, small tools make the biggest difference.”*