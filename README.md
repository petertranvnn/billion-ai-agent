# billion-ai-agent

1. Update

```
sudo apt-get update && sudo apt-get upgrade -y
```

2. Cài Node.js & npm
```
sudo apt install -y nodejs npm
```
3. Cài đặt git
```
sudo apt install -y git
```

4. Clone source repository

```
git clone https://github.com/BillionsNetwork/verified-agent-identity
```
```
cd verified-agent-identity
```

5. Cài đặt package

```
npm install shell-quote @iden3/js-iden3-auth @0xpolygonid/js-sdk ethers uuid cross-fetch
```

6. Cài skill qua ClawHub

```
npx clawhub@latest install verified-agent-identity
```
7. Tạo Billion identity

```
node scripts/createNewEthereumIdentity.js
```
8. Tạo billion verify link
```
node scripts/manualLinkHumanToAgent.js --challenge '{"name":"TênAgen","description":"mô tả"}'
```

Note: Thay tênAgent và description trong lệnh trên bằng tên và mô tả theo ý muốn của bạn


