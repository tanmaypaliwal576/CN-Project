<h1 align="center">Selective Repeat ARQ Simulator</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Networking-Selective%20Repeat%20ARQ-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Protocol-Simulator-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" />
</p>

---

## 🚀 Live Demo  
https://selectiverepeatarq.vercel.app/

---

## 🧠 What Is Selective Repeat ARQ?

Selective Repeat ARQ is a reliable data transfer protocol used in computer networks.  
It improves efficiency by retransmitting **only the specific lost or corrupted packets**, rather than the entire window.

This simulator visually demonstrates:
- Sender & Receiver sliding windows  
- Packet transmission  
- Packet loss & ACK loss  
- Timer expirations and selective retransmissions  
- Out-of-order packet buffering  

---

## 🎯 Features

- Real-time sliding window animation  
- Simulate packet & ACK loss  
- Timer-based retransmissions  
- Receiver-side buffering  
- Clear visualization of network reliability mechanisms  
- Easy and interactive UI for learning  

---

## 🛠️ Tech Stack

<p>
  <img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
</p>

---

## 📘 How It Works

### **Sender Window**
Tracks:
- Packets sent  
- Packets acknowledged  
- Packets awaiting timeout  

### **Receiver Window**
Handles:
- In-order delivery  
- Buffering out-of-order packets  
- Delivering only when expected sequence arrives  

### **Timer & Retransmissions**
Each packet has its own timer.  
Only packets that time out get retransmitted.

### **Loss Simulation**
You can toggle:
- Packet Loss  
- ACK Loss  

This helps visualize real-world network failures.

---

## 📌 Use Cases

### **1. Education & Learning**
Perfect for students learning computer networks and reliability protocols.

### **2. Lab Demonstrations**
Teachers can use it to explain ARQ mechanisms visually.

### **3. Debugging Conceptual Understanding**
Helps learners test protocol logic through interactive examples.

### **4. Portfolio & Resume Project**
Shows strong understanding of:
- Networking fundamentals  
- Sliding window mechanisms  
- Error handling logic  

### **5. Research & Experimentation**
Can be extended for:
- Delay simulation  
- Error-rate testing  
- Comparison with Go-Back-N ARQ  

---

## 📂 Project Structure

```
/assets
  /css
  /js
index.html
README.md
```

---

## 🤝 Contributing  
Pull requests are welcome.  
Feel free to open issues or suggest improvements.

---

## 📚 License  
This project is open-source under the MIT License.
