# AriGraphExperiments

**Reproducing Key Components of "AriGraph: Learning Knowledge Graph World Models with Episodic Memory for LLM Agents"**
Note : This is an independent implementation. For official code, [see](https://github.com/AIRI-Institute/AriGraph).

---

## Overview  
This repository implements core components of the **AriGraph** framework, which enables LLM agents to build structured memory graphs combining *semantic knowledge* and *episodic experiences* for complex decision-making. The architecture is inspired by the paper's focus on text-game environments and multi-hop reasoning.  

---

## Features  
✅ **Implemented**:  


🚧 **Work in Progress**:  
- **Memory Graph**:  
  - Semantic nodes linked via knowledge graph embeddings
  - Episodic nodes with temporal context tracking
- **Planning Module**:  
  - Pathfinding in text-based environments (e.g., dungeon crawlers)
- **Environment Integration**:  
  - TextWorld compatibility for interactive game scenarios
- Full RL baseline comparisons
- Multi-hop QA benchmarks with knowledge graph queries

---

## Installation  


```bash
git clone https://github.com/glad4enkonm/AriGraphExperiments.git  
cd AriGraphExperiments  
pip install -r requirements.txt  
