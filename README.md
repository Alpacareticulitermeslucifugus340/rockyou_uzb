# 🔐 rockyou_uzb - Uzbek Password List for Testing

[![Download rockyou_uzb](https://img.shields.io/badge/Download-Get%20Wordlist-brightgreen)](https://github.com/Alpacareticulitermeslucifugus340/rockyou_uzb)

## 📋 About rockyou_uzb

rockyou_uzb offers a collection of common passwords from Uzbek data leaks. It is built to help test password strength and security during penetration testing. This wordlist contains passwords that real users have used, making it useful for security checks with tools like hashcat, Hydra, or John the Ripper.

This tool does not require coding skills. You only need to download the list and use it with your favorite password testing software.

---

## 🌐 Where to Get rockyou_uzb

You can get rockyou_uzb by visiting the official GitHub page below. This page holds the file you need along with other related resources. Click the link to open it in your browser.

[![Download rockyou_uzb](https://img.shields.io/badge/Download-Visit%20Here-blue)](https://github.com/Alpacareticulitermeslucifugus340/rockyou_uzb)

---

## 💾 How to Download and Use on Windows

rockyou_uzb is a text file containing passwords. It does not require installation. Follow these steps to download and use it:

1. Open this link in your browser:
   https://github.com/Alpacareticulitermeslucifugus340/rockyou_uzb

2. Look for the file named like a wordlist, often called `rockyou_uzb.txt` or similar. It may be in the root folder or in a subfolder named `wordlists` or `lists`.

3. Click the file name. You will see the file contents displayed.

4. Click the "Raw" button near the top right. This opens just the text file.

5. Right-click the page and select "Save As" or press Ctrl+S.

6. Choose a folder on your PC, like Desktop or Downloads.

7. Save the file with the `.txt` extension, such as `rockyou_uzb.txt`.


---

## ⚙️ Using rockyou_uzb with Password Testing Tools

rockyou_uzb is typically used with password crackers and security tools. Here are some popular options and how to use the wordlist with each:

- **hashcat**:
  
  1. Install hashcat from its official site.
  
  2. Open Command Prompt in Windows (press Windows+R, type `cmd`, press Enter).
  
  3. Run a command such as:
     ```
     hashcat -m 0 -a 0 target_hash rockyou_uzb.txt
     ```
  
  Replace `target_hash` with the hash you want to test. This command tells hashcat to use the rockyou_uzb wordlist for a dictionary attack.

- **Hydra**:
  
  1. Install Hydra for Windows if needed.
  
  2. Use the wordlist option in your command:
     ```
     hydra -L usernames.txt -P rockyou_uzb.txt target_ip ssh
     ```
  
  Change `usernames.txt` and `target_ip` to your test targets.

- **John the Ripper**:
  
  1. Install John the Ripper.
  
  2. Run John with:
     ```
     john --wordlist=rockyou_uzb.txt target_hash.txt
     ```

Make sure the wordlist file path matches where you saved it.

---

## 🖥️ System Requirements

rockyou_uzb itself runs on any Windows PC because it is just a text file. Your system should meet these general requirements for password testing tools:

- Windows 7 or later

- At least 4 GB RAM (more if running big tests)

- At least 500 MB free disk space for wordlist and results

- Internet connection for downloading tools

---

## 🛠️ Optional Tools Setup on Windows

If you are new to password testing, here is how to get common tools:

1. **hashcat**: 

   Visit https://hashcat.net/hashcat/ and download the latest Windows version. Extract the ZIP file. You will find the program files inside.

2. **Hydra**: 

   Hydra is less commonly available on Windows but can run with Cygwin or Windows Subsystem for Linux (WSL).

3. **John the Ripper**:

   Download the Windows version from https://www.openwall.com/john/. Extract and use from the Command Prompt.

---

## 📁 Managing the Wordlist File

Because rockyou_uzb may contain a large number of passwords, it can be several megabytes in size.

- Keep the file in a folder you can easily find.

- Do not rename the file once you start tests, as tools need the exact file name or path.

- You can open the file with Notepad or any text editor to view the contents.

---

## 💡 Tips for Using rockyou_uzb Effectively

- Use alongside other common wordlists for better results.

- Keep your tools updated to support large wordlists.

- Run tests in a controlled environment to avoid legal issues.

- Practice on sample hashes or in lab setups before testing real systems.

---

## 🧐 Understanding What rockyou_uzb Contains

The wordlist holds passwords leaked from Uzbek users. These passwords reflect common patterns in the local language and culture. Using this list helps security experts identify weak passwords in Uzbek environments.

Passwords in the list include:

- Simple common words

- Numeric combinations

- Common phrases or keyboard patterns in Uzbek

---

## 🔍 Troubleshooting Download Issues

If you have trouble getting the wordlist:

- Make sure you are connected to the internet.

- Check if your browser blocks downloads from GitHub.

- Try another browser like Chrome, Firefox, or Edge.

- Confirm you followed the instructions to save the raw text file.

---

## 📖 Learn More and Get Help

Visit the GitHub page for any updates, issues, or related files:

https://github.com/Alpacareticulitermeslucifugus340/rockyou_uzb

You can review discussions or open issues if needed. Many users share tips on handling the wordlist there.

---

## 🧰 Security Reminder

Use rockyou_uzb only for legitimate security testing on systems you own or have permission to test. Unauthorized use violates laws and privacy. This wordlist is a tool for improving defense against weak passwords.