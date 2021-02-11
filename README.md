# 手順

## Start

### Create

```bash
mkdir project && cd project && touch .gitignore && clasp create --rootDir src && npm init --y && npm i @types/google-apps-script --save-dev && touch src/Code.js && code -a .
```

### Clone

```bash
mkdir project && cd project && touch .gitignore && clasp clone <スクリプトID> --rootDir src && npm init --y && npm i @types/google-apps-script --save-dev && code -a .
```

### Open

```bash
clasp open
```

### Push

```bash
clasp push
```

### .gitignore

```bash
.clasp.json
```

> 【参考】.clasp.jsonの中身
> ```json
> {"scriptId":"","rootDir":"src"}
> ```
