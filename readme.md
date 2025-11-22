# **The Modern Arch Linux Handbook (AI Powered)**

A next-generation, interactive, and AI-enhanced guide for installing Arch Linux. This single-page application replaces static wikis with a dynamic, context-aware handbook that adapts to your hardware and helps you troubleshoot errors in real-time.

**Current Version:** v13.0 (Gold Master)

## **🌟 Key Features**

### **🧠 AI-Driven Tools (Powered by Gemini)**

* **💻 Hardware Scout:** Checks your specific laptop or motherboard model for Linux compatibility issues before you start.  
* **🧮 Partition Architect:** Mathematically calculates the perfect partition layout based on your drive size and RAM.  
* **✨ Magic Paste:** Paste the messy output of lsblk or blkid, and the app automatically extracts the UUIDs and fills them into the configuration commands.  
* **🚑 Error Medic:** Paste obscure Arch error logs, and the AI diagnoses the root cause and provides the exact fix commands.  
* **🎨 Rice Designer:** Describe your dream aesthetic (e.g., "Cyberpunk Neon"), and it generates a list of themes, icons, and fonts to install.

### **🛡️ Safety & Reliability**

* **⛑️ Rescue Mode:** A global toggle that instantly transforms the guide from an "Installation Manual" into a "Disaster Recovery Dashboard," providing one-click repair commands for bootloaders, keyrings, and kernels.  
* **💾 State Persistence:** Your hardware selection, UUIDs, and custom scripts are saved to your browser's local storage. You won't lose your place if you refresh the page.  
* **🩺 Config Doctor:** Validates your critical config files (fstab, arch.conf) against your hardware profile to catch syntax errors before you reboot.

## **🚀 Usage**

1. **Download:** Clone this repository or download the index.html file.  
2. **Run:** Simply open index.html in any modern web browser. No server or backend is required.  
3. **Configure:** Use the "Hardware Configurator" at the top to select your CPU (Intel/AMD) and GPU (Nvidia/AMD/Intel). The code snippets throughout the guide will rewrite themselves to match your hardware.

## **🛠️ Technical Stack**

* **Frontend:** Native HTML5, JavaScript (Vanilla), and Tailwind CSS (via CDN).  
* **AI Backend:** Integration with Google's Gemini API (configured for browser-based use).  
* **Storage:** LocalStorage for state persistence.

## **🤝 Contributing**

If you find a bug or want to add a new feature (like a new AI tool), feel free to open an issue or submit a pull request\!

*Built for the Arch Linux community.*