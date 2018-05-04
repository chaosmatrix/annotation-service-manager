# Use Case

### Use Case List
1. Bind port numbers less than 1024 without root-privelidge
    1. grant capabilities
        * AmbientCapabilities=CAP_NET_BIND_SERVICE
        * reference:
            * man capabilities
        * warning:
            * Capabilities are a per-thread attribute
    2. use systemd.socket
        * if not consider performance
        * work like xinet

