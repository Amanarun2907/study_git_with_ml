Aman jain

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git remote -v
origin  https://github.com/Amanarun2907/study_git_with_ml.git (fetch)
origin  https://github.com/Amanarun2907/study_git_with_ml.git (push)

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        aman.docx

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git add .

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git restore --staged "aman.docx"

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        aman.docx

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git reset "aman.docx"

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        aman.docx

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git add .

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   aman.docx


C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git diff --staged
diff --git a/aman.docx b/aman.docx
new file mode 100644
index 0000000..e69de29
<aman.docx> does not seem to be a docx file!

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git commit -m "this is my new document commit"
[main 5e2fe36] this is my new document commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 aman.docx

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git diff --staged

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 252 bytes | 126.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Amanarun2907/study_git_with_ml.git
   a7e8f98..5e2fe36  main -> main

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git branch
* main

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git branch aman

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git branch
  aman
* main

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git checkout aman
Switched to branch 'aman'

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git branch
* aman
  main

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git status
On branch aman
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        aman1.docx

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git add .

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git commit -m "this is the new story i am working as a developer"
[aman 3d0c5c9] this is the new story i am working as a developer
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 aman1.docx

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git branch
  aman
* main

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git merge aman
Updating 5e2fe36..3d0c5c9
Fast-forward
 aman1.docx | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 aman1.docx

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 258 bytes | 258.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Amanarun2907/study_git_with_ml.git
   5e2fe36..3d0c5c9  main -> main

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>git log
commit 3d0c5c90375fb5b0543244d52c3ca43c88586d3b (HEAD -> main, origin/main, aman)
Author: Amanarun2907 <aman29.10.2004@gmail.com>
Date:   Tue Jul 15 13:28:19 2025 +0530

    this is the new story i am working as a developer

commit 5e2fe36f8ae45ceec1291ae8f38a1cbe85e9c68b
Author: Amanarun2907 <aman29.10.2004@gmail.com>
Date:   Tue Jul 15 13:24:52 2025 +0530

    this is my new document commit

commit a7e8f981cec2b483b8bfda61f9085b86edb862a7
Author: Amanarun2907 <aman29.10.2004@gmail.com>
Date:   Tue Jul 15 13:00:05 2025 +0530

    done

commit 2f2124a489bf287409647a583928a1b8e4364c27
Author: Amanarun2907 <aman29.10.2004@gmail.com>
Date:   Tue Jul 15 11:55:03 2025 +0530

    this is my commit

commit 71735054d584bdd0a56d9b346b45fe81203275c6
Author: Amanarun2907 <aman29.10.2004@gmail.com>
Date:   Mon Jul 14 17:37:47 2025 +0530


C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github> git log -p -3
commit 3d0c5c90375fb5b0543244d52c3ca43c88586d3b (HEAD -> main, origin/main, aman)
Author: Amanarun2907 <aman29.10.2004@gmail.com>
Date:   Tue Jul 15 13:28:19 2025 +0530

    this is the new story i am working as a developer

diff --git a/aman1.docx b/aman1.docx
new file mode 100644
index 0000000..e69de29
<C:\Users\aman2\AppData\Local\Temp/git-blob-a23112/aman1.docx> does not seem to be a docx file!

commit 5e2fe36f8ae45ceec1291ae8f38a1cbe85e9c68b
Author: Amanarun2907 <aman29.10.2004@gmail.com>
Date:   Tue Jul 15 13:24:52 2025 +0530

    this is my new document commit

diff --git a/aman.docx b/aman.docx
new file mode 100644
index 0000000..e69de29
<C:\Users\aman2\AppData\Local\Temp/git-blob-a23112/aman.docx> does not seem to be a docx file!

commit a7e8f981cec2b483b8bfda61f9085b86edb862a7
Author: Amanarun2907 <aman29.10.2004@gmail.com>
Date:   Tue Jul 15 13:00:05 2025 +0530


C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>

C:\Users\aman2\OneDrive\Desktop\ML\Complete-Data-Science-With-Machine-Learning-And-NLP-2024-main\Git And Github>