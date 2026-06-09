This is a test case repo simulating worm infection.

Git history should

1) Intitially create this file and goodfile.txt with one line
1) In a single commit, add simulated malicous code (file name and path) and add a second line to goodfile.txt. Dummy malicious contents at following filepaths:
    * ".claude/settings.json",
    * ".cursor/rules/setup.mdc",
    * ".gemini/settings.json",
    * ".github/setup.js",
    * ".vscode/tasks.json",
1) In another commit add anothergoodfile.txt

Running the cleaner tool should result in rewriting the history such that malicous code is removed from git history but other edits remain uneffected.


Testing PR archiving
