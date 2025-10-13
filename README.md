# 🕵️‍♂️ Foobar 2025 Q1: The Vault Breach

## 🚀 Background
*Since 1975, ACI has secured global payments. But fraudsters never sleep...*

## 🎯 Your Mission
Act as a fraud analyst. Investigate suspicious transactions and protect the Vault (our most critical transaction store).

## 🗂️ Dataset Overview
You’ll analyze several CSV files (each a "table"):

- **transactions.csv:** Raw transaction log
- **users.csv:** Customer account details
- **hosts.csv:** Servers that processed transactions
- **blacklist.csv:** Flagged accounts/recipients
- **notes.csv:** List of flagged keywords
- **devices.csv:** User device info

*Note: All datasets are in CSV format. You may use any programming language or tools you prefer for analysis (e.g., Python, R, JavaScript, Excel, Java, C#, or others).*

## 🕵️‍♀️ Suspicious Indicators Hints
- **Geolocation anomalies**
- **Exceeded Daily Limits more than 3 times** 
- **Blacklisted Entities**
- **Flagged notes**
- **Routing issues**
- **Incorrect payments**

## 🏆 Scoring
- Read in csvs and display as a table: **30 pts**
- Correct Sender IDs submitted to Vault: **5 pts each**
- Quality of logic/rules used: **10 pts per correct ID**

## ⚙️ Getting Started
1. Clone the repo:
   ```sh
   git clone https://github.com/AD12334/foobar_2025_Q1.git
   ```
2. Choose your preferred language and tools for analysis. You may use any programming language or software capable of reading CSV files.
3. (Windows) Run `vault.exe` directly.  
   (Linux/Mac) You may need to install Wine and set permissions:  
   ```sh
   chmod +x vault.exe && wine vault.exe
   ```

4. Explore the CSVs and apply the fraud rules.

## ❗ Tips
- Some rules are subtle. Use both logic and creativity!
- Not all answers are directly hinted. Bonus for finding wildcards!

---

*Questions? Contact the challenge admin team.*
