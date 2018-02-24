# PasswordSharingTool
Provides a secure way to share password between teams that are georaphically separate

One of the challenges we face with geographically separated teams is the challenge of securely sharing passwords. This tool provides a way to securely share password by email using:
1. Encrypted password data using an ephemeral key
2. The key is encrypted using an individuals public key.
3. The key and encrypted data is sent over email along with a HMAC of the encrypted data to ensure integrity of the data shared.
