# Assignment 4 - Git Repository with Meaningful Commits

Is assignment mein aapko ek Git repository banani hai aur usmein kam se kam teen (3) meaningful commits karne hain, jisse aapke code ke alag-alag versions saaf-saaf dikhein.

## Commands Reference

| # | Task | Command | Description |
|---|---|---|---|
| 1 | Initialize repository | `git init` | Naya Git repository shuru karne ke liye |
| 2 | Create initial HTML file | `touch index.html` | Pehli HTML file banane ke liye |
| 3 | First Meaningful Commit | `git add index.html` <br> `git commit -m "feat: add initial HTML structure"` | Pehla commit structure ke liye |
| 4 | Create CSS file | `touch style.css` | Styling file add karne ke liye |
| 5 | Second Meaningful Commit | `git add style.css` <br> `git commit -m "style: add basic CSS styles"` | Doosra commit styling ke liye |
| 6 | Create README file | `touch README.md` | Documentation file ke liye |
| 7 | Third Meaningful Commit | `git add README.md` <br> `git commit -m "docs: add project description in README"` | Teesra commit docs ke liye |
| 8 | View commit history | `git log --oneline` | Sabhi commits ko ek line mein check karne ke liye |

## Practice Exercise
Apne terminal ya Git Bash mein neeche diye gaye steps ko follow karein:
1. Ek naya folder banakar usme `git init` run karein.
2. `index.html` file banayein aur use stage karke pehla commit karein.
3. `style.css` file banayein aur doosra meaningful commit karein.
4. `README.md` file banayein aur teesra meaningful commit karein.
5. `git log --oneline` command se apne teeno commits verify karein.

## Answers

```bash
git init
touch index.html
git add index.html
git commit -m "feat: add initial HTML structure"
touch style.css
git add style.css
git commit -m "style: add basic CSS styles"
touch README.md
git add README.md
git commit -m "docs: add project description in README"
git log --onelines