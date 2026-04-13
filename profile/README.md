# WebSH - uncover your browser capabilites

### WebSH provides secure, browser-based access to remote servers. The platform is built on a zero-knowledge architecture where secrets are encrypted on the client and never exposed to the backend.
Core Functionality

- Client-side encrypted vault: SSH keys and profiles are stored locally and encrypted using AEAD ciphers. Decryption occurs only in the browser.
- Tiling terminal interface: Multi-session support with a binary space partitioning layout for efficient workspace management.
- Authenticated tunneling: Lightweight tunnel nodes for accessing local infrastructure behind NAT or firewalls without port forwarding.
- Encrypted synchronization: Optional end-to-end encrypted sync for settings, server lists, and command snippets.
- Session sharing: Live terminal output streaming with read-only permissions for debugging and collaboration.

<img width="1915" height="918" alt="image" src="https://github.com/user-attachments/assets/c3eff75c-7bdc-4c5a-b4b2-8151c67645bb" />

### Project Status
The system is designed for developers and system administrators who require remote shell access with a focus on privacy and isolation. All network communications are protected via TLS, and user authentication utilizes memory-hard hashing.

Link: https://websh.dev
