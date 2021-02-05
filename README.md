# Usage

Install dependencies:

```sh
$ yarn
```

Copy .envrc.example to .envrc and set ALCHEMY_URL:

```sh
$ cp .envrc.example .envrc
```

Run direnv allow

```sh
$ direnv allow
```

Now start fork

```sh
$ yarn start
```


# Impersonating Accounts

Remember to impersonate the accounts you need!

```javascript
await ethers.provider.send("hardhat_impersonateAccount", [ACCOUNT_1, ACCOUNT_2])
```