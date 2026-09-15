# Festival Visitor Guide

## Student Information

- Name: [Mahawa Koroma]
- Course and section: [CSC350H 1300]
- Date: [09/13/2026]

## Repository Evidence

- Current branch: [main]
- Personal Homework 2 GitHub URL: [Repository URL: https://github.com/koromae/CSC350-HW2-YOUR-GITHUB-KOROMAE.git]
- Starting `git status`: [On branch main
nothing to commit, working tree clean]
- Starting preparation commit ID: [bd125dd]

## Festival Identity

- Festival name: [BMCC Summer Festival]
- Location: [199 Chambers St, New York, NY 10007]
- Intended audience: [Student, Alumni and families]
- Theme: [Celebrate the rich diversity of the BMCC community around fun summer activities and networking]

## Prediction Before the First Commit

1. Where does the saved change currently live?

   [The saved changes currently live in the working tree]

2. Has it been staged or committed?

   [No, the changes have not been staged nor committed yet]

## Arrival Information

- Transit or parking: [Take the 1,2,3,A,C,E trains to chambers street, the 4,5,6 to brooklyn Bridge and walk on Chambers street to get to the main building. You can also take the R,Q,W, and N train.]
- Entrance or meeting location: [Please enter via the main entrance on Chambers Street of the main building og BMCC at 199 Chambers St, New York, NY 10007]

## Accessibility Information

1. [The building has elevators and ramps for anyone to access]
2. [The campus will provide assistance and structured guidance to elder alumni for their smooth visit to their campus]

## Visitor Reminder

[Please bring a valid photo ID upon your arrival, for it is required to access the building]

## GitHub Verification

[Verified on Github by Mahawa Koroma]

## Commit Evidence

| Checkpoint | Short commit ID | Required message |
|---|---|---|
| Personalized guide | [f547b69] | `docs: personalize festival visitor guide` |
| Visitor access information | [a700d6c] |  |
| GitHub verification | [8b3585d] | `docs: verify independent homework on GitHub` |
| Final reflection | [8b3585d] | `docs: complete independent Git reflection` |

## Individual Reflection

1. What is the difference between saving a file and committing it?

   [When saving a file, the changes on that file will only be stored inside the working tree. Whereas, when we commit it, a permanent snapshot is recorded and stored on the local repository]

2. What is the difference between `git diff` and `git diff --staged`?

   [When the command “git diff” is run, it shows the changes that have been saved on the working directory but not in the staged area. Whereas, when running the command “git diff –staged”, all changes that have been staged but not committed will be shown.]

3. Why did the GitHub verification sentence not appear locally before `git pull`?

   [It did not appear locally because the changes have been done and committed on the remote repository only, making those changes visible remotely on Github only and not on the local repository. Git pull is the command that will synchronize the local repository with the remote one. It is only after running that command that the verification sentence will appear locally.]

4. What did `-u` accomplish in `git push -u origin main`?

   [It creates a permanent tracking link between the main branch of the local repository and the main branch of the remote repository]

5. What evidence proves that the local and GitHub repositories are synchronized at the end?

   [The evidence is found when running the command “git log -n 1”. This command will show the commitID of the last commit. When run, the Commit ID ​​”8b3585d” appears, matching with the commit ID of the last commit on the remote repository. This testifies that both repository are synchronized ]

