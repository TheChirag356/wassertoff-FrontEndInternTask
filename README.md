# FrontEndInternTask – Wasserstoff Frontend Developer Internship

This repository contains the completed tasks for the Wasserstoff Frontend Developer Internship Assignment. The repository integrates two separate Git submodules:

- **Task 1**: Real-Time Collaborative Editor
- **Task 2**: Component Library SDK

---

## 🔗 Live Links

- **Task 1 (Collaborative Editor)**: [Live Demo](https://realtime-texteditor-sooty.vercel.app/)
- **Task 2 (Component Library SDK)**: [Live Demo](https://my-component-library-three.vercel.app/)

> 💡 Each task is self-contained and lives in its respective submodule.

---

## 📁 Repository Structure

```bash
FrontEndInternTask/
├── RealTimeEditor/        # Task 1: Real-Time Collaborative Editor
├── ComponentLibrary/      # Task 2: Component Library SDK
└── README.md              # This file
```

## Setup Instructions
Clone this repository along with submodules:

```bash
git clone --recurse-submodules https://github.com/chirag-arora/wasserstoff.git
cd wasserstoff/FrontEndInternTask
```

Or if already cloned:

```bash
git submodule update --init --recursive
```

## To run each task:
### Task 1 – Real-Time Collaborative Editor

```bash
cd RealTimeEditor
npm install
npm run dev
```
Visit http://localhost:3000 in multiple tabs to test collaboration features.


### Task 2 – Component Library SDK

```bash
cd ComponentLibrary
npm install
npm run dev
```
View component usage and demo pages at http://localhost:3000.


## Video Explanation

A short video explaining my approach, decisions, and architecture for both tasks is included in the submission email.
