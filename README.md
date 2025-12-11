# Team Python Assignment

This repository holds Python assignment workflow where each team member works independently in their own branch. The `master` branch is protected and managed by the admin.

---

## Quick overview
- The admin publishes one or more tasks (as markdown files) in `master`.
- Each member implements the task in their personal branch.
- Do not merge member branches into `master` — `master` is admin-managed.

---

## Task files (naming convention)
- Tasks are provided as markdown files in `master` and use a numbered naming convention:
  - `task1.md`, `task2.md`, ...
- The admin will indicate which task(s) to complete. If multiple task files exist, follow the admin's instruction about which one to work on (for example, "Complete task2.md").
- Starter code, if any, will be provided alongside the task file or referenced inside the task markdown.

---

## Repository layout (example)
- master/                → Admin only (README & task files like `task1.md`, `task2.md`)
- shubham-saini/             → Member branch
- prachi-singh/
- mancie-barla/
- naresh-rawat/
- md-alimullah/
- mohit-cheepa/
- aditya-pareek/
Each member has one branch. Keep branches separate — no cross-branch edits or merges.

---

## Branch rules & permissions

Main branch (`master`)
- Managed only by the admin.
- Members must not push, edit, or merge into `master`.

Member branches (example: `shubham-saini`)
- Push and work only in your own branch.
- Do not push to other members’ branches.
- Do not create merges/PRs between member branches.
- Do not create new branches without admin approval.

Note: GitHub may not technically enforce all restrictions on free plans. These rules are mandatory; the admin will revert mistakes.

---

## How to submit your solution

1. Clone the repository
```bash
git clone https://github.com/shubham-saini18/DS-python-AU.git
cd DS-python-AU
```

2. Get the latest branches and switch to your branch
```bash
git fetch --all
# If the branch already exists locally:
git checkout <your-branch>
# If the branch exists only on origin:
git checkout -b <your-branch> origin/<your-branch>
```
Example for Shubham:
```bash
git fetch --all
git checkout shubham-saini
```

3. Add your solution
- Complete the specified task (e.g., `task1.md`) and add your code and any supporting files in your branch.
- Recommended file naming for clarity (optional):
  - Script: `task1_solution.py` or `task1_shubham.py`
  - Notes or explanation: `task1_shubham.md`

4. Commit and push
```bash
git add .
git commit -m "Assignment submission: task1 - <brief description>"
git push origin <your-branch>
```

---

## Rules summary (must follow)
- Do NOT push anything to `master`
- Do NOT edit another member’s branch
- Do NOT merge branches or create PRs between member branches
- Do NOT create new branches without admin approval

Admin will revert mistakes if rules are broken.

---

## Admin responsibilities
- Protect and maintain `master`
- Publish and update task files (`task1.md`, `task2.md`, ...)
- Create member branches
- Review submissions and reset incorrect commits when needed

---

## Purpose & benefits
This workflow keeps the repository:
- Clean and conflict-free
- Easy to review per-person work
- Fair and consistent for evaluation

If you have questions about which task to complete or branch permissions, contact the admin before making changes.
Happy coding — good luck!
