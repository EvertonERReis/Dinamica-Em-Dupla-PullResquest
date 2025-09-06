# "Qual sua linguagem de programação favorita e por quê?"

## Respostas:
### Eu não sei o que estou fazendo aqui haha



## contribuidores:
### Joao
### Rian

####


C:\git\teste2>git branch
* main

C:\git\teste2>git branch camera

C:\git\teste2>git branch list

C:\git\teste2>git branch
  camera
  list
* main

C:\git\teste2>git branch dao-bruno

C:\git\teste2>git branch
  camera
  dao-bruno
  list
* main

C:\git\teste2>git checkout dao-bruno
Switched to branch 'dao-bruno'

C:\git\teste2>git branch
  camera
* dao-bruno
  list
  main

C:\git\teste2>git checkout -b sono-joao
Switched to a new branch 'sono-joao'

C:\git\teste2>git branch
  camera
  dao-bruno
  list
  main
* sono-joao

C:\git\teste2>git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

C:\git\teste2>git branch
  camera
  dao-bruno
  list
* main
  sono-joao

C:\git\teste2>git branch -d sono-joao
Deleted branch sono-joao (was 1a8b0b1).

C:\git\teste2>git branch
  camera
  dao-bruno
  list
* main

C:\git\teste2>git pull origin main
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 7 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (7/7), 2.75 KiB | 88.00 KiB/s, done.
From https://github.com/EvertonERReis/teste2
 * branch            main       -> FETCH_HEAD
   1a8b0b1..686bb5e  main       -> origin/main
Updating 1a8b0b1..686bb5e
Fast-forward
 README.md | 5 ++++-
 1 file changed, 4 insertions(+), 1 deletion(-)

C:\git\teste2>git merge camera
Already up to date.

C:\git\teste2>code .

C:\git\teste2>git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

C:\git>git clone https://github.com/LucasSchmidt92/teste-2.git
Cloning into 'teste-2'...
remote: Enumerating objects: 13, done.
remote: Counting objects: 100% (13/13), done.
remote: Compressing objects: 100% (8/8), done.
remote: Total 13 (delta 1), reused 11 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (13/13), done.
Resolving deltas: 100% (1/1), done.

C:\git>git clone https://github.com/LucasSchmidt92/teste-2.git
Cloning into 'teste-2'...
remote: Enumerating objects: 14, done.
remote: Counting objects: 100% (14/14), done.
remote: Compressing objects: 100% (9/9), done.
remote: Total 14 (delta 1), reused 11 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (14/14), done.
Resolving deltas: 100% (1/1), done.

C:\git>cd C:\git\teste-2

C:\git\teste-2>git branch
* main

C:\git\teste-2>git branch -d everton-colaborando
error: branch 'everton-colaborando' not found

C:\git\teste-2>git branch
* main

C:\git\teste-2>git checkout -b everton-colaborando
Switched to a new branch 'everton-colaborando'

C:\git\teste-2>git branch
* everton-colaborando
  main

C:\git\teste-2>git push -u origin nome-da-branch
error: src refspec nome-da-branch does not match any
error: failed to push some refs to 'https://github.com/LucasSchmidt92/teste-2.git'

C:\git\teste-2>git branch
* everton-colaborando
  main

C:\git\teste-2>\git push -u origin main
'\git' não é reconhecido como um comando interno
ou externo, um programa operável ou um arquivo em lotes.

C:\git\teste-2>git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

C:\git\teste-2>git branch
  everton-colaborando
* main

C:\git\teste-2>git push -u origin everton-colaborando
remote: Permission to LucasSchmidt92/teste-2.git denied to EvertonERReis.
fatal: unable to access 'https://github.com/LucasSchmidt92/teste-2.git/': The requested URL returned error: 403

C:\git\teste-2>git push -u origin everton-colaborando
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'everton-colaborando' on GitHub by visiting:
remote:      https://github.com/LucasSchmidt92/teste-2/pull/new/everton-colaborando
remote:
To https://github.com/LucasSchmidt92/teste-2.git
 * [new branch]      everton-colaborando -> everton-colaborando
branch 'everton-colaborando' set up to track 'origin/everton-colaborando'.

C:\git\teste-2>git checkout main
Already on 'main'
Your branch is up to date with 'origin/main'.

C:\git\teste-2>git checkout everton-colaborando
Switched to branch 'everton-colaborando'
Your branch is up to date with 'origin/everton-colaborando'.

C:\git\teste-2>code .

C:\git\teste-2>git status
On branch everton-colaborando
Your branch is up to date with 'origin/everton-colaborando'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   readme.md

no changes added to commit (use "git add" and/or "git commit -a")

C:\git\teste-2>git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

C:\git\teste-2>git add .

C:\git\teste-2>git commit -m "Alterou o arquivo README.md"
[everton-colaborando 2875d96] Alterou o arquivo README.md
 1 file changed, 1 insertion(+)

C:\git\teste-2>git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 303 bytes | 303.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/LucasSchmidt92/teste-2.git
   020fce0..2875d96  everton-colaborando -> everton-colaborando

C:\git\teste-2>git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

C:\git\teste-2>git pull origin main
From https://github.com/LucasSchmidt92/teste-2
 * branch            main       -> FETCH_HEAD
Already up to date.

C:\git\teste-2>git merge everton-colaborando
Updating 020fce0..2875d96
Fast-forward
 readme.md | 1 +
 1 file changed, 1 insertion(+)

C:\git\teste-2>git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\git\teste-2>git push
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/LucasSchmidt92/teste-2.git
   020fce0..2875d96  main -> main

C:\git\teste-2>

