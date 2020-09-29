KENNEDY MOSOTI

PART2A)

```bash

$ git checkout -b test1

Switched to a new branch 'test1'


$ git checkout master

Switched to branch 'master'

Your branch is up to date with 'origin/master'.


$ git checkout -b test1

Switched to a new branch 'test1'

$ git branch -a

  master

  test1

* test2

  remotes/origin/master

```


PART2B)

```bash

$ git checkout test1

Switched to branch 'test1'

M       homework/VCS/readme.md

$ cd test1

$ touch ../homework/vcs/test.txt

```


PART2C)

```bash
$ echo "This is some example text for branch test1" > homework/test.txt

```


PART2D)
```bash
$ git push origin test1

Enumerating objects: 11, done.

Counting objects: 100% (11/11), done.

Delta compression using up to 16 threads

Compressing objects: 100% (5/5), done.

Writing objects: 100% (6/6), 742 bytes | 371.00 KiB/s, done.

Total 6 (delta 1), reused 0 (delta 0), pack-reused 0

remote: Resolving deltas: 100% (1/1), completed with 1 local object.

remote:

remote: Create a pull request for 'test1' on GitHub by visiting:

remote:      https://github.com/kmosoti/1301_DATA/pull/new/test1

remote:

To https://github.com/kmosoti/1301_DATA.git

 * [new branch]      test1 -> test1
 

```

Part 2E)
''
