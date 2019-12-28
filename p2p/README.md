# go-p2p-network

# RUN

    go build
Let's run for three peers.
- Open terminal 1
    
        ./p2p -sp 3001

- Open terminal 2

        ./p2p -sp 3002 -d /ip4/127.0.0.1/tcp/3001/p2p/<terminal-1 key  paste here>

- Open terminal 3

        ./p2p -sp 3003 -d /ip4/127.0.0.1/tcp/3002/p2p/<terminal-2 key  paste here>

# Input

Give any integer number to any peer or terminal. It will be reflect to all peers or terminals.

