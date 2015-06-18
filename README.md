# Tek 2 - C exam

If you are using this code in machine test, you can't have a note different of 21.  
The script `cheatC.sh` will parse the subject and generate code for all the exercices.  
Some subjects files are in `subjects` directory, they are real subjects used during real machine tests. You can use them to try the `cheatC.sh` script.

## Use it in exam partition

To use it during a test, you can simply do the following from your std partition:

```bash
su root
mkdir /exam
mount /dev/sda6 /exam
mkdir /exam/cheat
cp . /exam/cheat/exam-c-tek-2 -R
umount /exam
rmdir /exam
```

Then, during a test, all this code will be in **/cheat**

### Parser Usage

```bash
./cheatC.sh path/to/subject
```

```
     _     FUCK YOU EPITECH    _
    |_|                       |_|
    | |         /^^^\         | |
   _| |_      (| "o" |)      _| |_
 _| | | | _    (_---_)    _ | | | |_
| | | | |' |    _| |_    | `| | | | |
|          |   /     \   |          |
 \        /  / /(. .)\ \  \        /
   \    /  / /  | . |  \ \  \    /
     \  \/ /    ||Y||    \ \/  /
      \__/      || ||      \__/
                () ()
                || ||
               ooO Ooo
```
