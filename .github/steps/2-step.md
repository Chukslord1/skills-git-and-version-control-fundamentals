## Step 2: Create a branch for safe experimentation

You now need to draft onboarding rules, but you should avoid changing main directly.

### 📖 Theory: Branches isolate work

<!-- GitHub-styled notifications can be used outside of ordered lists. Available options are: NOTE, IMPORTANT, WARNING, TIP, CAUTION -->
<!--
> [!NOTE]
> (Important note or additional information relevant to this section)
 -->

Branches let you isolate work so unfinished changes do not affect stable content.

- main is typically the stable integration branch.
- A feature branch is a separate line of work for a specific task.
- You can compare branches before merging to validate changes.

Read more:

- [About branches](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches)
- [Git branches overview](https://docs.github.com/en/get-started/using-git/about-git#about-git-branches)

### ⌨️ Activity: Draft changes on a feature branch

1. Create a branch named `feature/onboarding-rules`.
1. On that branch, open `handbook.md` and add this section:

   ```md
   ## Onboarding checklist

   - Rule 1: Read the handbook and ask questions in your first week.
   - Rule 2: Open pull requests for all changes.
   ```

1. Commit your update to `feature/onboarding-rules`.
1. Open the compare view to review differences between `feature/onboarding-rules` and `main`.

<details>
<summary>Having trouble? 🤷</summary><br/>

- If commit options still show main, cancel and confirm branch creation completed first.
- Use the branch dropdown near the file view to verify you are editing `feature/onboarding-rules`.

</details>
