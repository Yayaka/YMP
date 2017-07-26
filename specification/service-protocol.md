# Service protocols

*Service protocol* specifies its own services and messages.


## Specification

A specification of service protocol contains following descriptions:

- MUST its name
- MUST its version
- MUST list of services
- MUST list of actions
- MUST timeout and retransmission strategy
- MAY parameters to configure.

A name, services, and actions SHOULD match the regular expression "[a-z0-9-]+" and a version MUST be a semver.


## Subprotocols

If a service protocols has subprotocols, they SHOULD be specified in its parameters in a similar format of host informations.


## Compatibility

Messages don't have the proprety to specify the version of service protocol.
Each service protocol SHOULD make efforts to keep the compatibility between different versions.