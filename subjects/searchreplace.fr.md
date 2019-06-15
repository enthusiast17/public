## searchreplace

### Instructions

Écrire un programme qui prends 3 arguments, le premier argument est une `string` dans laquelle une lettre (le 2éme argument) est remplacée par une autre (3éme argument).

- Si le nombre d'aruments n'est pas 3, le programme affiche un newline(`'\n'`).

- Si le second argument n'est pas contenu dans le premier (la `string`) alors le programme réécris la `string` suivi d'un newline(`'\n'`).

### Utilisation

```console
student@ubuntu:~/piscine/test$ go build
student@ubuntu:~/piscine/test$ ./test "hella there" "a" "o"
hello there
student@ubuntu:~/piscine/test$ ./test "abcd" "z" "l"
abcd
student@ubuntu:~/piscine/test$ ./test "something" "a" "o" "b" "c"

student@ubuntu:~/piscine/test$
```