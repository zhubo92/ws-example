# WebSocket 示例

## client 和 client2 进行聊天，或者 1.html 和 2.html进行聊天

```shell
nvm use $(Get-Content .nvmrc)
```

```shell
cd server
npm install
```

```shell
cd ../client
npm install
```

```shell
cd ../client2
npm install
```

```shell
cd ../server
npm run start
```

```shell
cd ../client
npm run serve
```

```shell
cd ../client2
npm run serve
```