# Magikarp Ground Mission

- 先 ssh 進到 launched instance
```
$ ssh ctf-player@venus.picoctf.net -p 51643
```
- 在 vm 內 follow instruction 操作
```
$ pwd
/home/ctf-player/drop-in
$ ls
$ cat instructions-to-2of3.txt
Next, go to the root of all things, more succinctly `/`
$ cd /
$ ls
$ cat instructions-to-3of3.txt
Lastly, ctf-player, go home... more succinctly `~`
$ cd
$ ls
$ cat drop-in/1of3.flag.txt /2of3.flag.txt 3of3.flag.txt | tr -d '\n'
picoCTF{xxsh_0ut_0f_\/\/4t3r_21cac893}
```
:triangular_flag_on_post: `picoCTF{xxsh_0ut_0f_\/\/4t3r_21cac893}`