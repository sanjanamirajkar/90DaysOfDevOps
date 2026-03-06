# Day 26 – GitHub CLI: Manage GitHub from Your Terminal

## Task 1: Install and Authenticate
1. Install the GitHub CLI on your machine
2. Authenticate with your GitHub account
3. Verify you're logged in and check which account is active

4. Answer in your notes: What authentication methods does `gh` support?
    - Web browser or personal access token
     
 <img width="1161" height="226" alt="Screenshot 2026-03-06 135002" src="https://github.com/user-attachments/assets/be846ec1-e836-4697-931b-dd3375cb4760" />

---

## Task 2: Working with Repositories
1. Create a **new GitHub repo** directly from the terminal — make it public with a README
2. Clone a repo using `gh` instead of `git clone`
3. View details of one of your repos from the terminal
4. List all your repositories
5. Open a repo in your browser directly from the terminal
6. Delete the test repo you created (be careful!)

<img width="1087" height="482" alt="Screenshot 2026-03-06 140020" src="https://github.com/user-attachments/assets/81b8be6a-d718-49d4-a073-709027f581c1" />

<img width="1919" height="398" alt="Screenshot 2026-03-06 140154" src="https://github.com/user-attachments/assets/f748bcff-188c-47f5-90e8-b40f37ca00ef" />

<img width="1164" height="121" alt="Screenshot 2026-03-06 141352" src="https://github.com/user-attachments/assets/c11c02f0-6126-4704-ba14-43950d38ec76" />

---

## Task 3: Issues
1. Create an issue on one of your repos from the terminal — give it a title, body, and a label
2. List all open issues on that repo
3. View a specific issue by its number
4. Close an issue from the terminal

5. Answer in your notes: How could you use `gh issue` in a script or automation?
    * By combining gh issue commands in a script, you can automate workflows such as:
      - gh issue list
      - gh issue comment <issue num>
      - gh issue close <issue num>

<img width="924" height="427" alt="Screenshot 2026-03-06 142021" src="https://github.com/user-attachments/assets/d7a339c8-5874-4016-bd5c-3dcb9122fa5c" />


---

## Task 4: Pull Requests
1. Create a branch, make a change, push it, and create a **pull request** entirely from the terminal
2. List all open PRs on a repo
3. View the details of your PR — check its status, reviewers, and checks
4. Merge your PR from the terminal

<img width="1915" height="687" alt="Screenshot 2026-03-06 142824" src="https://github.com/user-attachments/assets/fab28e12-1e9c-4485-a3c6-229b99abc4aa" />
<img width="966" height="276" alt="Screenshot 2026-03-06 143011" src="https://github.com/user-attachments/assets/24325c0f-640c-4903-9dd8-54342b26d800" />

5. Answer in your notes:
   - What merge methods does `gh pr merge` support?
      * merge commit
      * rebase merge
      * squash merge
   - How would you review someone else's PR using `gh`?
      * `gh pr view --web`
      * `gh pr review <pr-num> --approve`

---

## Task 5: GitHub Actions & Workflows (Preview)
1. List the workflow runs on any public repo that uses GitHub Actions
2. View the status of a specific workflow run

3. Answer in your notes: How could `gh run` and `gh workflow` be useful in a CI/CD pipeline?
    * They allow you to automate workflows without interactive sessions, making it easy to trigger, monitor, 
     and manage GitHub Actions directly from scripts or automation tools.

<img width="1691" height="667" alt="Screenshot 2026-03-06 143620" src="https://github.com/user-attachments/assets/40528e40-2389-4b58-b715-46e7d0989aec" />

---













