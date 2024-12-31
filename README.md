# fastapi

> Used to quickly build fastapi applications

## Update submodule

```shell
git submodule update --remote fastapi-core
git commit -m "Update fastapi submodule to latest commit"
git push origin main
```

## With submodule

- update

  ```shell
  git submodule update --init --recursive --remote
  ```

- pull

  ```shell
  git submodule update --init --recursive
  ```

- clone
  ```shell
  git clone --recurse-submodules https://github.com/pyweb-compat/fastapi
  ```

## Commit rules

### fix

```txt
🔧fix:xxxx
🔍fix:xxxx
```

### bug

```shell
🐛bug:xxx
🐞bug:xxx
```

### docs

```shell
📝docs:xxx
📚docs:xxx
```

### dev

```shell
💻dev:xxx
🔨dev:xxx
```

### add

```shell
✨add:xxx
➕add:xxx
```

### delete

```shell
❌del:xxx
♻️del:xxx
```

### remove

```shell
⏩move:xxx
```

### todo

```shell
🔖todo:xxx
⚙️todo:xxx
```
---

## Using lang

```shell
+ Python
+ Golang
+ Lua
+ Java
```
---