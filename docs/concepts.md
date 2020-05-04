---
layout: page
title: Concepts
permalink: /concepts
---
# 🧠 Concepts

## Top level concepts

- 📜 Standard - The universal logical rules by which all system interactors play
- ⚙️ Protocol - running instance of standardized and distributed identity system
- 👩 User - Human represented by a digital identity, and with access to a device
- 👨‍✈️ Operator - Stores private user information partially or fully, may provide the user with a usable interface, and surface notifications.
  - ✅👨‍✈️ Designated operator - The operator responsible for providing the user with a graphical interface, and for delivering notifications.
- 🤖 Service agent - Represents digital entity of a non-user system.
- 🛡 Guardian - Is consulted in rare high impact potentially risky cases such as 1. loss of access 2. large transactions 3. succession events (like death or transition).
  - 🛡👨 Individual guardian
  - 🛡🏢 Guardian provider
- ✍️ Guarantor - Guarantees and verifies an identity and insures against a set of loss/harm criteria.
  - ✅ Verifier - Verifies identities and/or claims about identities.

## Identity and connection

### 🆔🔵🔺🔸 Identity types

- 👨Human
  - 🌳 Root
  - 👩‍💻 User
    - ⌚️👨 Device user
  - 🌍 Public
  - 👤 Abstract
    - 👤👨‍👩‍👧‍👦💚💼 Contextual
    - 👤🧢 Dedicated (Per-subscription) (per long term connection)
    - 👤🕶 Masked/alias
    - 👤👺 Anonymous
      - 👤👺🧢 Pseudo-anonymous
- 🤖 Delegate (agent)
- 🗣 Subjective (according to 3rd party)
- 👨‍👦‍👦 Organizations, communities and groups
  - 👨‍👩‍👧‍👦 Family
  - ⚽️ Team
  - 🏘 Neighborhood
  - ♥️ Relationship
  - 💚 Friends
  - 🏢 Business
  - 💼 Professional
  - 🏛 Jurisdiction (Nation, State, City)
- ⏹ Resource
  - 🏠 Place
  - *️⃣ Credential/secret
  - 👛 Digital safe/wallet
    - 💎 Digital non-fungible valuable
- 🏃‍♂️ Runner
  - ⌚️Device [📱💻⌚️🚗🎧]
  - 🖱Browser
  - 📳 App/site

### 🔺🔌🤝🔸 Connection types

- 🕰🔌🤝 Long term connection
  - 🤝👥 Social connection (Contact)
    - 👨‍👩‍👧 Family
    - 💜 Friend
    - 👋 Acquaintance
  - 🤝🏢 Business connection (Subscription)
  - 🤝🏛 Jurisdictional connection (Government)
  - 🤝👨‍👦‍👦 Group connection (Membership)
- ⏱🔌 Short term connection
  - ⌚️🔌 Device connection
- ⬅️➡️ Direction
  - ➡️ 🔌 One way
  - ↔️ 🔌 Two way

### 🔒 Security level

- 🔓 None (~$0.01)
- 🔒 Low (~$1)
  - 🔒🌗 Medium low (~$100)
- 🔒🔒 Medium (~$10K)
  - 🔒🔒🌗 Medium high (~$1M)
- 🔒🔒🔒 High (~$100M)
  - 🔒🔒🔒🌗 Very high (~$10B)
- 🔒🔒🔒🔒 Extremely high (~$1T)

## 🔐 Cryptography schemes

- 🔏 Encryption method - Eg. RSA 2048-bit, ECC(ECDSA) 256-bit
- #️⃣ Hash function - Eg. Keccak256, SHA3, SHA-256

## 📋 Work scopes

- 🙍‍♀️ Customer/segment (e.g. Consumer, enterprise, etc)
  - 🛍 Market (e.g. contact management, customer verification, etc)
    - 🤳 Use case (e.g. Consumer establishing social connections (contacts))
      - 📦 Product (e.g. password management Add-in) or Solution
        - 🦸‍♀️ Epic [Scenario] (e.g. Consumer adding a new contact and setting privacy settings)
          - 🎛 Feature (e.g. Contact management UX on iOS)
            - 🚶‍♀️User story [Sub-scenario] (e.g. April adds new contact on iOS and Android)
              - ☑️ Task [Sub-feature] (e.g. Create form with button to add contact on iOS and Android)
