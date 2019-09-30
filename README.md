Add 2 origins to the same repository  

Remote1: test1  
Remote2: test2  
  
git remote add origin \<REMOTE-URL1\>  
git remote set-url --add --push origin \<REMOTE-URL1\>  
git remote set-url --add --push origin \<REMOTE-URL2\>  

