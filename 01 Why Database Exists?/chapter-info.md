# Chapter 1: Why Databases Exist?

---

### 🧠 The Why?

Before diving into the real learning, you might have asked yourself — *“Why even study DBMS?”*

If you're a complete beginner, the name itself might sound self-explanatory:  
> **Database Management System** — a system that manages databases.

And that’s not wrong.

But let's go a little deeper.

You probably already know that **data is critical** — whether it's storing user information, transactions, sensor readings, or even Instagram likes. Every modern application we interact with is powered by a system that handles data in the background.

Now imagine this:

At a small scale, you might store data in spreadsheets, JSON files, or local logs. But what happens when:
- Thousands of users are reading/writing data simultaneously?
- You need to prevent data loss in case of failure?
- You want to allow multiple teams to work with the data securely?

This is where **DBMS steps in**.

It’s not just about storing data — it’s about managing it:
- **Efficiently**
- **Securely**
- **Consistently**
- **Scalably**

---
### 💡 The Bigger Software Picture

As Martin Kleppmann puts it in *Designing Data-Intensive Applications*, most modern systems need to prioritize:

1. **Reliability** – The system should work correctly even in the face of faults  
2. **Scalability** – It should handle increased load or volume gracefully  
3. **Maintainability** – Easy to evolve, debug, and understand over time  

A well-structured DBMS helps meet all three — making it one of the **core pillars of any serious software architecture**.

---


This chapter is here to help you understand:
- Why DBMS exists in the first place
- What problems it solves (compared to basic file systems)
- What kind of DBMS systems are out there
- Why this is the very foundation of backend and system design

Let’s begin with the problem DBMS was created to solve.
