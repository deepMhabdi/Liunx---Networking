# Day 18: File Permissions Deep Dive 🔐

🚀 **Learn from doing** — today was about going **beyond basic chmod** and exploring advanced permission concepts.  

---

## 🖥️ Advanced Permission Tools  

- **`chmod u+s`** → setuid (run with owner’s permissions)  
- **`chmod g+s`** → setgid (inherit group ID)  
- **`chmod +t`** → sticky bit (only owner can delete in shared dir)  
- **`ls -ld`** → Verify special bits  

---

## 📂 Task of the Day  

- Created a folder `shared_dir` and added a sticky bit (`chmod +t`)  
- Verified with `ls -ld shared_dir` → saw the **`t`** at the end  
- Tried `setuid` and `setgid` on files and directories  
- Observed how permissions changed in `ls -l`  

💡 It felt like unlocking **hidden superpowers 🦸** of Linux file permissions.  

---

## ✨ Key Takeaway  

Special permissions (`setuid`, `setgid`, `sticky bit`) are widely used in real systems like `/tmp` — **mastering them is key for secure multi-user environments**.  
