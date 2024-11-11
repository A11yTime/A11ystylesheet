# Add the upstream remote if not done yet
git remote add upstream https://github.com/original-owner/original-repository.git

# Fetch the upstream changes
git fetch upstream

# Switch to your main branch
git checkout main

# Merge upstream changes into your local branch
git merge upstream/main

# Resolve any merge conflicts, if necessary
git add <resolved-file>
git commit -m "Resolved conflicts and merged upstream changes"

# Push changes to your fork
git push origin main
