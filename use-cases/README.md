**MoneroAuth Use Cases**

**Actors:**

**Controller** – The entity that initiates the use case by taking action and sending the first message. This is usually an individual human being requesting authentication/authorization to use a resource. Machines or Resources (below) can also play the role of Controller.

**Resource Manager** – The entity assigned to manage digital/physical resources a.k.a The Gatekeeper. Resource Managers are responsible for authenticating and authorizing entities to access resources under its control.

**Resource** – Is either a digital or physical resource that requires authentication/authorization prior to use. Resource examples:
+ dataset
+ application
+ physical lock
+ garage-door opener
+ smart thermostat
+ etc.

**authbot** – an automated MoneroAuth personal assistant providing public key cryptography and key management services over a private, end-to-end encrypted messaging network. The communications network currently utilized is the [Matrix](https://matrix.org/), open network for secure, decentralized communication.

The *authbot* also supports a dictionary of commands used for secure, automated resource management.
