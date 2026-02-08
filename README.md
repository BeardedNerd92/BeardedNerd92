# Zack Grooms

Backend systems engineer focused on building from first principles:

- state
- invariants
- transactions
- idempotence
- correctness under retries

Currently building systems one feature at a time and documenting the process.

---

## Current Project

**Inventory System v2 — Django + SQLite**

Architecture:
transport → service → model → database

Focus areas:
- atomic state transitions  
- idempotent endpoints  
- invariant enforcement  
- retry-safe design  

State model:
S = Map[id → item]
item = { id, name, qty }
S' = f(S, input)

Implemented:
- POST /items  
- DELETE /items/<id> (idempotent)  

Next:
- atomic quantity updates  
- concurrency handling  

Repo:
https://github.com/BeardedNerd92/inventory-systemv2

---

## Engineering Log

I document daily system-building progress:

Dev log:  
https://dev.to/grooms_nicholas

LinkedIn:  
https://www.linkedin.com/in/zack-grooms/

Portfolio:
https://beardednerd92.github.io/Zack-grooms/

---

## Focus

Backend engineering  
Django  
System design fundamentals  
Correctness over complexity  

Building in public. One feature per day.
