Predict the total amount of Trump’s World Liberty Financial (WLFI) token sold by the end of 2025. WLFI is represented by the address `0xdA5e1988097297dCdc1f90D4dFE7909e847CBeF6` on Ethereum Mainnet. The reference will be the holdings of the WLFI token in the sales contract (`0xe217E15b3C19cC0427F9492dC3bcfe8220aFAD10`) at the final block of 2025, representing unsold tokens.

### Market Rules:
 - **UP Option:**  Redeemed at **$(x - 5) / (20 - 5) GM$**.
 - **DOWN Option:**  Redeemed at **$(20 - x) / (20 - 5) GM$**.
 - **Where $x = min(max(result, 5), 20)$ (unit: billion):**
   - If the total sold is below **5 billion**, **x is set to 5**.
   - If the total sold exceeds **20 billion**, **x is set to 20**.

### Sources:
- [TransparentUpgradeableProxy | Etherscan](https://etherscan.io/address/0xe217e15b3c19cc0427f9492dc3bcfe8220afad10)  
- [World Liberty Financial Token Sale](https://www.worldlibertyfinancial.com/intl/token-sale)
