Zadania - Bash
==========================
Zadanie nr 1

 ```sh
  
  mkdir temp
  cd temp
  mkdir dom nauka praca
  cd nauka
  mkdir c logo pascal
  cd ../praca
  mkdir dokumenty zlecenia
  cd zlecenia
  mkdir zrealizowane niezrealizowane
  cd ../../dom
  mkdir wazne-sprawy
  cd wazne-sprawy
  touch rachunki.txt
  cp rachunki.txt ../../praca/zlecenia/zrealizowane
  cd ../../praca/zlecenia/zrealizowane
  mv rachunki.txt wykonano.txt
  echo "HelloWorld" >>wykonano.txt
  split -b 4 wykonano.txt
  cp xaa xab xac ../../dokumenty
  cd ../../dokumenty
  cat *>odtworzono.txt
  cp odtworzono.txt ../../dom/wazne-sprawy
  cd ../../dom/wazne-sprawy
  cal 10 2009
  cal 10 2009 -3
  cal 11 2009 -3
  

 
```
Zadanie nr 2

```sh
 head -n 2 program.c
 tail -n 4 program.c
 grep "main" program.c
 chmod 640 program.c





```
  

  ![logo](https://assets-cdn.github.com/images/modules/open_graph/github-octocat.png).
