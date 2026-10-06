<h1 align="center">Hi 👋, I'm Satyam Kesharwani</h1>
<h3 align="center">Backend & Systems Engineer · C++, distributed systems, databases · NIT Kurukshetra 2027</h3>

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=22&duration=3000&pause=1000&color=A855F7&center=true&vCenter=true&width=700&lines=Building+High+Performance+Systems;Distributed+Systems+Enthusiast;Turning+Ideas+Into+Scalable+Software" alt="Building high-performance systems" />

<p align="center">
  <a href="https://www.satyamk.dev">
    <img src="https://img.shields.io/badge/✨_Visit_My_Portfolio-satyamk.dev-0e75b6?style=for-the-badge" alt="Visit my portfolio at satyamk.dev" />
  </a>
  <a href="https://www.satyamk.dev/blog">
    <img src="https://img.shields.io/badge/📝_Engineering_Blog-7_deep_dives-a855f7?style=for-the-badge" alt="Read my engineering blog" />
  </a>
</p>

</div>

I build backend and systems software from scratch: a **distributed key-value database in C++17**, a **URL shortener with multi-layer caching**, and **custom memory allocators** for an order matching engine. I'm a final-year B.Tech Computer Engineering student at **NIT Kurukshetra** (CGPA 8.88/10) with **two published research papers** (Springer ICDAM 2025, IEEE NE-IECCE 2026).

