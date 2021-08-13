# Haveno Functional Requirements

This document maintains functional requirements for the Haveno user interface (work in progress).

### Startup
- On first startup, the user must configure a password.
- On first startup, the user can use a local node or configure a remote node (url, username, password).
- On startup, the application presents a splash screen with progress and description of startup state.

### Wallet
- The user can deposit into their Haveno wallet.
- The user can generate new deposit subaddresses for their Haveno wallet.
- The user can withdraw from their Haveno wallet.
- The user can view their Haveno wallet balance.
- The user can view their Haveno wallet unlocked balance.
- The user can view a list of incoming and outgoing transfers to/from their Haveno wallet.
- The user can view the time until the Haveno wallet balance unlocks (if locked).

### View Market
- For each trade asset, the user can view open offers to buy or sell XMR.
- For each trade asset, the user can view a graph showing market depth of open offers.

### Make or Take Offers
- The user can make an offer to buy or sell XMR for another asset.
- The user can take an offer to buy or sell XMR for another asset.
- The Haveno wallet must have sufficient balance in order to make or take an offer.
- If the Haveno wallet balance is insufficient to make or take an offer, the user is prompted to deposit funds to their Haveno wallet and wait 10 confirmations (~20 minutes).
- The user is prompted to confirm trade details before making or taking offer.
- Total funds needed to trade = trade amount + security deposit + trade fee.
- If the user is selling XMR, they can enter a new receiving payment account (which is saved) or select from previous receiving payment accounts.

### Open Trade
- The user can directly chat with their trade peer.
- The user can open a dispute for an open trade after an allotted time.
- The user can directly chat with the arbitrator.
- The user can accept or reject the arbitrator decision?
- The user is notified when their offer is taken.
- The user is notified when they should make payment or confirm received payment.

### View User's Offers and Trades
- The user can view and cancel their open offers.
- The user can view their open trades.
- The user can view their completed trades.
- The user can view their failed trades.

### Settings
- The user can export a backup of their Haveno instance to a zip file.
- The user can view the mnemonic phrase of their Haveno wallet for manual backup (excludes funds locked in multisig).
- The user can configure a local or remote node.

### Receiving Payment Accounts
- The user can view, add, and remove accounts to receive payment for XMR.

### Other
- The application can present any errors that occur (e.g. error bar appears across top?).