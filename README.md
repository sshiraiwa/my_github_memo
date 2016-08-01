# my_github_memo

My personal memo on how to use GitHub....

clean repository
 > git clean -f (-n)  -n for dry run
 
show remote
 > git remote -v
 
remove remote.. 
 > git remote rm origin
 
create a branch w/o history
 > git branch upload $(echo "commit message" | git commit-tree HEAD^{tree})
 
when creating a new repo at github. Need to add new remote origin
 > git remote add origin git@github.com:piScope/PyMFEM_pi.git

.and push.. 
 > git push -u origin upload:master
