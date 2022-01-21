 2053  git clone git@github.com:joerencl/BankingMicroservice.git
 2054  cd BankingMicroservice
 2055  touch App.java
 2056  git add .
 2057  git commit -m "initial commit"
 2058  git push origin master
 2059  git add .
 2060  git commit -m "second commit"
 2061  git push origin master
 2062  git branch dev1
 2063  git branch dev2
 2064  git checkout dev1
 2065  echo "Developed by dev1" >> dev1.txt
 2066  git add dev1.txt
 2067  git commit -m "commit by dev1"
 2068  git push origin dev1
 2069  git checkout dev2
 2070  echo "Developed by dev2" >> dev2.txt
 2071  git add dev2.txt
 2072  git commit -m "commit by dev2"
 2073  git push origin dev2
 2074  git checkout main
 2075  git checkout master
 2076  git merge dev1
 2077  git merge dev2
 2078  git push origin master
