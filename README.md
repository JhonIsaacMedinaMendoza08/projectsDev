#Configuracion inicial
trainer@johlver-virtual-machine:~/apoloJ1$ git add .
trainer@johlver-virtual-machine:~/apoloJ1$ gitmoji -i
✔ Gitmoji commit hook created successfully
trainer@johlver-virtual-machine:~/apoloJ1$ gitmoji -c
? Choose a gitmoji: 🔨  - Add or update development scripts.
? Enter the commit title [18/48]: Add code html file
? Enter the commit message: Add structure to file html blablalbla

Error: Seems that you're trying to commit with the cli but you have the hook created.
If you want to use the `gitmoji -c` command you have to remove the hook with the command `gitmoji -r`. 
The hook must be used only when you want to commit with the instruction `git commit`

trainer@johlver-virtual-machine:~/apoloJ1$ gitmoji -r
✔ Gitmoji commit hook removed successfully
trainer@johlver-virtual-machine:~/apoloJ1$ gitmoji -c
? Choose a gitmoji: ✨  - Introduce new features.
? Enter the commit title [12/48]: Ad structure
? Enter the commit message: demo
[main a011f57] ✨ Ad structure
 1 file changed, 11 insertions(+)
trainer@johlver-virtual-machine:~/apoloJ1$ git log --oneline
a011f57 (HEAD -> main) ✨ Ad structure
366fd2d (origin/main) docs: :memo: Add new line
6c8afac Create LICENSE
dbfd3f4 Add title README
ec17259 Start Project Web
trainer@johlver-virtual-machine:~/apoloJ1$ 