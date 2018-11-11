# Account Receivable Signing Demo

In this demo you are signing an invoice of Tessier-Ashpool SA to Weyland-Yutani Corp with your MetaMask account.  
The resulting signature can be verified and checked against the Smart Contract in the [invoice-verifier project].

# Setup

* Clone this repo or download ZIP
* Serve files locally using a web server, eg. by running `python -m SimpleHTTPServer 8000` in the root directory
* Make sure MetaMask is installed and the correct account for signing is selected

# Usage

* Unlock MetaMask
* Call `http://localhost:8080` and use value from sample data
* After signing the data, copy the generated values from the textbox to the `ard.csv` file in [invoice-verifier project]

# Original EIP712 Signing Demo

This is derived from the demonstration of EIP712 signing support (EIP712 Signing Demo) via MetaMask's `eth_signTypedData_v3` API call.

[Try the original version here.](https://weijiekoh.github.io/eip712-signing-demo/index.html)

You need a version of MetaMask that supports eth_signTypedData_v3 to use this demo (4.14+).