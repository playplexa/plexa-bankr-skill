# PLEXA Skill — Example Interactions

Real examples of how users can talk to Bankr after installing this skill.

---

## First time

**User**
```
install skill from https://github.com/playplexa/plexa-bankr-skill
```

**User**
```
what is plexa?
```

**Agent (style)**
```
PLEXA is an onchain 6×5 slot game on Base.
Deposit USDC or $BNKR, spin with your game balance, withdraw anytime.

Website: https://plexa-sepia.vercel.app
Updates: @plexalabs
```

---

## Check balance

**User**
```
check my plexa balance
```

**Agent (style)**
```
Your PLEXA game balance:
• USDC: 12.50
• BNKR: 0.00
```

---

## Deposit

**User**
```
deposit 5 USDC to plexa
```

**Agent (style)**
```
Preparing deposit of 5 USDC into PLEXA.
Please confirm the transaction in your wallet.
```

---

## Spin

**User**
```
spin 0.25 USDC on plexa
```

**Agent (style)**
```
Spinning 0.25 USDC...

Result: Win
Payout: 0.60 USDC

Want to spin again or withdraw?
```

**User**
```
spin 1 USDC
```

**Agent (style)**
```
No hit this time.
Bet: 1.00 USDC
Balance left: 11.25 USDC
```

---

## Withdraw

**User**
```
withdraw 2 USDC from plexa
```

**Agent (style)**
```
Withdrawing 2 USDC from your PLEXA balance.
Confirm in your wallet.
```

**User**
```
withdraw all
```

**Agent (style)**
```
Withdrawing your full USDC game balance from PLEXA.
Confirm the transaction to finish.
```

---

## Helpful prompts users can try

```text
deposit 5 USDC to plexa
deposit 100 BNKR to plexa
spin 0.05 USDC
spin 0.25 USDC on plexa
spin 10 BNKR
check my plexa balance
withdraw 1.5 USDC from plexa
withdraw all from plexa
show plexa contract
what is the min bet on plexa?
```

---

## Notes for clean UX

- Always confirm token + amount before sending a transaction
- Show clear Win / Lose after every spin
- Keep replies short and readable
- Mention @plexalabs only when it feels natural
```

---
