# Team Collaboration

## Branches
- main: shared working baseline
- feature/name: new features
- fix/name: bug fixes
- chore/name: setup and maintenance

## Workflow
1. git switch main
2. git pull --ff-only
3. git switch -c feature/your-feature
4. Make and test changes.
5. Commit and push your branch.
6. Open a pull request.
7. Merge after review.

## Team rules
- Assign ownership of features before coding.
- Use pull requests to merge into main.
- Communicate changes to shared APIs and data models.
- Avoid force-pushing shared branches.
- Keep API credentials out of Git.
- Keep the demo working throughout the event.
