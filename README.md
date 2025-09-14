# Anoma Intent Refill Demo

A simple prototype showing how **intent-centric design** can improve the onboarding UX in Web3.

---

## 🎯 Idea

One of the most frustrating moments in Web3 is landing on a new chain with an empty wallet.  
You have funds elsewhere, but without gas you can’t move.  

This demo shows how intents can solve that:

1. User declares: *“Send me 0.01 ETH on Arbitrum so I can start using it.”*  
2. The app looks at your assets (e.g. USDC on Ethereum).  
3. Solver finds the best route (swap + bridge under the hood).  
4. Wallet gets refilled automatically.  

From the user’s side: no begging for gas, no juggling bridges, no wasted time.  
Just **intent → action → done**.

---

## 🛠️ How it works

- Frontend mock built with HTML/CSS/JS.  
- “Generate Intent” button creates a JSON-like intent request.  
- “Solver Proposal” shows how a solver could resolve the request.  
- It’s only a demo — no real swaps or bridges are executed.  

---

## 🚀 Try it live

**Demo:** https://anoma-intent-refill.vercel.app/
**Repo:** https://github.com/tada2k/anoma-intent-refill-demo-tada2k/

---

## ✨ Credits

- Author: tada2k  
- X: [@QuocTin92322](https://x.com/QuocTin92322)  
- Discord: tada2k#0373 

Built for **Anoma Intents Refill** to demonstrate the power of intent-centric UX.
