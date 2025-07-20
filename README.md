## 📌 Abstract

This project explores the application of **blockchain technology** to build a secure, transparent, and verifiable **electronic voting system**. It proposes a decentralized system that ensures:
- Voter privacy
- End-to-end verifiability
- Tamper-proof vote recording  
Blockchain's **peer-to-peer structure** and **cryptographic verification** make it a promising foundation for national-level e-voting systems. The implementation uses **encrypted vote tokens**, client-server communication, and real-time broadcasting of blocks.

---

## 🧠 Motivation

Blockchain emerged from the 2009 financial crisis via Bitcoin. It provides a decentralized, transparent, and trustless environment. Applying blockchain to voting can eliminate:
- Centralized tampering
- Vote duplication
- Lack of trust in traditional e-voting systems

---

## 🔬 Literature Survey

Several papers and systems (e.g., FollowMyVote, BitCongress) explored blockchain-based voting. Key findings:
- Blockchain supports immutability and decentralization
- It ensures one person = one verifiable vote
- Token-based voting using distributed ledgers enables secure audit trails

---

## 🛠️ Methodology

### ✔️ Key Components:
- **Main Class:** Starts the server or client node; manages communication.
- **Block Class:** Stores encrypted voter ID, name, and choice; includes hash linking for security.
- **Client Manager:** Handles user input, socket communication, and local blockchain file generation.
- **Server Manager:** Accepts and manages multiple voting clients and incoming blocks.
- **Message Struct:** Defines message types (broadcast, vote, client ID) between nodes.
- **Network Layer:** Handles message parsing and data routing in P2P network.

### 🔁 Flow:
1. Server starts and waits for clients (voting machines).
2. Clients connect and cast encrypted votes.
3. Server broadcasts new blocks to all clients.
4. Clients update local blockchain and store vote securely.

---

## 🧪 Results

- Successfully broadcasted votes from server to all connected clients.
- Vote tallying and verification were demonstrated.
- Clients displayed real-time voting status.
- Disconnection handling and data consistency were tested.

---

## 📈 Figures

### 🖥️ Vote Casting on Voting Machine  
<img width="670" height="652" alt="image" src="https://github.com/user-attachments/assets/b32e3d2d-d258-4209-ae98-0254bb87b073" />


### 🔁 Server Broadcasting Block to Clients  
<img width="1046" height="430" alt="image" src="https://github.com/user-attachments/assets/84346e47-64cd-466a-b17f-0f626428cb36" />


---

## 📦 Technologies Used

- **Language:** Java  
- **Concepts:** Blockchain, Cryptography, Socket Programming  
- **Architecture:** P2P Client-Server  
- **Tools:** Java Serialization, Threading, File I/O

---

## 🔒 Conclusion

E-voting using blockchain can solve trust issues in electoral systems. This project shows a working simulation using basic cryptography and P2P broadcast to:
- Ensure vote immutability
- Prevent tampering or vote manipulation
- Support disconnected clients
Although blockchain has current limitations, it's a powerful candidate for future secure voting systems.

---

## 📚 References

1. Ahram et al., "Blockchain Technology Innovations", IEEE TEM Conference, 2017.  
2. R. Chatterjee et al., "Overview of Emerging Blockchain Technology", CINE, 2017.  
3. Vujičić et al., "Blockchain, Bitcoin, and Ethereum Overview", INFOTEH, 2018.  
4. Tasatanattakool & Techapanupreeda, "Blockchain Challenges and Applications", ICOIN, 2018.

---

## 📝 License

This project is for academic purposes only. All rights reserved by the authors and institution.

