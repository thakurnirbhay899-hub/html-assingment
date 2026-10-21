# Assignment 4 - Git Repository with Meaningful Commits

In this assignment, you need to create a Git repository and make at least three (3) meaningful commits showing different stages of your project[span_1](start_span)[span_1](end_span).

## Commands Reference

| # | Task | Command | Description |
|---|---|---|---|
| 1 | Initialize repository | `git init` | To start a new Git repository |
| 2 | Create initial HTML file | `touch index.html` | To create the first HTML file |
| 3 | First Meaningful Commit | `git add index.html` <br> `git commit -m "feat: add initial HTML structure"` | First commit for structure |
| 4 | Create CSS file | `touch style.css` | To add a styling file |
| 5 | Second Meaningful Commit | `git add style.css` <br> `git commit -m "style: add basic CSS styles"` | Second commit for styling |
| 6 | Create README file | `touch README.md` | For documentation |
| 7 | Third Meaningful Commit | `git add README.md` <br> `git commit -m "docs: add project description in README"` | Third commit for docs |
| 8 | View commit history | `git log --oneline` | To verify all commits in a single line |

## Practice Exercise
Run the following steps in your terminal or Git Bash:
1. Create a new folder and run `git init` inside it.
2. Create `index.html`, stage it, and make the first commit.
3. Create `style.css` and make the second meaningful commit.
4. Create `README.md` and make the third meaningful commit.
5. Verify all three commits using `git log --oneline`.

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
git log --oneline