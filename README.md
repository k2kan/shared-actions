# Shared-actions

```
- uses: k2kan/shared-actions/decrypt-vault@main
  with:
    environment: production
    ansible-vault-password: ${{ secrets.ANSIBLE_VAULT_PASSWORD }}
```