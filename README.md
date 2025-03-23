Steps to reproduce:

```
❯ npm create vite@latest -- -t react-swc-ts test

❯ jq < test/tsconfig.app.json
jq: parse error: Invalid numeric literal at line 10, column 7

❯ jq < test/tsconfig.node.json
jq: parse error: Invalid numeric literal at line 9, column 7
```
