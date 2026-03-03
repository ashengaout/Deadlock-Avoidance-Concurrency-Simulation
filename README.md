## 🍝 **Deadlock Avoidance & Concurrency Simulation**

A Java-based implementation of the Dining Philosophers problem. This project focuses on managing thread synchronization and resource contention using Semaphores.

### 🚀 **Features**
🧵 **Multithreading:** Models philosophers as independent concurrent threads.


🔒 **Semaphore Synchronization:** Uses java.util.concurrent.Semaphore to manage mutually exclusive access to shared resources (forks).

🛡️ **Deadlock Prevention:** Implements an asymmetric resource acquisition strategy to break the "Circular Wait" condition.

📂**Data Parsing:** Dynamically reads process metadata (PID, Arrival, Burst) from an external process.txt file.

### 🛠️ **Technical Implementation**
To prevent a system-wide deadlock, the implementation forces the final philosopher to request resources in the opposite order of their peers. This ensures that at least one philosopher can always eat, preventing a total circular stall.

### 🏗️ **Tech Stack**

**Language:** Java 

**Concurrency Tools:** java.util.concurrent.Semaphore, Thread

**Concepts:** Multithreading, Deadlock Avoidance, Synchronization

**Environment:** Developed as part of Operating Systems Graduate Coursework in Computer Science
