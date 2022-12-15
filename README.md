# Proto EnerBit gRPC models

Implementation of models and interfaces of gRPC services for version 1
####
To compile all protos files manualement:

```
RUN: protoc --go_out=plugins=grpc,paths=source_relative:pkg **/*.proto 

- After compile copy all content /pkg/internal/* to /pkg
```

After compile copy all content /pkg/internal/* to /pkg