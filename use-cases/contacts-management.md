# 📇 Contacts management <!-- omit in toc -->

- Adding and managing contacts from phone and social networks
- Connecting with others and exchanging contacts and personal information
- Searching, browsing and using contacts

Outline:

- [References](#references)
- [📦 Products and solutions](#%f0%9f%93%a6-products-and-solutions)
- [🦸‍♀️ Epics](#%f0%9f%a6%b8%e2%80%8d%e2%99%80%ef%b8%8f-epics)
- [🎛 Features](#%f0%9f%8e%9b-features)
- [🚶‍♀️ User stories](#%f0%9f%9a%b6%e2%80%8d%e2%99%80%ef%b8%8f-user-stories)
  - [📇👤⚙️ Profile setup](#%f0%9f%93%87%f0%9f%91%a4%e2%9a%99%ef%b8%8f-profile-setup)
  - [📇🤜🤛 Connect](#%f0%9f%93%87%f0%9f%a4%9c%f0%9f%a4%9b-connect)
  - [📇ℹ️↖️ Sharing](#%f0%9f%93%87%e2%84%b9%ef%b8%8f%e2%86%96%ef%b8%8f-sharing)
  - [📇🔍 Search and browse](#%f0%9f%93%87%f0%9f%94%8d-search-and-browse)
  - [📇👍🔔 Notifications](#%f0%9f%93%87%f0%9f%91%8d%f0%9f%94%94-notifications)
  - [📇👤⚙️ Profile update](#%f0%9f%93%87%f0%9f%91%a4%e2%9a%99%ef%b8%8f-profile-update)
  - [📇👥➕ Add and manage contacts](#%f0%9f%93%87%f0%9f%91%a5%e2%9e%95-add-and-manage-contacts)
  - [📇👥✔️ Quick merge](#%f0%9f%93%87%f0%9f%91%a5%e2%9c%94%ef%b8%8f-quick-merge)
  - [📇⬇️ Import](#%f0%9f%93%87%e2%ac%87%ef%b8%8f-import)
  - [📇👥✔️ Bulk merge](#%f0%9f%93%87%f0%9f%91%a5%e2%9c%94%ef%b8%8f-bulk-merge)
  - [📇👤🔒 Maintain security](#%f0%9f%93%87%f0%9f%91%a4%f0%9f%94%92-maintain-security)
- [🗺 Interface map](#%f0%9f%97%ba-interface-map)

## References

- [Use cases entry](../use-cases.md#📇-social-connections)
- [🙍‍♀️ Customers] > [🙍‍♀️ Consumer] > [🛍 Markets] > [🙍‍♀️📇 Social connections] > [🤳 Use cases] > [🙍‍♀️📇 Social connection management]`

## 📦 Products and solutions

- 📱 Sample mobile app
- ☁ Sample service
- 👨‍✈️☁ Operator service
- 🌐 Sample web app
- ⛓📝 Blockchain contracts

## 🦸‍♀️ Epics

- Level 100
  - 📇👤⚙️ [Support] Identity setup - Set up profile identity and personal information
  - 📇🤜🤛 Connect - Connecting with others and exchange information
  - 📇ℹ️↖️ Sharing - Share contacts and personal information
  - 📇🔍 Search and browse - Search and browse contacts
- Level 200
  - 📇👍🔔 [Support] Notifications - View and respond to requests and notifications
  - 📇👥➕ Add and manage - Add and manage contacts
  - 📇👤⚙️ Profile update - Check what people see and update profile
  - 📇👥✔️ [Dialog] Quick merge - Quickly organize and merge contacts
  - 📇⬇️ Import - Import contacts from phone and other networks
- Level 300
  - 📇👥✔️ [Dialog] Bulk merge - Organize and merge contacts in bulk
  - 📇👤🔒 [Dialog] Maintain security - Maintain the security of your identity's connection to Universal Identity protocol
  - Inspect privacy of information with respect to contacts

## 🎛 Features

- 📱 App
  - ⚙️ Settings section
  - ⏹ Splash-screen
  - 🏁🧙‍♂️ Setup wizard
  - 🌐🔗 Deep linking
  - 📰👥 Social login bootstrap
  - 📱👥⬇️ Phone contact import
  - 🔒🎰 Secure cryptography module
  - 🗝🗄 Secure key storage and access
  - 🔔 Notifications (and requests) subsystem
  - 👥 Contacts section
- ☁ Service
  - 👤🗄 User storage and access
  - 🔔🗄 Notification and request storage and access
- 👨‍✈️☁ Operator service
  - 🆔🗄 Identity storage and access
  - ℹ️🗄 Personal information storage and access
  - ⛓🌉 Blockchain bridge
- 🌐 Web app
  - 📋 Administration section
  - 🌐🔗 Deep linking
  - 🌐📰 Social login bootstrap
  - Mobile app bootstrap hand-off
  - 👥 Contacts section
  - Medium security key storage and access
- ⛓📝 Contracts
  - Protocol
  - Operator
  - Identity

## 🚶‍♀️ User stories

### 📇👤⚙️ Profile setup

- 🏁⚙️ First time setup - Consumer opens the app for first time and sets up her user identity - [link](social-connections/user-stories/first-time-setup.md)
- Consumer discovers the app through a contact link
- Consumer uses app to import known identities
- Consumer re-opens the app

### 📇🤜🤛 Connect

- Consumer invites someone to connect using a QR code
- Consumer invites someone to connect by sending a URI through existing messaging connection (Text, IM,  etc)
- Consumer invites someone to connect using NFC tapping of phones

### 📇ℹ️↖️ Sharing

- Consumer shares her own contact with others using a link
- Consumer shares specific personal information with specific contact(s)
- Consumer shares connected contact(s) with another contact
- Consumer requests additional personal information from specific contact

### 📇🔍 Search and browse

- Consumer searches for contact by typing a name
- Consumer browses contacts by connection type or category (favorites, family, friend, etc)

### 📇👍🔔 Notifications

- Consumer accepts request sharing personal information with an new contact
- Consumer accepts request sharing new personal information with an existing contact
- Consumer is notified that specific contact is now shared with her
- Consumer is notified that specific personal information is now shared with her

### 📇👤⚙️ Profile update

- Consumer views and edits root personal information
- Consumer sets up contextual personal identity with selective information

### 📇👥➕ Add and manage contacts

### 📇👥✔️ Quick merge

### 📇⬇️ Import

### 📇👥✔️ Bulk merge

### 📇👤🔒 Maintain security

## 🗺 Interface map

- 📱 App
  - ⏹ Splash-screen
  - 🗂 Sections
    - 👥 Contacts
      - 👤 Contact
        - View (default)
        - ✏️ Update
        - ↖️ Share
        - Merge
    - 🤜🤛 Connect
      - 🤜🤛📶 (Connect) now
      - 🤜🤛？↖️ Request
    - ↖️ Share
      - ↖️👤 Contact
      - ↖️ℹ️ (Personal) information
    - 🔔 Notifications (and requests)
      - *️⃣ All
      - 🎛👤 Filter (by contact)
  - 🔝 Headers
    - 🧑 Me/self
      - 🆔 Identities
      - ℹ️ (Personal) information
      - 🔗 Links
    - ⚙️ Settings
  - Dialogues
  - Wizards
    - Identity setup
      - Identify yourself
        - Legacy login (Facebook etc.)
        - First time (Universal identity)
          - Legacy login (Facebook etc.)
          - Manual entry and verification - Name, profile image, phone, email
        - Existing identity
  - States
    - Unidentified
    - Identified
      - Per ID network
        - Unlinked
        - Linked
          - Not imported
          - Imported
      - Identity security
        - Start (Low) - OK, Requires securing action
        - Medium
        - High
      - Usage stage
        - Adding and importing
        - Using
          - Organizing
          - Streamlined
  - Recorded actions
    - Imports - total launches, total contacts, per source, last date time per source
    - Add - total
    - Merge/organization - total launches, total contacts, last date time
    - Contact history - information changes, transitions (merges etc)
- 🌐 Web app
  - 👥 Contacts
  - 🔔 Notifications (and requests)
  - 📋 Administration
