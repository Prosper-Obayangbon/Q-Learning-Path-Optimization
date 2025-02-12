# 🤖 Q-Learning for Path Optimization in Grid World

This project implements **Q-learning**, a reinforcement learning (RL) algorithm, to optimize **pathfinding strategies** in a **static grid world**. The model enables an autonomous agent to **learn the shortest path to a goal** by interacting with the environment and improving its decision-making over time.

---

## 🚀 **Project Overview**  
- **Algorithm Used**: Q-Learning (Model-Free RL)  
- **Environment**: Custom **10x10 Grid World** with obstacles  
- **Agent's Goal**: Learn an optimal path from **start to goal**  
- **Learning Approach**: **ε-greedy policy** for exploration-exploitation balance  
- **Hyperparameters Tuned**: Learning rate, discount factor, exploration rate  
- **Performance Metrics**: Learning speed, path efficiency, reward accumulation  

---

## 📊 **Key Features & Insights**  

✅ **Q-Table Learning**  
- The agent **starts with no knowledge** and learns by updating Q-values using the **Bellman equation**  
- Q-table evolution demonstrates **improved decision-making over episodes**  

✅ **Path Optimization**  
- Early episodes involve **random exploration**, but the agent progressively learns to take **optimal routes**  
- The **final trained agent selects the shortest path consistently**  

✅ **Comparison with Baseline**  
- **Hyperparameter tuning improves performance**, reducing the number of steps required per episode  
- **Tuned Q-learning agent vs. Non-tuned agent**:  
  - **Tuned Agent**: Average reward **78.3**, Steps per episode **22.7**  
  - **Non-Tuned Agent**: Average reward **30.7**, Steps per episode **70.3**  

✅ **Statistical Validation**  
- **T-test results** show a **significant improvement** in agent performance after hyperparameter tuning  
- **P-value: 4.46 × 10⁻²³**, confirming a meaningful increase in rewards  

---

## 🛠 **Technologies & Tools Used**  
- **Python** for implementation  
- **NumPy** for matrix operations  
- **Matplotlib** for visualization (Q-table evolution, agent path trajectory)  
- **Reinforcement Learning (RL)** concepts  


---

## 🏗 **How to Run the Project**  

### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/yourusername/Q-Learning-Path-Optimization.git
cd Q-Learning-Path-Optimization
```

### **2️⃣ Install Dependencies**  
```bash
pip install numpy matplotlib
```

### **3️⃣ Run the Python Script**  
```bash
python q_learning_pathfinding.py
```

### **4️⃣ View Results**  
- The script will output **Q-table updates**, **path trajectories**, and **reward progress**  
- Graphs will display the **agent's learning process and optimized paths**  

---

## 📌 **Future Improvements**  
🔹 Implement **Deep Q-Learning (DQN)** for handling larger state spaces  
🔹 Extend to **dynamic environments** with real-time updates  
🔹 Integrate **multi-agent reinforcement learning** for collaborative navigation  

---

## 📧 **Contact & Contributions**  
📌 **Author**: Prosper Nosa Obayanbon  
📌 **Email**: obayangbonnosa@gmail.com

🙌 **Contributions are welcome!** Feel free to fork, modify, and submit pull requests.  


