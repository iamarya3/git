# Initialize a new Git repo (only if not already initialized)
git init

# Create and switch to a new branch
git checkout -b feature-1

# Create a new file and add content
echo "This is a new feature" > feature.txt

# Stage and commit the file
git add feature.txt
git commit -m "Add feature.txt in feature-1 branch"

# Switch back to main branch
git checkout main

# Merge the feature-1 branch into main
git merge feature-1
