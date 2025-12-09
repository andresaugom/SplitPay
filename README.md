# SplitPay  
### HackMTY 2024 — 36-Hour Hackathon Project in Collaboration with **Capital One**

SplitPay is a proof-of-concept platform built during **HackMTY**, one of the largest hackathons in Latin America, developed in collaboration with **Capital One**.  
Its goal is simple: **make group payments effortless**. Instead of one person paying and everyone else reimbursing later, SplitPay lets users perform a **single shared transaction** and automatically divides the charge among multiple Capital One account holders.

This project was built under hackathon constraints and is not an official Capital One product.  
Both the frontend and backend repositories are provided below.

---

## What SplitPay Does

SplitPay enables:
- A **single payment** split across multiple user accounts.
- **Real-time coordination** between transaction participants.
- Clear visualization of who pays what and how the final charge is distributed.
- A straightforward experience for shared purchases: restaurants, travel, subscriptions, group outings, etc.

The system demonstrates how collaborative payments could be integrated into a banking ecosystem while keeping the user experience simple and reliable.

---

## System Architecture  
*(Diagrams will be added here)*  
> **[Space reserved for Architecture Diagram]**  
> **[Space reserved for Flow Diagram]**

---

## Tech Stack Overview

### **Frontend — SplitPay-F**
- **Next.js 15+**, **React 19+**
- **Material UI**
- **React Hook Form + Zod**
- **ApexCharts** (visualizations)
- **DayJS**
- **TypeScript**
- **Jest + Testing Library**

### **Backend — SplitPay-B**
- **Node.js (JavaScript)**
- **REST API**
- In-hackathon data storage (configurable: memory / mock DB)
- Designed to integrate with **Capital One’s transaction ecosystem**

---

## Repositories

### **Frontend (SplitPay-F)**
> UI for creating and managing split transactions  
➡️ https://github.com/andresaugom/SplitPay-F

### **Backend (SplitPay-B)**
> REST API powering the split-payment logic  
➡️ https://github.com/andresaugom/SplitPay-B

---

## Key Features

### Collaborative Payments  
Create a single transaction and automatically divide it among several users.

### Real-Time Synchronization  
Frontend and backend coordinate the creation, update, and finalization of split payments.

### Banking-Ready Flow  
Architecture designed to integrate with Capital One APIs.

### Hackathon-Focused  
Rapid prototyping, clean UX, and clear demonstration of group-payment feasibility.

---

## Getting Started

### Clone both repos:

```sh
git clone https://github.com/andresaugom/SplitPay-F.git
git clone https://github.com/andresaugom/SplitPay-B.git
````

### Run the frontend:

```sh
cd SplitPay-F
npm install
npm run dev
```

### Run the backend:

```sh
cd SplitPay-B
npm install
npm start
```

---

## Project Status

This is a **hackathon proof-of-concept**, built in 36 hours.
It is not a production system and does not represent an official Capital One product.

---

## License

Check each repository to see it's own license.

---

## Team & Credits

* Developed for **HackMTY 2025**
* Built in collaboration with **Capital One's hackathon program**

