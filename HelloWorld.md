## This is a markdown file

install.packages("gert")
library(gert)
git_status()
git_add(".")  # stages all new/modified files
git_commit("Resolve merge conflicts")  # only if conflicts existed
git_commit("Add initial project files") # Commit changes
git_push() # Push to GitHub
git_push(force = TRUE)