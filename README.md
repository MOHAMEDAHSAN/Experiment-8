### Name : S Mohamed Ahsan
### Reg No : 212223240089

# Experiment-8

### Aim
Study the system specifications of an ATM system and report any identified bugs.

### Purpose
The **purpose** of an ATM system is to allow customers of financial institutions to perform financial transactions such as cash withdrawal, deposit, balance inquiry, and fund transfer without the need for direct interaction with bank staff

### Scope
The **scope** covers transaction processing at banking kiosks or standalone machines for a range of functions including withdrawal, deposit, balance check, funds transfer, statement printing, and bill payments. It also includes security, maintenance, and software integration with banking networks.

### Intended Audience
The main **intended audience** consists of bank customers seeking quick access to their accounts, banks and their IT departments, ATM manufacturers, and software developers responsible for ATM interfaces and network security.

### Product Perspective
The ATM system acts as a **client** in a distributed banking network, communicating with the backend bank server and other intermediaries through secure channels. It serves as part of the overall banking infrastructure alongside mobile and web banking

### Product Functions
Key **functions** of an ATM include:
- Cash withdrawal
- Deposits (cash/cheque)
- Balance inquiry
- Fund transfer between accounts
- Printing of transaction receipts
- Language and accessibility support
- Account statement and passbook updates
- Bill payments and third-party payments (sometimes)

### Operating Environments
ATMs typically operate on specialized embedded operating systems, connected via secure telecommunications to the bank’s central servers. They must withstand diverse physical conditions, including variable temperatures, humidity, and lighting in indoor and outdoor settings.

### Design/Implementation Constraints
Typical constraints include:
- Compliance with banking security standards (PCI DSS, EMV etc.)
- Reliability in power and connectivity fluctuations
- Limited hardware interfaces (screen, keypad, card reader, cash/receipt dispenser)
- Customer privacy and security
- Device durability for public use

### Assumptions and Dependencies
- Users possess a valid ATM/debit card and PIN.
- Backend bank server remains online and responds promptly.
- ATM hardware is regularly maintained.
- Secure communication channels between ATM and bank

### Some of the Possible Bugs on ATM Machine

- **Hardware Malfunctions:** Card reader failing, cash dispenser jams, printer paper out, display issues.
- **Software Glitches:** System freeze, transaction errors, incorrect balance updates, duplicate transactions.
- **Security Concerns:** Skimming device detection failures, vulnerabilities to malware or unauthorized physical access.
- **Operational Bugs:** Withdrawal or transfer amount limits not enforced, incorrect receipt printing, mishandling invalid PINs or cards.
- **Network Issues:** Poor connectivity leading to failed or stuck transactions, timeout errors in communication with the banking server.

### Result
The ATM system’s specification covers a wide array of features, but careful review is necessary to prevent and address common bug categories—hardware, software, security, and network—to provide a seamless banking experience.

This summary provides an organized breakdown matched to the structure of the Experiment- specification and highlights real-world ATM issues.
