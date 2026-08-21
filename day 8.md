

# Git Branching: Hands-on Practice — Create, Switch, Commit & Push Assignments

---

### Assignment 1: Understanding Concepts

**Objective:** Check basic understanding of branching.

**Tasks:**
1. What is a **branch** in Git? Explain in your own words.
2. Why should we **not** work directly on the `main` branch?
3. Explain the road analogy of branching (main road vs side road).
4. What is the difference between `git branch` and `git switch`?

**Submission:** Written answers in your notebook.
<img width="2284" height="2213" alt="IMG_20260821_120336" src="https://github.com/user-attachments/assets/657766ef-f693-445e-9944-85f8fc73cddb" />

---

### Assignment 2: Commands Identification

**Objective:** Identify the correct commands.

**Tasks:**
1. Write the command for the following actions:

| Action                              | Command |
|-------------------------------------|---------|
| List all branches                   |         |
| Create a new branch named `feature-home` |    |
| Switch to `feature-home`            |         |
| Create + Switch in one command      |         |
| Merge `feature-home` into main      |         |
| Delete `feature-home` after merge   |         |

2. Write both the **modern** and **older** command for:
   - Switching to a branch
   - Creating + switching to a new branch

**Submission:** Filled table + answers
<img width="1872" height="952" alt="IMG_20260821_120402" src="https://github.com/user-attachments/assets/2f3ed341-1e99-480c-ac07-840c9e17a377" />
<img width="2328" height="565" alt="IMG_20260821_120440" src="https://github.com/user-attachments/assets/dea4a22c-23ae-4a5e-8423-4afc1fe0a9ea" />

---

### Assignment 3: Practical Branching Workflow

**Objective:** Perform the complete branching cycle.

**Tasks:**
1. Make sure you are on the `main` branch.
2. Create a new branch named `feature-contact`.
3. Create a file `contact.txt` and write your name + any message.
4. Stage and commit the file with a meaningful message.
5. Switch back to `main`.
6. Merge `feature-contact` into `main`.
7. Delete the `feature-contact` branch.
8. Verify using:
   - `git branch`
   - `git log --oneline`

**Submission:**  
- Screenshot of `git branch` (before and after)  
- Screenshot of `git log --oneline`  
- Screenshot showing `contact.txt` is present on `main`

---

### Assignment 4: Conceptual + Error Handling

**Objective:** Understand rules and common mistakes.

**Tasks:**
1. What will happen if you try to delete a branch that is not yet merged?  
   Write the error and how to fix it.
2. Why should you always **commit** before switching branches?
3. Fill in the correct flow:

```
create branch → Work → git add . → git commit -m" "→ Switch to main → merge branch → Delete branch
```

4. Explain the difference between:
   - `git branch -d branch-name`
   - `git branch -D branch-name`

**Submission:** Written answers
<img width="2329" height="1036" alt="IMG_20260821_120517" src="https://github.com/user-attachments/assets/a50733f5-a576-47ee-ad82-b4c96e61220a" />

---

### Assignment 5: Complete Real Scenario

**Objective:** Apply branching in a realistic situation.

**Scenario:**  
You are working on a website project. Currently you are on the `main` branch. You need to add two new pages: **About** and **Services**.

**Tasks:**
1. Create a branch `feature-about`, add a file `about.txt`, commit it, merge it into `main`, and delete the branch.
2. Create another branch `feature-services`, add a file `services.txt`, commit it, merge it into `main`, and delete the branch.
3. After completing both, show:
   - Final list of branches (`git branch`)
   - Final commit history (`git log --oneline`)
4. Answer:
   - Why did we create two separate branches instead of doing both features on one branch?
   - What is the advantage of merging only after the feature is complete?

**Submission:**  
- Screenshots of both merges  
- Final `git branch` and `git log --oneline`  
- Written answers for the two questions
<img width="2320" height="668" alt="IMG_20260821_120547" src="https://github.com/user-attachments/assets/4e70c61a-d808-4475-a919-686daecfedc0" />

---

### Deadline : 25th August, 2026.
