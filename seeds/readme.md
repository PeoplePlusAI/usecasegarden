# Guidelines for Creating Seeds  

Welcome to the **Seeds** folder! This is where your ideas for solving real-world problems take root. Follow these guidelines to architect impactful, scalable, and frugal solutions aligned with the philosophy of Use Case Garden.

---

## **1. Choose a Use Case That Excites You**  
Head over to the [Use Case Garden](https://pplus.ai/usecasegarden) and find a use case that resonates with you. Passion drives innovation – pick something that makes you eager to dive in.

---

## **2. Follow the Guidelines**  
Before you start, revisit the [architecting guidelines](../README.md) to ground your approach in practicality, +1 thinking, frugality, and transparency. These principles will shape your solution into something meaningful and adaptable.

---

## **3. Architect the Use Case**  
Once you’ve chosen your use case, follow these steps to design your solution:  

### **Step 1: Rewrite the Problem Statement from a Technical POV**  
- Reframe the problem in terms of technical challenges and constraints.  
- Example:  
   **Original Problem**: "Potholes on city roads are a big issue."  
   **Technical POV**: "Design a system to detect and classify potholes using image recognition on low-cost edge devices."  

### **Step 2: Propose Your Solution**  
- Describe your solution clearly and concisely. What are you building?  
- Include details like system architecture, user workflows, and key functionalities.  
- Example:  
   "The proposed solution involves using edge devices mounted on public buses to collect road condition data via cameras. Images will be processed locally to detect potholes using TensorFlow Lite, with results uploaded to a central database for analysis and action."

### **Step 3: Suggest Tech Stack, Technologies, and Project Flows**  
- Provide a detailed breakdown of the tools, libraries, and frameworks you plan to use.  
- Outline the project flow – from data collection to deployment.  
- Example:  
   - **Tech Stack**: TensorFlow Lite, Raspberry Pi, OpenCV  
   - **Project Flow**:  
     1. Image capture on edge devices  
     2. Local processing to detect potholes  
     3. Periodic data upload to a central database  
     4. Visualization dashboard for city authorities  

### **Step 4: Argue the Whys**  
For each decision, explain **why** you’ve chosen this approach based on the guidelines:  
- **Why this solution?** (Practicality and +1 thinking)  
- **Why this tech stack?** (Frugality and scalability)  
- **Why this project flow?** (Transparency and adaptability)  

Example:  
- **Why TensorFlow Lite?** It’s optimized for edge devices, ensuring low power and cost efficiency.  
- **Why this architecture?** It minimizes bandwidth usage, making it suitable for urban and rural deployments.  

---

## **The Tone: Playful, Curious, Inclusive**  
Your seed submission doesn’t have to sound like a PhD thesis. Keep it approachable, creative, and aligned with our mission: **to make AI that works for real people in real places.**

Imagine you’re presenting this to your friends at a chai stall – clear, conversational, and engaging.  

---

## **Final Notes**  
Once your seed is ready:  
1. Submit it as a markdown file in this folder.  
2. Ensure it includes all the sections described above.  
3. Open a pull request and tag someone from the core team for review.  

---

Let’s grow impactful solutions together, one seed at a time! 🌱
