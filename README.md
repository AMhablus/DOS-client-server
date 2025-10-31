# 🛰️ Go RPC Chat Example

This is a simple Go project that demonstrates how to use **RPC (Remote Procedure Call)** for communication between a client and a server.

## Recording Link
- Google Drive: [Click Here!](https://drive.google.com/file/d/1pNZOylBWN6v6ypiEDr_PuyPvmCPsG-b3/view?usp=sharing)

## 📘 Overview
- The **server** listens for incoming TCP connections and serves RPC requests.
- The **client** connects to the server and makes remote procedure calls as if they were local functions.
- The `net/rpc` package automatically handles encoding, decoding, and communication between client and server.

## ⚙️ Files
- `server.go` — starts the RPC server and waits for client requests.
- `client.go` — connects to the server and calls the server’s RPC functions.

## 🚀 How to Run

1. **Start the server**
   ```bash
   go run server.go


2. **Run the client in another terminal**
   ```bash
   go run client.go

3. **Enter messages**
    Type a message and press Enter to send it to the server.
    The server processes the request and returns a response.