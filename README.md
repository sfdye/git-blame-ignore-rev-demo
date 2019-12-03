# test-repo

## Demo

```bash
git blame hello.py

a4418b3a (Wan Liuyang 2019-12-03 22:48:16 +0800 1) def main():
dbd6f39f (Wan Liuyang 2019-12-03 22:48:55 +0800 2)     print("hello world")
dbd6f39f (Wan Liuyang 2019-12-03 22:48:55 +0800 3)
a4418b3a (Wan Liuyang 2019-12-03 22:48:16 +0800 4)
dbd6f39f (Wan Liuyang 2019-12-03 22:48:55 +0800 5) if __name__ == "__main__":
dbd6f39f (Wan Liuyang 2019-12-03 22:48:55 +0800 6)     main()
```

```bash
git blame --ignore-revs-file .git-blame-ignore-revs hello.py

a4418b3a (Wan Liuyang 2019-12-03 22:48:16 +0800 1) def main():
a4418b3a (Wan Liuyang 2019-12-03 22:48:16 +0800 2)     print("hello world")
dbd6f39f (Wan Liuyang 2019-12-03 22:48:55 +0800 3)
a4418b3a (Wan Liuyang 2019-12-03 22:48:16 +0800 4)
a4418b3a (Wan Liuyang 2019-12-03 22:48:16 +0800 5) if __name__ == "__main__":
dbd6f39f (Wan Liuyang 2019-12-03 22:48:55 +0800 6)     main()
```
