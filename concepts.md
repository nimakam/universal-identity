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

## Common attributes

### 🔒 Security level

- 🔒0️⃣ None (~$0.01) [🔓]
- 🔒🔽 Low (~$1) [🔒]
  - 🔒⏺🔽 Medium low (~$100) [🔒🌗]
- 🔒⏺ Medium (~$10K) [🔒🔒]
  - 🔒⏺🔼 Medium high ($1M) [🔒🔒🌗]
- 🔒🔼 High (~$100M) [🔒🔒🔒]
  - 🔒⏫ Very high (~$10B) [🔒🔒🔒🌗]
- 🔒🔼⏫ Extremely high (~$1T) [🔒🔒🔒🔒]

### ✅ Trust/verification level

- ✅0️⃣ None (~$0.01) [❌]
- ✅🔽 Low (~$1) [✅]
  - ✅⏺🔽 Medium low (~$100) [✅🌗]
- ✅⏺ Medium (~$10K) [✅✅]
  - ✅⏺🔼 Medium high (~$1M) [✅✅🌗]
- ✅🔼 High (~$100M) [✅✅✅]
  - 🔒⏫ Very high (~$10B) [✅✅✅🌗]
- ✅🔼⏫ Extremely high (~$1T) [✅✅✅✅]

## Identity and connection

### 🆔🔵🔺🔸 Identity types

- 👨Human
  - 🌳 Root
  - 👩‍💻 User
    - ⌚️👨 Device user
  - 🌍 Public
  - 👤 Abstract
    - 👤👨‍👩‍👧‍👦💚💼 Contextual
    - 👤🧢 Dedicated (Per-subscription) (per long term connection) [🧑‍🎨]
    - 👤🕶 Masked/alias [🦸]
    - 👤👺 Anonymous [💀👻]
      - 👤👺🧢 Pseudo-anonymous [🦹🎩]
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

### 🆔🏗 Identity (structure)

- 🆔 Identifier (DID)
- 🤴🆔 Owner identity
- 👨‍✈️🆔 Operator identities
- 🗣🆔 According to identity (stack)
- 🧳 Properties
  - ℹ️ Information
  - 🎬 Actions
- ↖️🆔ℹ️ Reference/template identity information
- 🛡🆔 Guardian identities (and terms)
- 🤖🆔 Delegate (agent) identities
  - 🎬👍 Actions permissions
- ⤴️ References
  - 🤖🤴🆔 Patron (on-behalf-of) identities  

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

### 🔌🏗 Connection structure

- ⬅️➡️ Direction
  - ➡️🆔 Start identity
  - ⬅️🆔 End identity
- 🤴🆔 Owner identity
- 👨‍✈️🆔 Operator identity
- ⏱⌛️ Time constraints
- ✅📶 Trust level
- 🔒📶 Security level
- ☎️ Communications/notifications
- 🎬Actions
- ✍️🆔 Guarantor identity (and terms)
  - ⤴️ References
    - 🔌⤴️ Parent connections (if applicable)

### 🆔✳️ Identity context

- 🧠🆔 Known identities
- ✅🆔 Trusted identities
- 🔌 Connections
- 🏃‍♂️🆔 Runner identity
- 👨‍✈️🆔 Operator identity
- 👩‍💻🆔 User identity
- ✳️⤴️ Parent context (if applicable)
- ☎️ Communications/notifications
- 🎬Actions

## 📋 Deliverable levels

- 🙍‍♀️ Customer/segment (e.g. Consumer)
  - 🛍 Market (e.g. Social connection)
    - 🤳 Use case (e.g. Consumer establishing social connections)
      - 📦 Product (e.g. password management Add-in) or Solution
        - 🦸‍♀️ Epic [Scenario] (e.g. Consumer adding a new contact and setting privacy settings)
          - 🎛 Feature (e.g. Contact management UX on iOS)
            - 🚶‍♀️User story [Sub-scenario] (e.g. April adds new contact on iOS and Android)
              - ☑️ Task [Sub-feature] (e.g. Create form with button to add contact on iOS and Android)

## Transitions

### Identity transition

- Create
- Revoke
- Replace
- Terminate
- Merge
- Split
- Shceduled vs. immedeate
- Versioned - Single version vs parallel
  - VCurrent
  - Schedule finalized - parallel start, parallel deadline, vNext primary start, vNext primary deadline, vCurrent deprecation deadline
  - Parallel transition - VCurrent -> [VCurrent + VNext]
    - VCurrent primary
    - VNext primary
  - Final transition - [VCurrent + VNext] -> VNext

### Key transition

- Issue
- Rotation
  - Schedule
  - Execute
- Revoke

## Information ownership

### Owned information types

- Identity information
  - Property information - eg. Name, email, phone, address, identifier, etc
    - Identifier - eg. Decentralized identifier (DID)
  - Connection information - Eg. Endpoint identity, knowledge, category: friend, acquaintance
  - Meta information
    - Claims and attestations - eg. Owner exclusively controls X facebook account, confirmation of control @ Y time.
    - Notification and request - eg. Friend X has requested connection    
    - Audit information - Eg. Z accessed A private key for signing request B @ C time
  - Identity links - Eg. Root identity, public identity
    - Public key information
    - External identifier
  - Securability
    - Private - eg. Password/credentials
    - Selective sharing - eg. Address shared with friends and family
    - Public - eg. Name, public profiles  
- Shared ownership information - eg. Usage, transaction documents, communication 
  - Scope
    - Public
    - Group
    - Connection

### Information ownership metadata

- Single ownership
  - Digital/connected persistence policy
    - Indefinite - eg. Decentralized identifier
    - Until revoked - eg. Phone number
    - Limited time - eg. Phone number for 1 month until extended
    - Never (Just-in-time retrieval) 
      - Retreive and notify - eg. Address retrieved at time of mailing
      - Retrieve by permission - eg. Credit card number to process transaction
- Shared ownership
  - Media - Image, video, article, etc
  - Digital persistence policy
    - Indefinite - eg. Session identifier, Total purchases / year
    - Until revoked - eg. Aggregate usage information: total interactions / month
    - Limited time - eg. Detailed usage information (clicks and times) for 1 month until extended, communication for 2 years  
  - Public scope licensing
    - Usage - Public, commercial
    - Modification
    - Distribution

## Cryptography schemes

- Encryption method - Eg. RSA 2048-bit, ECC(ECDSA) 256-bit
- Hash function - Eg. Keccak256, SHA3, SHA-256