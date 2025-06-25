# 🧠 LRU Cache Visualizer

An advanced **Data Structures & Algorithms (DSA)** project demonstrating the **Least Recently Used (LRU) Cache** strategy with optimal time complexity and a modern, interactive GUI built with **Streamlit**.

---

## 📌 Overview

This project simulates an **efficient LRU cache** using a queue-based approach that ensures **O(1) time complexity** for both insertion and retrieval. The user-friendly **Graphical User Interface (GUI)** allows dynamic interaction, while real-time **matplotlib** visualizations showcase hit and miss ratios, making the learning experience both intuitive and insightful.

---

## ✨ Key Features

* ⚡ **Optimized LRU cache** using queue and hashing techniques
* ⏱️ **Constant-time complexity** for key cache operations
* 🖥️ **Interactive GUI** via Streamlit for seamless simulation
* 📊 **Matplotlib bar graphs** displaying:

  * Hit ratio
  * Miss ratio
* 📈 **Real-time metrics dashboard** with statistics like:

  * Total hits and misses
  * Hit and miss percentages

---

## 🧮 How It Works

The LRU cache internally uses a queue (e.g., `collections.deque`) to track access order. Here's the logic:

* 🔁 When a page is accessed:

  * **Cache Hit**: Move the item to the front of the queue
  * **Cache Miss**: Evict the least recently used item if cache is full, then insert the new item
* 📥 Users can enter custom cache sizes and page reference strings
* 📊 Visuals and metrics update live in the GUI for each run

---

## 🛠️ Tech Stack

| Layer         | Tools Used               |
| ------------- | ------------------------ |
| Language      | Python                   |
| Interface     | Streamlit                |
| Visualization | Matplotlib               |
| Logic Core    | Queues, Hashing (Python) |

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/yourusername/lru-cache-visualizer.git
cd lru-cache-visualizer

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit application
streamlit run app.py
```

