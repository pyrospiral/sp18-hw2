Implements gRPC framework, to write a wide-area distributed application for simple sorting with code pushed to datacenters on four continents for measuring the resulting performance of the application.


Compiling protobufs:
`mvn protobuf:compile protobuf:compile-custom`

Compiling Java code:
`mvn package`

Running server:
`./target/globesort/bin/runServer <server_port>`

Running client:
`./target/globesort/bin/runClient <server_ip> <server_port> <values>`
