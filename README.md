# Shared-actions

```
- name: Decrypt vault secrets
  uses: k2kan/shared-actions/decrypt-vault@dev
  with:
      environment: ${{ steps.extract.outputs.environment }}
      ansible-vault-password: ${{ secrets.ANSIBLE_VAULT_PASSWORD }}
```