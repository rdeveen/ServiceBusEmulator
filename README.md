# Service Bus Emulator
Emulator for the Azure Service Bus SDK

* Queues
* Topics

```
docker build . -t service-bus-emulator:latest
```

```
docker run --rm -p 5090:5090 --name ServiceBusEmulator service-bus-emulator:latest
```