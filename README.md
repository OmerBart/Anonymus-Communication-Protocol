# Anonymous Communication Protocol

In traditional server-client communication, encryption protects the confidentiality of information but does not hide metadata like sender and recipient identities. This exercise aims to implement a protocol for anonymous communication between Alice and Bob. Instead of Alice directly communicating with Bob, messages are sent through an intermediary server. The server aggregates messages for a set time period and delivers them to their destination in random order, making it difficult for eavesdroppers to determine sender-recipient pairs. All messages have the same size and are encrypted using a public key provided by the server.

## Key Features:
- Encrypts messages for confidentiality.
- Hides sender and recipient identities.
- Uses an intermediary server to aggregate and randomize message delivery.
- All messages are of equal size to obfuscate content.
- Public key encryption ensures secure communication.

