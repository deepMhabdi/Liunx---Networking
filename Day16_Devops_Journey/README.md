# Day 8: Process Management ⚙️

🚀 **Learn from doing** — today I explored how Linux manages **processes** behind the scenes.  

---

## 🖥️ Process Tools  

- **`ps`, `ps aux`** → List processes  
- **`top`** → Monitor system activity live  
- **`jobs`, `fg`, `bg`** → Manage background and foreground jobs  
- **`kill`, `pkill`** → Stop processes  

---

## 📂 Task of the Day  

- Started a background process with `sleep 100 &`  
- Verified it with `jobs` and `ps aux | grep sleep`  
- Killed it using `kill -9 <PID>`  
- Explored `top` to see resource usage  

💡 It felt like being a **traffic controller 🚦**, managing which processes run, pause, or stop.  

---

## ✨ Key Takeaway  

Linux gives precise control over processes, which is **crucial for troubleshooting and resource management**.  
