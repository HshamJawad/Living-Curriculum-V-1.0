# Living Curriculum Prototype

## Overview
This repository hosts an **experimental prototype** exploring the concept of a **Living Curriculum** for TVET and competency-based training.

Instead of treating curricula as static documents (PDFs, manuals, printed activity sheets), this prototype demonstrates how an **Activity Sheet** can become an interactive, learner-involved, and AI-supported learning artifact.

This is **not a finished product**, but a **concept demonstration** intended to provoke discussion, experimentation, and feedback from curriculum developers, trainers, and TVET practitioners.

---

## Core Idea: Living Curriculum
A *Living Curriculum* maintains a **stable competency structure** (tasks, steps, performance criteria) while adding a **dynamic interaction layer** that supports:

- Visualization before practice  
- Learner participation  
- Reflection against performance criteria  
- Contextual adaptation during training delivery  

The goal is **augmentation**, not replacement, of curriculum design expertise.

---

## What the Prototype Demonstrates

### 1. AI-Supported Visual Learning
- Each activity step can generate a contextual illustration.
- Images help learners understand procedures, tools, posture, and safety **before execution**.
- Image generation is currently implemented using a **free, no-API image service** (for MVP testing only).

### 2. Guided Regeneration
- Trainers or learners can add **guidance text** (e.g., tools, PPE, environment).
- Images can be regenerated to better match correct practice.
- This reinforces *procedural accuracy* rather than decorative visuals.

### 3. Learner as Co-Constructor
- Learners are not passive content consumers.
- They interact with steps, visuals, and criteria.
- The curriculum adapts during delivery, not only during design.

### 4. Performance-Criteria-Based Self-Check
- Each step is linked to performance criteria.
- Learners perform a structured self-check:
  - readiness
  - safety awareness
  - procedural correctness
- Feedback is rule-based at this stage (no paid AI services).

### 5. Image Persistence
- Selected images can be saved per activity step.
- Saved visuals reload automatically on page refresh.
- This simulates *approved instructional visuals* for repeated use.

---

## Technology Stack (Intentionally Simple)
- HTML / CSS / Vanilla JavaScript
- No backend required for the current prototype
- No API keys required
- Designed to run locally or via GitHub Pages

> The focus is **pedagogical feasibility**, not platform complexity.

---

## Intended Audience
- TVET curriculum developers  
- Competency-based training designers  
- DACUM facilitators  
- Trainers and instructors  
- Education and training researchers  

---

## Current Status
- Functional prototype
- Focused on concept validation
- Not intended for production or large-scale deployment
- Open for experimentation and critique

---

## Limitations (By Design)
- AI-generated images are approximate, not authoritative
- Visuals must always be validated against standards and safety regulations
- The image service used is **not suitable for commercial or high-volume use**
- No formal assessment or certification logic implemented

---

## Disclaimer
This prototype is provided **“as is”** for educational and demonstration purposes only.

The author assumes no responsibility for:
- misuse of generated content
- unsafe application of illustrated procedures
- compliance with local regulations or standards

Users must always validate training materials with qualified professionals and applicable occupational standards.

This project is **not affiliated with or endorsed by any organization**, unless explicitly stated.

---

## Feedback and Contributions
Feedback, critique, and discussion are welcome—especially from practitioners working in:
- TVET
- Competency-Based Training (CBT)
- Curriculum design and reform

This repository is shared to encourage **informed dialogue**, not to promote a finished solution.

---

## Author
Developed as an exploratory prototype by a TVET curriculum practitioner with experience in:
- DACUM methodology
- Competency-based training
- Curriculum and training material design
- Emerging applications of AI in education

---

## Next Possible Directions
- AI-generated formative questions per step
- Short procedural video generation
- Institution-ready backend integration
- Versioning and curriculum lifecycle tracking

These are **future considerations**, not current claims.
