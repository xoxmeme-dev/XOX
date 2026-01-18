# 💎 XOX

XOX is a GameFi utility token deployed on BNB Smart Chain.

---

## 🧾 Token Information

- Name: XOX  
- Symbol: XOX  
- Network: BNB Smart Chain  
- Total Supply: 1,000,000,000 XOX  

### Token Contract
- Address: 0x69aC3fe78c15DCb9dBB130fC47685b55c602e056  
- BscScan:  
  https://bscscan.com/token/0x69aC3fe78c15DCb9dBB130fC47685b55c602e056  

---

## 🔢 Token Distribution

The total supply of XOX is fixed at 1,000,000,000 tokens.

- 35% — Staking Rewards  
  Allocated for staking incentives.

- 30% — Token Sale & Liquidity  
  Reserved for future token sales and liquidity provisioning.

- 30% — Game Platform Ecosystem  
  Allocated for the development and operation of the game platform ecosystem.

- 5% — Reserve  
  Set aside as a contingency reserve.

---

## 🔐 Supply Management & Lockup

To enhance transparency and reduce custody risk, a portion of the total supply
is secured via smart-contract-based lockups.

- 40% of the total supply is locked via PinkSale V2
- 4-year vesting period with 25% released annually
- All lockups are enforced on-chain and publicly verifiable

---

## 🔒 Staking

XOX staking is provided through a vault-based staking contract.

### Vaults
- Vault 0: 2.5% APY, no lockup (basic)
- Vault 1: 4.0% APY, 90-day lockup
- Vault 2: 6.0% APY, 180-day lockup
- Vault 3: 15.0% APY, 365-day lockup

Deposit limits (per vault):
- Vault 0: min 5,000 XOX / max 2,500,000 XOX
- Vault 1–3: min 10,000 XOX / max 2,500,000 XOX

Each wallet can have one active stake per vault.

### Withdrawals
Withdrawals follow a two-step process:
1. Request withdrawal
2. Claim after the waiting period

Waiting period:
- Standard withdrawal: 24 hours
- Early withdrawal (before lockup ends): 72 hours

Rewards are calculated up to the withdrawal request time.

Early withdrawal APY is applied based on the actual staking duration:
- ≥ 180 days: 6.0%
- ≥ 90 days: 4.0%
- < 90 days: 2.5%

### Rewards
Staking rewards are distributed from a predefined reward pool.
No additional tokens are minted for rewards.

### Staking Contract
- Address: 0x5e8E2597b28dc20e09F4c3e0892fC267aAA3e37d

---

## 📦 Contracts

The token and staking contracts are deployed on BNB Smart Chain
and can be reviewed via public explorers and this repository.

---

## 🔗 Official Link

- Website: https://xoxmeme.io/
- Twitter/X: https://x.com/XOX_HQ
