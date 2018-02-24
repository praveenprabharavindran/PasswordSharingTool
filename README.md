# PasswordSharingTool
Provides a secure way to share password between teams that are georaphically separate

One of the challenges we face with geographically separated teams is that of securely sharing passwords. This tool provides a way to securely share password by:
1. Encrypting the password data with an ephemeral key
2. The key itself would be encrypted using an individuals public key.
3. The key and encrypted data is sent over email along with a HMAC of the encrypted data to ensure integrity of the data shared.
