<h1 align="center">Hi 👋, I'm Bartosz Szostakiewicz</h1>
<h3 align="center">🎓 Master's Student in Computer Science at ETH Zurich | BSc @ MIMUW</h3>

---


### 🌐 Connect with Me
<p align="left">
  <a href="https://www.linkedin.com/in/bartosz-szostakiewicz/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</p>

---

### 🧩 Featured Projects

#### 🐜 [Ant Colony Optimization for TSP (CUDA C++)](https://github.com/Bartekszost/ACO-TSP)
Parallel **Ant Colony Optimization (ACO)** algorithm for the **Travelling Salesman Problem (TSP)**, implemented fully in **CUDA**.  
The project explores GPU parallelism, shared memory optimization, and data-parallel algorithms inspired by *Cecilia & García (2012)*.

- 🚀 Implemented both **Worker Ant** and **Queen Ant** variants, leveraging **shared memory** and **prefix-sum (Blelloch) parallel reduction** for improved efficiency.  
- ⚙️ Used **atomic pheromone updates**, **CUDA Graphs**, and **curand** for reproducible stochastic behavior.  
- 📈 Achieved up to **3–5× faster execution** compared to the Worker baseline, with stable numerical results on large datasets (`rat783`, `pr1002`).  
- 🧪 Benchmarked on an **NVIDIA Titan V GPU cluster** with datasets up to 1000 cities.  

**Technologies:** CUDA, C++, GPU Programming, Parallel Reduction, Shared Memory Optimization  
**Paper:** [Enhancing Data Parallelism for Ant Colony Optimisation on GPUs (Cecilia & García, 2012)](https://doi.org/10.1016/j.jpdc.2012.01.002)

---

#### ⚙️ [Distributed SSSP – Δ-Stepping in MPI](https://github.com/Bartekszost/MPI-SSSP)
Implemented a **distributed Δ-Stepping algorithm** for the **Single Source Shortest Paths (SSSP)** problem using **MPI**.  
The project demonstrates scalability trade-offs in distributed-memory graph processing.

- 🧮 Designed an efficient **message-passing scheme** with `MPI_Alltoallv` for inter-process bucket synchronization.  
- ⚙️ Integrated **hybridization** and **edge classification** heuristics, yielding up to **20–50% performance gain** over the baseline.  
- 📊 Conducted **Δ-parameter tuning** and **weak scaling benchmarks** up to **80 MPI workers**, analyzing communication overhead and workload balance.  
- 🌐 Generated test graphs via **RMAT-1** and **RMAT-2** models, following *Chakaravarthy et al., “Scalable SSSP Algorithms for Massively Parallel Systems” (IPDPS 2014)*.  

**Technologies:** C++, MPI, Parallel Computing, High-Performance Benchmarking  
**Paper:** [Scalable Single Source Shortest Path Algorithms for Massively Parallel Systems (Chakaravarthy et al., 2014)](https://www.odbms.org/wp-content/uploads/2014/05/sssp-ipdps2014.pdf)

---

#### 🗺️ [MapReduce System (Kubernetes, Google Cloud, Java)](https://github.com/Bartekszost/MapReduce-System)
Designed and implemented a distributed **MapReduce system** deployed on **Google Cloud Kubernetes Engine (GKE)**.  
The project demonstrates the full workflow of scalable data processing — from local binaries to containerized orchestration.

- ⚙️ Implemented **Map**, **Partitioner**, **Combiner**, and **Reduce** stages as statically linked binaries, ensuring portability and performance.  
- 🐳 Containerized each component using **Docker**, and deployed them via **Kubernetes** manifests on **GKE**.  
- ☁️ Automated deployment using **Google Artifact Registry** and shell scripts (`build_docker.sh`, `deploy.sh`) for reproducible builds.  
- 🧩 Developed a **Java client** for orchestrating and monitoring distributed tasks through network communication with the master node.  
- 🧠 Explored distributed file partitioning, intermediate combining, and fault-tolerant reduce operations at cluster scale.  

**Technologies:** Java, C++, Docker, Kubernetes (GKE), Google Cloud Platform, Bash Automation  

---

#### ☁️ [Weather Map Application (React, Redux, TypeScript)](https://gitlab.mimuw.edu.pl/bs448513/waw-weather-app)
Interactive **Weather Map Web App** developed as part of the **Web Applications** course at **MIMUW**.  
Visualizes real-time weather and geospatial data using modern, reactive frontend architecture.

- 🌦️ Integrated **Overpass** and **Weather APIs** for dynamic map-based weather visualization.  
- 🔁 Utilized **Redux** and **Redux-Observable** for state management and asynchronous data flow.  
- 💨 Built a **responsive, TailwindCSS-based UI** focused on clarity and performance.  
- ⚡ Designed with modular architecture and component reusability for scalability.  

**Technologies:** React, TypeScript, Redux, Redux-Observable, TailwindCSS, API Integration  


---

### 🧰 Tech Stack

#### 💬 Languages
![C++](https://img.shields.io/badge/C++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/C-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0.svg?style=for-the-badge&logo=python&logoColor=ffdd54)
![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

#### 🧱 Frameworks & Libraries
![React](https://img.shields.io/badge/React-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Angular](https://img.shields.io/badge/Angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Flask](https://img.shields.io/badge/Flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![Django](https://img.shields.io/badge/Django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)

#### 🧠 AI / ML / Data Science
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

#### 🗄️ Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)

#### ☁️ DevOps & Tools
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab%20CI-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)

#### 🎨 Design & Others
![Figma](https://img.shields.io/badge/Figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![Adobe Photoshop](https://img.shields.io/badge/Photoshop-%2331A8FF.svg?style=for-the-badge&logo=adobephotoshop&logoColor=white)
![Adobe Premiere Pro](https://img.shields.io/badge/Premiere%20Pro-9999FF.svg?style=for-the-badge&logo=AdobePremierePro&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-%23008080.svg?style=for-the-badge&logo=latex&logoColor=white)
