Zadania - Bash
==========================
Zadanie nr 1

  -sh
  
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

  

  ![logo](https://assets-cdn.github.com/images/modules/open_graph/github-octocat.png).
