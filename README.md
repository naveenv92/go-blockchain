# go-blockchain
Adapted from Medium article [here](https://mycoralhealth.medium.com/code-your-own-blockchain-in-less-than-200-lines-of-go-e296282bcffc)

## Running
1. Create `.env` with `PORT=<port>`
2. `go run main.go`

## Viewing blockchain
1. Go to `http://localhost:<port>`

## Writing to blockchain
```bash
curl --location 'http://localhost:8080' \
--header 'Content-Type: application/json' \
--data '{"BPM": <bpm>}'
```
