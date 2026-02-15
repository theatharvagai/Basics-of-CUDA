# ⚡🚀 CUDA Parallel Computing & GPU Programming

### 🧠 High-Performance Computing using CUDA Kernels & Tiled Matrix Multiplication

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=28&duration=3000&color=00E0FF&center=true&vCenter=true&width=1000&lines=CUDA+Parallel+Computing;GPU+Kernel+Programming;High+Performance+Matrix+Multiplication;Shared+Memory+Optimization" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-NVIDIA%20CUDA-green?style=for-the-badge&logo=nvidia" />
  <img src="https://img.shields.io/badge/Language-C%2FC%2B%2B-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Domain-High%20Performance%20Computing-purple?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Parallelism-GPU%20Computing-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Concept-Shared%20Memory-red?style=for-the-badge" />
</p>

---

# 📌 Project Overview

This repository contains implementations of **GPU Parallel Programming using NVIDIA CUDA**, focusing on high-performance computation through kernel optimization, unified memory, and shared memory tiling techniques.

The project demonstrates how large-scale computations can be accelerated using GPU architectures instead of traditional CPU-based sequential execution.

---

# 🧠 Core Concepts Implemented

* CUDA Kernel Programming
* Thread & Block Hierarchy
* Unified Memory Management
* Shared Memory Optimization
* GPU vs CPU Performance Comparison
* Parallel Array Operations
* Tiled Matrix Multiplication

---

# 🏗️ System Architecture

```
CPU (Host)
     ↓
Memory Allocation (Unified / Device Memory)
     ↓
CUDA Kernel Launch <<<Grid, Block>>>
     ↓
Parallel Execution on GPU Threads
     ↓
Synchronization & Result Verification
     ↓
Performance Metrics (Execution Time & GFLOPs)
```

---

# ⚙️ Implemented CUDA Modules

## 1️⃣ Parallel Array Operations (Menu-Driven CUDA)

* Element-wise Addition Kernel
* Element-wise Subtraction Kernel
* Element-wise Multiplication Kernel
* Unified Memory Allocation (`cudaMallocManaged`)
* GPU Synchronization (`cudaDeviceSynchronize`)

Handles large arrays (1M+ elements) efficiently using GPU threads.

---

## 2️⃣ Tiled Matrix Multiplication (Shared Memory Optimization)

* 1024 × 1024 Matrix Multiplication
* Shared Memory Tiling Technique
* Reduced Global Memory Access
* CUDA Events for Kernel Timing
* Performance Analysis using GFLOPs

Optimized for high computational throughput on GPU.

---

# 🔥 Key Features

⚡ High-Speed Parallel GPU Execution
🧮 Large-Scale Matrix Computation (CUDA)
🧠 Shared Memory Tiling Optimization
📊 Kernel Performance Timing & Benchmarking
🔁 Menu-Driven CUDA Kernel Operations
🚀 Efficient Memory Management (Unified Memory)
🧪 CPU Verification for Correctness

---

# 🧩 Execution Pipeline

```
Input Data → Memory Allocation → CUDA Kernel Launch
           → Parallel GPU Computation → Synchronization
           → Result Copy to Host → Verification & Performance Analysis
```

---

# 🛠️ Tech Stack

| Category       | Technology                       |
| -------------- | -------------------------------- |
| Language       | C / C++ (CUDA C)                 |
| GPU Framework  | NVIDIA CUDA                      |
| Parallel Model | Grid-Block-Thread Architecture   |
| Optimization   | Shared Memory & Unified Memory   |
| Tools          | NVCC Compiler, CUDA Runtime      |
| Domain         | High Performance Computing (HPC) |

---

# 📂 Project Structure

```
📁 CUDA-Parallel-Computing
 ┣ 📄 menu_driven_cuda.cu        # Array operations using CUDA kernels
 ┣ 📄 tiled_matrix_mul.cu        # Tiled matrix multiplication (Shared Memory)
 ┣ 📄 cuda.ipynb                 # Colab execution notebook
 ┗ 📄 README.md                  # Documentation
```

---

# 🚀 How to Compile & Run

## 🔹 Compile using NVCC

```bash
nvcc menu_driven_cuda.cu -o menu_cuda
./menu_cuda
```

## 🔹 Run Tiled Matrix Multiplication

```bash
nvcc tiled_matrix_mul.cu -o tiled_matrix_mul
./tiled_matrix_mul
```

> Ensure CUDA Toolkit and NVIDIA GPU drivers are properly installed.

---

# 📊 Performance Highlights

* Massive speedup over CPU execution
* Efficient parallel execution using thousands of GPU threads
* Optimized global memory access via shared memory tiling
* GFLOPs calculation for performance benchmarking

---

# 🎯 Academic & Industry Relevance

* High Performance Computing (HPC)
* Parallel Computing
* GPU Acceleration
* Scientific Computing
* AI/ML Infrastructure Optimization

---

# 🔮 Future Improvements

* CUDA Streams for Asynchronous Execution
* Multi-GPU Parallelization
* Tensor Core Optimization
* Integration with Deep Learning Workloads
* Benchmark comparison with OpenMP & CPU

---

# 👨‍💻 Author

**Atharva**
M.Tech CSE | VIT Vellore
HPC • CUDA • Parallel Computing • Systems Programming

---

# ⭐ Final Note

This project showcases practical implementation of **GPU-accelerated parallel computing using CUDA**, highlighting kernel optimization, memory management, and high-performance matrix computation techniques used in modern AI and scientific computing systems.
