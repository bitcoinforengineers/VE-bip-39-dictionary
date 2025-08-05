 # # 🇻🇪 Venezuelan BIP-39 Wordlist Project

Goal: Create a culturally adapted, memory-friendly, high-entropy Venezuelan Spanish wordlist compatible with BIP-39 seed phrase standards.

 # #📦 What Is This?

This project aims to create an open-source BIP-39-compatible wordlist in Venezuelan Spanish, optimized for ease of memorization by native speakers. The purpose is to support:
Easier onboarding into Bitcoin self-custody
Educational tools in local dialect
Local-first sovereignty tools

 # #🧠 Why?

BIP-39 mnemonic phrases are difficult to remember for non-native English speakers.
Even the official Spanish wordlist is based on European Spanish.
A Venezuelan-adapted list improves accessibility, security, and self-custody adoption.

 # #📐 Design Constraints (to maintain BIP-39 compatibility)

Must contain 2048 unique words.
Each word must be distinct in the first 4 characters.
No special characters or accents.
All lowercase.
Words must be easy to pronounce and familiar to Venezuelans.
No slang with radically shifting meaning.
Favor concrete nouns, verbs, and adjectives.

 # #🔄 Status
```
✅ Phase 1: Word collection (2,500 candidates)
🔄 Phase 2: Filtering & entropy checks
🛠️ Phase 3: BIP-39 compatibility testing
🧪 Phase 4: Wallet test vectors + seed conversion
```
 # #✨ Sample Words (WIP)

arepa
pabellon
llano
cuatro
tequeño
mango
panela
cafe
pelota
morral

 # #📁 Repository Structure
```
venezuelan-bip39/
├── src/
│   ├── wordlist.txt             # Final 2048 wordlist
│   ├── build.py                 # Script to validate entropy, uniqueness
│   └── bip39_test_vectors.json  # Tests for seed phrase compatibility
├── docs/
│   └── methodology.md           # Word selection rationale
├── test/
│   └── test_wallet_integration.py
├── README.md
└── LICENSE
```
 # #🔐 How to Use (Planned)

pip install bip39ven
bip39ven generate 12-word

 # #🚨 Disclaimer

This is an experimental educational project and not yet recommended for use in production wallets until peer-reviewed and tested by the Bitcoin dev community.

 # #🤝 Contributions Welcome

Native Venezuelans: Suggest word candidates.
Cryptographers: Review entropy model.
Developers: Add CLI tools and testing.

🌐 Learn more at: bitcoinforengineers.com/venezuelan-bip39

 # #📜 License: MIT

