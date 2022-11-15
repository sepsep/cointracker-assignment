# CoinTracker  Assignment
Sepandar Sepehr

## Prerequisite
Make sure you have the latest version of Go installed
## Running the App
First run `go build cointracker_app.go` to make sure dependencies are installed

Then run `go run cointracker_app.go` 

Go to `http://localhost:8080/wallet` on your browser.
On this page, you can add a wallet ID, remove one, get transactions of, and synchronize transactions for all stored wallets. 

## TODO
* Build repository instead of interacting with DB directly 
* Add logging and metrics