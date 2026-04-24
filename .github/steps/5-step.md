## Step 5: Recover safely with revert

A teammate reports that one checklist item is incorrect. You need to undo the bad change without rewriting history.

### 📖 Theory: Revert creates a safe undo commit

Revert creates a new commit that undoes a previous commit safely.

- Revert preserves history instead of deleting it.
- Revert is safer than rewriting history on shared branches.
- Teams use revert to fix mistakes quickly while keeping an audit trail.

Read more:

- [About commits](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits)
- [About distributed version control](https://docs.github.com/en/get-started/using-git/about-git#distributed-version-control)

### ⌨️ Activity: Revert a mistaken commit on main

1. On main, add this incorrect line under the onboarding checklist and commit it:

   ```md
   - Rule 3: Force-push directly to main.
   ```

1. Find that new commit in history.
1. Use GitHub to revert that commit.
1. Confirm there is now a new revert commit in main history.
1. Open `handbook.md` and verify the incorrect line is gone.

<details>
<summary>Having trouble? 🤷</summary><br/>

- Ensure you are reverting the commit that introduced the incorrect line, not the earlier merge commit.
- If revert creates a pull request in your repository settings, merge that pull request to complete the revert.

</details>
