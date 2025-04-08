![image](https://github.com/user-attachments/assets/19e6f058-3e60-44a6-8a73-b7460258cc69)
⚖️ Proof of Justice (PoJ)

📌 NFT-Based Decentralized Legal Record System
Proof of Justice (PoJ) is a decentralized application (DApp) that revolutionizes legal transparency. It tokenizes court judgments as NFTs, ensuring they are immutable, tamper-proof, and permanently accessible through the Ethereum blockchain and IPFS.

🚀 What Happens When a Judgment Is Uploaded?
User Inputs Metadata: Court name, region, case type, judge’s name, and author.
PDF Upload: The legal judgment document is uploaded by the admin.
Pinning to IPFS: The PDF is stored using Pinata, generating an immutable IPFS CID.
Metadata Packaging: The PDF link + metadata is compiled into a JSON object and pinned to IPFS.
NFT Minting: The IPFS metadata link is embedded in a smart contract and minted as an ERC-721 NFT.
Access & Verification: Anyone can verify the authenticity by viewing the NFT and its associated IPFS metadata.
🛠 Tech Stack
Frontend: HTML, CSS, JavaScript
Smart Contracts: Solidity (ERC-721 Standard)
Blockchain: Ethereum (Sepolia Testnet)
Wallet: MetaMask
IDE: Visual Studio Code
Smart Contract Deployment: Remix IDE
Decentralized Storage: IPFS (via Pinata)
Blockchain Interaction: Web3.js
⚙ Tools & Dependencies
Solidity: Smart contract development
Remix IDE: Compile & deploy contracts
MetaMask: Wallet for user authentication and transactions
Web3.js: Frontend ↔ blockchain communication
Pinata SDK: Upload files & metadata to IPFS
Visual Studio Code: Frontend development
OpenZeppelin: ERC-721 base contracts and access control
✨ Features
✅ Tokenize legal judgments as NFTs
✅ Upload and pin judgment PDFs to IPFS
✅ Mint NFTs to legal authorities or parties
✅ Verify authenticity and ownership on-chain
✅ View case metadata and PDF files via frontend
✅ Secure, transparent, tamper-proof recordkeeping
✅ Only admin/authorized users can mint/update NFTs

🔁 Workflow
User Uploads Case Details → 
PDF is uploaded to Pinata → 
IPFS hash returned → 
Metadata + hash pinned as JSON → 
NFT minted with metadata link → 
Verification via NFT & IPFS
🧪 Testing & Deployment
Contracts written in Solidity using Remix IDE
Blockchain transactions done via MetaMask on Sepolia Testnet
Files & metadata uploaded to IPFS using Pinata
Frontend connects to smart contract using Web3.js
📂 How to Run This Project
Clone the Repository
git clone https://github.com/your-username/proof-of-justice.git
cd proof-of-justice
Install dependencies (if applicable)
npm install
Connect MetaMask
Switch MetaMask network to Sepolia Testnet
Get free test ETH from https://sepoliafaucet.com
Deploy Smart Contract
Open PoJ.sol in Remix IDE
Compile & deploy using Injected Web3 (MetaMask)
Run Frontend
Open index.html in browser
Use UI to input metadata, upload PDF, and mint NFT
🎥 Demo & Slides
YouTube Video: https://www.youtube.com/watch?v=Toi6KhHg5Q4
Canva Presentation: https://www.canva.com/design/DAGkDQi93CQ/CSPy23C-ePGl62iKp3sAgg/edit?utm_content=DAGkDQi93CQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton 
![image](https://github.com/user-attachments/assets/aa794cb7-a6ff-4324-a10b-36774c1092f4)
![image](https://github.com/user-attachments/assets/99bf1507-89a0-442d-bbb0-75e8668bca4d)


👨‍💻 Authors
Vighnesh B – https://www.linkedin.com/in/vighnesh-b-b9391b291/
Keerthana Sai Gazula – https://www.linkedin.com/in/keerthana-sai-gazula-4013b927a/
📄 License
This project is licensed under the MIT License. Feel free to fork and build upon it.
