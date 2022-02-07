---
layout: default
title: Hyperledger Fabric Connector
parent: Labs
---
# Lab Name
Hyperledger Fabric Connector

# Short Description
A service to integrate Hyperledger Fabric and enterprise systems. The service
provides both synchronous and asynchronous interfaces for the integration.
A RESTful option is made available for synchronous transaction submission and
querying. For asynchronous transaction submissions an integration option is
available through Kafka. While an option is also available to listen to emitted
events from the blockchain, one can subscribe to either or both Block or/and
Chaincode Events.

# Scope of Lab
The service is designed to integrate Hyperledger Fabric with enterprise
systems. The current possible integrations are RESTful interfaces, Kafka pub-sub
messaging (also supports Azure EventHub). Additional interfacing options can be
enabled based on the needs. The interfaces also make provisions for dealing with
the Private Data Collections.

This service has both tranactional capabilities (such as data
ingestion, event emitting) and ability for administrative operations
(such as channel creation/update, chaincode operations).
A user management option would be made available for choosing the right
credential to interact with the Fabric network.

# Initial Committers
Github IDs for the set of initial committers.
- https://github.com/anandbanik
- https://github.com/jopuneet
- https://github.com/weihong-ou
- https://github.com/ShubhIO

# Sponsor
- https://github.com/arsulegai  - TSC Member

# Pre-existing repository
- https://github.com/blockchain-wmt/hlf-rest-client
