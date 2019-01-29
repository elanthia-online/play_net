# play.net utils

### `bin/claim_rewards` 

automates claiming simucoin rewards, accepts a file of accounts to use

example `accounts.txt`:
```
my_account my_password
account_2 account_2_password
```

```
$ cat accounts.txt | bin/claim_rewards
```