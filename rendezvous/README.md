# go-p2p-network for rendezvous

# RUN

    go build
Let's run for three peers.
- Open terminal 1
    
        ./rendezvous -listen /ip4/127.0.0.1/tcp/6666

- Open terminal 2

        ./rendezvous -listen /ip4/127.0.0.1/tcp/6668

- Open terminal 3

        ./rendezvous -listen /ip4/127.0.0.1/tcp/6670

# Input

Give any integer number to any peer or terminal. It will be reflect to all peers or terminals.

