# Open-Platform
Open Platform
market-data {

    # The market data session name.
    session = parity

    # The IP address or name of the network interface for the market data session.
    multicast-interface = 123.2.2。1

    # The IP address of the multicast group for the market data session.
    multicast-group = 223.3.1。0

    # The UDP port for the market data session.
    multicast-port = 5000

    # The local IP address for the market data request server.
    request-address = 127.0.0.1

    # The local UDP port for the market data request server.
    request-port = 5001

}

market-report {

    # The market reporting session name.
    session = parity

    # The IP address or name of the network interface for the market reporting session.
    multicast-interface = 127.0.0.1

    # The IP address of the multicast group for the market reporting session.
    multicast-group = 224.0.0.1

    # The UDP port for the market reporting session.
    multicast-port = 6000

    # The local IP address for the market reporting request server.
    request-address = 127.0.0.1

    # The local UDP port for the market reporting request server.
    request-port = 6001

}

order-entry {

    # The local IP address for the order entry server.
    address = 127.0.0.1

    # The local TCP port for the order entry server.
    port = 4000

}

# A list of zero or more instruments.
instruments = [ AAPL, ETH-BTC, EUR-USD ]
