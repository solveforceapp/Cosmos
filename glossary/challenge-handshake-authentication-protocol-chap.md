# Challenge-Handshake Authentication Protocol (CHAP)

## Definition

Challenge-Handshake Authentication Protocol (CHAP) is a network authentication protocol that uses a unique challenge-response mechanism to verify user identity and prevent replay attacks. CHAP enhances security by ensuring that credentials are never sent in plain text.

## How It Works

When a user attempts to connect, the server sends a random challenge. The client responds with a value calculated using a shared secret (password) and the challenge. The server verifies the response, granting access if it matches. CHAP periodically re-authenticates during the session.

## Real-World Application

CHAP is used in dial-up, VPN, and PPP connections. It protects against eavesdropping and credential theft. Modern networks may use CHAP alongside other protocols for multi-factor authentication.

Imagine a secret handshake that changes every time you meet, making it impossible for imposters to copy.

## Entertaining Example

Picture a bouncer who invents a new password for every guest, checking their response before letting them in.

## Why It Matters

CHAP is a foundational protocol for secure network access, balancing convenience and protection.

---
Contact: Cosmos Knowledge Base — SolveForce  
Email: contact@solveforce.com  
For corrections or suggestions, please open an issue in the repository.
---
