---
layout: archive
title: ""
permalink: /projects/
author_profile: true
---

# Projects

### GPU HW & SW Optimizations

Guide: Prof. Hyesoon Kim, CS8803 - GPUs, Fall '25

* Optimized CUDA kernels for tiled matrix multiplication and bitonic sort using shared & pinned memory, tiling, loop unrolling, kernel fusion & fission, async operations, memory transfer, etc.
* Implementing CUDA kernels for Softmax, GEMM, and Multi-head attention to achieve an LLM inference pipeline having FlashAttention2 support, optimized with KV-cache for token times

### Array Bounds Check Optimizer

Guide: Prof. Santosh Pande, CS6291 - Advanced Compilers, Spring '25

* Developed LLVM compiler passes to eliminate redundant checks and improve runtime by ∼20%
* Applied Gupta’s algorithm for redundancy removal via check splitting and selective elimination
* Implemented ABCD algorithm for JIT applications and check removal by graph-based algorithms

### Securing Computer Systems

Guide: Prof. Ahamad Mustaque, CS6238 - SCS, Spring '25

* Implemented a trusted computing base (TCB) and memory protection, reducing flaws by 40%
* Designed and deployed authentication and access control, improving security enforcement by 35%

### A survey of various Erasure Coding Schemes

Guide: Prof. Jun Xu, CS7260 - Network Algorithmics Course Project, Fall '24

* We translated the implementations of Raptor and LT codes into Python and compared their performance on a random set of files on simulated noisy channels

### Secure Multiparty Computation and ZK-SNARK applications

Guide: Prof. Manoj Prabhakaran, CS758 - Advanced Tools from Modern Cryptography Course Project, Fall '23

* Explored the problem of function characterization for SMPC under honest majority assumptions
* Delved into the complexities of Zero-Knowledge Succinct Non-Interactive Argument of Knowledge (ZK-SNARK) exploring applications in network security, identifying potential areas for improvement

### [iplC : Miniature GCC-like C Compiler](https://github.com/calcudexter/iplC)

Guide: Prof. Amitabha Sanyal, CS302 - Implementation of Programming Languages Course Project, Spring '23

* Effectively implemented a Flex scanner for precise language token recognition and smoothly integrated a Bison script, enforcing comprehensive syntactical checks, with a lexical analyzer
* Incorporated various essential components into the compiler for a holistic and enhanced performance, including type verification, semantic checks, overload resolution, and Abstract Syntax Tree generation
* Built a stack-offset-based Symbol Table, proficiently produced Assembly code, and rigorously verifying against a standard compiler, ensuring the accuracy and reliability of the generated code

### [Advanced Databases with Functional Dependencies](https://github.com/calcudexter/fdpgsql)

Guide: Prof. S Sudarshan, CS387 - Database and Information Systems Course Project, Spring '23

* Developed a database system including features to declare functional dependencies across relations
* Significantly improved system functionality by introducing a user-friendly terminal interface, enabling clients to easily interact with the database via simplified SQL queries, enhancing the user experience
* Developed a query processor that efficiently extracts identifiable fragments, executes commands, and delivers the requested data, leading to faster management and streamlined data retrieval

### [Blockchain Simulator](https://github.com/aka2910/P2P-selfish-mining)

Guide: Prof. Vinay Ribeiro, CS765 - Blockchains, Cryptocurrencies and Smart Contracts Course Project, Spring '23

* Implemented a discrete-event simulator for P2P crypto network utilizing SimPy, using Proof-of-Work
* Simulated selfish & stubborn mining attacks varying the mining power, bandwidth, and delays
* Constructed a D-App in Solidity for a pool of users and simulated transactions among users via BFS

### [Virtual FMX World Animation](https://github.com/calcudexter/cg-assgn3)

Guide: Prof. Parag Chaudhuri, CS475 - Computer Graphics Course Project, Fall '22

* Created a 3D voxel modeling tool, with adjustable resolution and save-load capabilities from scratch
* Designed a virtual FMX world encompassing rider, bike, tracks, obstacles, and adaptable skin support
* Elevated the artificial environment with illumination modeling, object collisions, and keyboard control
* Unified all essential elements for fast animation via script with linear and angular interpolation

### Joint Audio-Visual Deepfake detection

Guide: Prof. Preethi Jyothi, CS753 - Automatic Speech Recognition Course Project, Spring '22

* Extensively studied, implemented, and parallelly trained the model from Facebook’s ICCV ’21 paper
* Implemented Late fusion and 2+1 Stream fusion algorithms on visual and audio stream features
* Exploited out-of-sync audio-visual Mel spectrograms for increased detection accuracy using attention

### Multilingual Speech Recognizer

Guide: Prof. Preethi Jyothi, CS753 - Automatic Speech Recognition Course Project, Spring '22

* Trained tied-state triphone HMMs using Kaldi toolkit to transcribe speech samples in Wolof language
* Implemented text-to-speech synthesizer with SoX CLI using concatenative synthesis on transcripts
* Fine-tuned the pipeline for STT & TTS on Marathi & Kannada languages via Python-Coqui

### [Peer-to-Peer File Sharing Application](https://github.com/calcudexter/tcp_file_sharing)

Guide: Prof. Kameswari Chebrolu, CS252 - Computer Networks Course Project, Spring '22

* Created a 100% reliable peer-to-peer network software using C++ socket programming libraries
* Devised multiple error handling strategies ensuring smooth sharing with no data loss at the receiver

### [RISC 16 Bit Processor in VHDL](https://github.com/ojaswijain/CS230_Project)

Guide: Prof. Virendra Singh, CS 230 - Digital Logic Design and Computer Architecture Course Project, Spring '22

* Coded an efficient finite state automaton for a processor with predefined functionality using VHDL
* Tested the architecture with a python wrapper for assembly translation and testbench in Quartus