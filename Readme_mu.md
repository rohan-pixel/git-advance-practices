## 🚀 Git Repository Setup & Cleanup Guide

If you accidentally committed `node_modules` or are preparing your project for the first push, follow these steps to clean the repo and set it up correctly.

---

### **📦 1. Remove `node_modules` from Git tracking**

```bash
git rm -r --cached node_modules
```

---

### **📁 2. Re-add all files except ignored ones**

```bash
git add .
```

---

### **🧹 3. Commit cleanup changes**

```bash
git commit -m "Clean repo by removing node_modules and updating .gitignore"
```

---

### **✏️ 4. Update `.gitignore`**

Manually edit your `.gitignore` file to ensure unwanted files/folders are excluded.

*No command required.*

---

### **📜 5. Stage the updated `.gitignore` and other files**

```bash
git add .gitignore
git add .
```

---

### **📌 6. Create initial commit (if not created earlier)**

```bash
git commit -m "Initial project setup with folder structure, charts, utilities, assets and improved README"
```

---

### **🌐 7. Add remote GitHub repository**

```bash
git remote add origin <your-repo-url>
```

---

### **⬆️ 8. Push to the `main` branch**

```bash
git branch -M main
git push -u origin main
```

---