> **Open to work:** a 6-month internship from **January 2027** and full-time roles after graduating in May 2027 · Bangalore, Hyderabad, remote, or anywhere in India · 📫 **stym4193@gmail.com** · [LinkedIn](https://www.linkedin.com/in/stym01/) · [Resume](https://www.satyamk.dev/resume)

---

# 👨‍💻 About Me

```ts
const satyam = {
  education: "B.Tech Computer Engineering @ NIT Kurukshetra (2023–2027)",

  interests: [
    "Systems Engineering",
    "Distributed Systems",
    "Database Internals",
    "Backend Architecture"
  ],

  currentlyLearning: [
    "Database Internals",
    "Distributed Systems Design",
    "Kubernetes",
    "Large Scale Infrastructure"
  ]

};
```

### 🚀 Quick Facts
- 💻 **Building high-performance systems from scratch:** C++ databases, custom allocators, distributed caching and ML pipelines.
- ⚔️ **LeetCode Knight:** max rating 1908 (top ~5%), 660+ problems solved.
- 📜 **Published researcher:** lead author at ICDAM 2025 (Springer), second author at NE-IECCE 2026 (IEEE).
- 🏆 **Amazon ML Challenge 2026:** rank 313 of 26,636 teams · **Amazon ML Summer School 2025:** selected.
- ⚡ **Fun fact:** If you ever feel useless, think about the guy who writes Terms & Conditions.

---

### 🔥 Featured Projects

- **[AtomicKV: Distributed Key-Value Database](https://github.com/stym01/AtomicKV)** · C++17, Linux epoll, B-Tree, gossip  
  A production-grade distributed database built from scratch on a single-threaded Linux epoll event loop: an LRU cache with a Bloom filter in front of an on-disk B-Tree, a consistent hash ring with virtual nodes, gossip failure detection, async replication with read repair and anti-entropy, and Lamport clocks for last-write-wins. **10,000+ req/s at ~16 ms** average latency with 200 concurrent clients.  
  📝 Write-ups: [the storage engine](https://www.satyamk.dev/blog/atomickv-key-value-store-cpp-epoll-btree) · [the distributed layer](https://www.satyamk.dev/blog/atomickv-distributed-consistent-hashing-gossip-replication)

- **[Shortify: URL Shortener with Multi-Layer Caching](https://github.com/stym01/Distributed-url-shortener-with-multi-layer-caching-and-rate-limiting)** · Node.js, Redis, PostgreSQL, Docker, AWS  
  In-process LRU and Redis caches over PostgreSQL (**7.12 ms** average redirects), a Redis Bloom filter against cache penetration, a `SET NX` lock against cache stampedes, Snowflake IDs in Base62 and a token-bucket rate limiter; Docker on AWS EC2 via GitHub Actions.  
  📝 Write-up: [URL shortener system design, built and measured](https://www.satyamk.dev/blog/url-shortener-system-design-redis-postgresql-caching)

- **[Custom Memory Allocators & Order Matching Engine](https://github.com/stym01/Custom-Allocator-HFT-Engine)** · C++17  
  Linear, Stack, Pool and Free-List allocators written from scratch and used by a price-time-priority limit order book, so the matching path never calls `new`/`malloc`. Pool **~2.5×** and linear **~15×** faster than glibc `new`/`delete` (1M ops, median of 7 runs).  
  📝 Write-up: [custom allocators and a fair benchmark](https://www.satyamk.dev/blog/building-hft-engine-cpp)

- **[RansomDroid: Android Ransomware Detection](https://github.com/stym01/Android-Ransomware-Detection-Using-Deep-Learning-ViT_CNN)** · PyTorch, Vision Transformer, CuckooDroid  
  A Vision Transformer on images built from sandbox behaviour reports of 4,280 Android apps: **99.78% accuracy**. *(Lead author, ICDAM 2025, Springer)*  
  📝 Write-up: [from behaviour to pixels](https://www.satyamk.dev/blog/android-ransomware-detection-vision-transformer)

- **[SOC & SOH Estimation with TinyML](https://github.com/stym01/Iot-Project)** · ESP32, PyTorch, Edge Impulse EON  
  An offline battery monitor on an ESP32 with a physics-informed neural network (**R² = 99.70%**), compressed to INT8 C++; Virtual Cranking and Vampire Drain alerts. *(Second author, NE-IECCE 2026, IEEE)*  
  📝 Write-up: [physics-informed TinyML on an ESP32](https://www.satyamk.dev/blog/tinyml-esp32-battery-soc-soh-physics-informed-neural-network)

- **[Chatur: RAG Assistant for PDFs](https://github.com/stym01/Chatur-AI_Powered_PDF_Conversational_Assistant)** · LangChain, FAISS, Gemini, Streamlit  
  📝 Write-up: [building a RAG PDF assistant](https://www.satyamk.dev/blog/rag-pdf-assistant-langchain-faiss-gemini)

---

### 💻 Tech Stack

**Languages:**  
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

**Backend & Systems:**  
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)

**Databases:**  
![PostgreSQL](https://img.shields.io/badge/postgresql-4169e1?style=for-the-badge&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

**Machine Learning & Data:**  
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

---

### 🏆 Achievements & Publications

- **Amazon ML Challenge:** rank 313 of 26,636 teams (2026); rank 2,313 of 19,556 teams (2025).
- **Amazon ML Summer School 2025:** selected for Amazon India's machine learning program.
- **LeetCode Knight:** max rating 1908 (top ~5%); global rank 412 of 35,968 in Weekly Contest 497.
- **Hackathons:** led a 4-member team to 3rd place among 515 teams at Excalibur 2025; Grand Finalist (top 11 of 206) at Case on Point 2025.
- **Publications** · [Google Scholar](https://scholar.google.com/citations?user=5rIeQGYAAAAJ) · [ORCID](https://orcid.org/0009-0003-0908-5055)
  - [*From Behavior to Pixels: A Vision Transformer Approach for Android Ransomware Detection*](https://link.springer.com/chapter/10.1007/978-3-032-03072-6_11) · **ICDAM 2025 (Springer LNNS)** · lead & corresponding author
  - [*SOC and SOH Estimation of Lead-Acid Battery using IoT and Residual-Physics Neural Network*](https://ieeexplore.ieee.org/abstract/document/11665960) · **NE-IECCE 2026 (IEEE)** · second author

---

## 📈 GitHub Insights

<div align="left">

### 📊 GitHub Stats
[![Satyam's GitHub statistics showing commits, PRs, and contributions](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=stym01&theme=radical)](https://github.com/stym01)

### 🔥 Contribution Streak

[![GitHub contribution streak statistics](https://streak-stats.demolab.com/?user=stym01&theme=radical&hide_border=true)](https://github.com/stym01)

<a href="https://github.com/stym01">
  <img alt="Profile view counter" src="https://komarev.com/ghpvc/?username=stym01&color=blueviolet&style=flat-square&label=Profile+Views" />
</a>

</div>
