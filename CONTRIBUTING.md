\# Contributing to Nevora Insights



\## Branch Strategy



The `main` branch must always contain stable and working code.



Do not push directly to `main`.



Create a branch for every task:



\- `feature/...` - New functionality

\- `fix/...` - Bug fixes

\- `refactor/...` - Code restructuring

\- `test/...` - Testing and evaluation

\- `docs/...` - Documentation

\- `chore/...` - Project configuration



Examples:



\- `feature/document-parser`

\- `feature/drive-sync`

\- `feature/dashboard`

\- `test/retrieval-evaluation`



\## Development Workflow



1\. Update local `main`.

2\. Create a new branch.

3\. Implement one focused task.

4\. Test the changes.

5\. Commit the changes.

6\. Push the branch.

7\. Create a Pull Request.

8\. Request at least one review.

9\. Merge after approval.

10\. Delete the feature branch after merging.



\## Commit Convention



Use the following prefixes:



\- `feat:` New feature

\- `fix:` Bug fix

\- `test:` Testing

\- `docs:` Documentation

\- `refactor:` Code restructuring

\- `chore:` Configuration or maintenance



Examples:



`feat: add document parser`



`fix: handle empty pdf`



`test: add retrieval evaluation cases`



`docs: update architecture`



\## Pull Request Rules



Every Pull Request should explain:



\- What was changed?

\- Why was it changed?

\- How was it tested?



Do not merge unfinished or untested work into `main`.



\## Important



Never commit:



\- API keys

\- Passwords

\- `.env` files

\- Real company documents

\- Sensitive personal information

