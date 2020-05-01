# Useful commands

* Preprocessing command

  ```shell
  g++ -E -P program.cpp -o program.ii
  ```

* Translation command

  ```shell
  g++ -S program.i -o program.s
  ```

* Assembling command

  ```shell
  g++ -c program.s -o program.o
  ```

* Compiling command (includes linking)

  ```shell
  g++ 1program.o -o program
  ```