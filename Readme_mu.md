# 1. Remove node_modules from Git tracking (if mistakenly added)
```git rm -r --cached node_modules```

# 2. Re-add everything except ignored files
```git add .```

# 3. Commit changes
```git commit -m "Clean repo by removing node_modules and updating .gitignore"```

# 4. Update .gitignore (manual edit)
```# (No command — you edited the file)```

# 5. Stage updated .gitignore and other changes
```git add .gitignore```
```git add .```

# 6. Create initial commit (if not created earlier)
```git commit -m "Initial project setup with folder structure, charts, utilities, assets and improved README"```

# 7. Add remote GitHub repo
```git remote add origin <your-repo-url>```

# 8. Push to main branch
```git branch -M main```
```git push -u origin main```
