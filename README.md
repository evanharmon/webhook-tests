# webhook-tests
for testing webhooks

## Create webhook secret

```console
node -e "console.log(crypto.randomBytes(20).toString('hex'))"
```

store in settings and save in a `.env` file in whatever repo is being used to test accepting
