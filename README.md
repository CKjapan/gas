# 手順

### Create

```bash
mkdir project && cd project && touch .gitignore && clasp create --rootDir src && npm init --y && npm i @types/google-apps-script --save-dev && clasp open && code -a .
```

```bash
clasp pull
```

### Clone

```bash
mkdir project && cd project && touch .gitignore && clasp clone <スクリプトID> --rootDir src && npm init --y && npm i @types/google-apps-script --save-dev && clasp open && code -a .
```

```bash
clasp pull
```

### Open

```bash
clasp open
```

### Push

```bash
clasp pull
```

### .gitignore

```bash
.clasp.json
```

> 【参考】.clasp.jsonの中身
> ```json
> {"scriptId":"","rootDir":"src"}
> ```
