# ansible-hashi-vault-otp
Begining of an Ansible playbook that can consume SSH One Time Passwords from HashiCorp Vault

This playbook assumes you have have created an approle in Vault with the appropriate permissions to generate & read dynamic OTP credentials.
- https://www.vaultproject.io/docs/auth/approle

And that you have enabled the One-Time SSH Passwords secret type, and created a corresponding role.
- https://www.vaultproject.io/docs/secrets/ssh/one-time-ssh-passwords
