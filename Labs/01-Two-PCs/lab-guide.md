# 🖥️ Lab 01: Connecting Two PCs  

## 🎯 Objective  
Learn how to connect two PCs in Cisco Packet Tracer using a simple LAN setup and test communication.

## 📌 Steps  

1️⃣ **Open Cisco Packet Tracer**  
2️⃣ **Drag & Drop Two PCs** from the device list  
3️⃣ **Connect the PCs using a Cross-over Cable**  
   - Click the **Connections** tool  
   - Select **Copper Cross-over** cable  
   - Connect **PC1 FastEthernet0 → PC2 FastEthernet0**  
4️⃣ **Assign IP Addresses:**  
   - PC1: **10.10.10.1**  
   - PC2: **10.10.10.2**  
5️⃣ **Test the Connection:** 
   - Open PC1’s Command Prompt  
   - Run `ping 10.10.10.2`  
   - If successful, you will see replies!  

## ✅ Expected Output  
- The two PCs should be able to **ping each other successfully**  

## 🔍 Troubleshooting  
- If ping fails, check:  
  - **Cable Type:** Should be cross-over  
  - **IP Configuration:** Run `ipconfig` to verify  
  - **Interface Status:** Should be **Up**  
