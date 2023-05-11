## Architecture

Currently, the project consists of a Go microservice and a corresponding client application. They communicate using [gRPC](https://grpc.io/).

```
-------------------            -------------------
| Client          |            | Server          |
| --------        |            |                 |
| | SDK* |        | <--gRPC--> |                 |
| --------        |            |                 |
-------------------            -------------------

* Unimplemented
```
### Service Information
[Service Info](service-go/README.md)

### Client Information
[Client Info](client-go/README.md)

### Potential next steps

| Feature/Component      | Description                                                                                                  |
| ---------------------- | ------------------------------------------------------------------------------------------------------------ |
| Authentication         | Authenticate and authorize API requests.                                                                      |
| Client SDK             | Manage client-side authentication.                                                                            |
| Configuration          | Inject config values from environment.                                                                        |
| Structured Logging     | DONE |
| Testing                | Unit tests, integration tests.                                                                                |
| Continuous Integration | GitHub Actions for tests.                                                                                    |
| Front-end client       | A visual interface.                                                                                          |
| Setup scripts          | Automate onboarding.                                                                                          |
| Containerization       | DONE |
