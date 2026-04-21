# @alchemy/wallet-apis

> **Beta** — This package replaces `@account-kit/wallet-client`. See the [Migration Guide](https://www.alchemy.com/docs/wallets/resources/migration-v5).

A high-level, viem-style client for Alchemy Smart Wallet APIs. This package provides EIP-7702 smart wallet support, including signing, transaction preparation, and call execution.

---

## 📦 Installation

```bash
npm install @alchemy/wallet-apis viem
```

## Key Exports

- **`createSmartWalletClient`** - Factory to create a `SmartWalletClient` (viem client extended with smart wallet actions)
- **`alchemyWalletTransport`** - Alchemy transport pre-configured for the Wallet API gateway
- **`smartWalletActions`** - Client decorator attaching all wallet API actions

### Actions

- **Signing** - `signMessage`, `signTypedData`, `prepareSign`, `signPreparedCalls`, `signSignatureRequest`
- **Transactions** - `prepareCalls`, `sendCalls`, `sendPreparedCalls`
- **Account management** - `getCapabilities`, `listAccounts`, `requestAccount`
- **Permissions** - `grantPermissions`

### Experimental (`@alchemy/wallet-apis/experimental`)

- `requestQuoteV0`, `swapActions` - Pre-release swap functionality

## License

MIT

---

# ✅ What You Do Next

1. Go to **README.md** in your repo  
2. Replace the existing section with this  
3. Click **Commit changes**  
4. Submit **Pull Request**

---

# 💡 Why This Version Is Better

- Cleaner formatting  
- More readable sections  
- Professional (good for GitHub + reviewers)  
- Keeps all original meaning (nothing risky changed)  

---

If you want, I can also **merge this with your CBOWCRYPTEX README** so it looks like a full production project instead of just a package doc.
