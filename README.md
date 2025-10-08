# 🔒 Security Analysis of Smart Contracts on Ethereum

This repository presents the main outcomes and concepts of my **Bachelor’s thesis** in Computer Science at the **Frankfurt University of Applied Sciences**.  
The goal of this project was to analyze security vulnerabilities in Ethereum Smart Contracts and to propose effective mitigation strategies through both theoretical and practical evaluation.

---

## 🎯 Objective

The objective of this work was to identify, analyze, and address security risks in Ethereum-based Smart Contracts.  
The thesis combines **theoretical research** with **practical implementation and testing**.

---

## 🧠 Research Question

> *Which security-relevant risks occur during the development of Smart Contracts on Ethereum – and how can they be effectively detected and mitigated?*

---

## ⚙️ Methodology

The project consisted of two main phases:

### **1. Theoretical Part**
- Understanding Blockchain technology, Ethereum, and Smart Contract fundamentals  
- Studying common vulnerabilities (e.g., Reentrancy, Gas usage, Guard conditions)

### **2. Practical Implementation**
- Development of sample Smart Contracts (**CryptoBank** and **CryptoBankSecure**) using **Solidity**  
- Deployment and testing on **Sepolia Testnet** with **MetaMask**  
- Static analysis with:
  - [Remix IDE Analyzer](https://remix-ide.readthedocs.io/)
  - [Slither Security Framework](https://github.com/crytic/slither)
- Improvement and re-analysis of the secured version

---

## 🧩 Technologies Used

- Solidity (v0.8.0)
- Remix IDE
- Slither Analyzer
- MetaMask Wallet
- Sepolia Testnet & Etherscan
- Node.js, VS Code

---

## 📊 Results

- Identified and mitigated **Reentrancy vulnerability**
- Implemented **secure Ether transfer** and **immutable owner variable**
- Reduced **gas consumption**
- Demonstrated clear improvement between the initial and secured versions of the contract

---

## 📘 Project Presentation

Below are simplified, public versions of my Bachelor’s thesis presentation.  
They are designed to **illustrate the content and methodology** in a neutral layout.

- 🇩🇪 [German Version (PDF)](./presentation/presentation_DE.pdf)  
- 🇬🇧 [English Version (PDF)](./presentation/presentationEN.pdf)

---

## 🧭 Outlook

Smart Contracts represent a powerful technology but still face challenges such as:
- Scalability  
- Usability  
- Legal and regulatory frameworks  

Future research may include combining Smart Contract analysis with **AI-driven security tools**, **oracles**, and **automated contract verification**.

---

## 🧑‍🎓 Author

**Yousef Ghanem**  
Bachelor of Science in Computer Science  
Frankfurt University of Applied Sciences – 2025  

*(This repository is for demonstration and educational purposes.  
Official university logos and templates have been removed.)*
