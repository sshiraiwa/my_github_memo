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

.and push.. 
 > git push -u origin upload:master
