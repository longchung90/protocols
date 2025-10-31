# GitHub Upload Checklist

This is a reusable protocol for adding new files (like notebooks) to any GitHub repository.

---

## 1. Navigate to your repository
```bash
cd ~/Documents/GitHub/<repo_name>
```

---

## 2. Organize files (optional)
Create a folder if needed:
```bash
mkdir notebooks
```

Move the file into that folder:
```bash
mv ~/Downloads/my_file.ipynb notebooks/
```

---

## 3. Stage changes
```bash
git add notebooks/my_file.ipynb
```
Or stage all changes:
```bash
git add .
```

---

## 4. Commit changes
```bash
git commit -m "Add notebook for JavaScript practice"
```

---

## 5. Push to GitHub
```bash
git push origin main
```

---

## 6. Verify on GitHub
- Go to your repository page on GitHub.
- Confirm the file appears under the correct folder.
- For `.ipynb` files, GitHub provides a nice notebook preview.

---

✅ You now have a consistent protocol to follow whenever you add files to GitHub.
