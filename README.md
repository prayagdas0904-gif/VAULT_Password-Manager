# Vault

A native Android password organizer built with Kotlin + Jetpack Compose.



## Features

* PIN-protected vault
* Encrypted local storage using AES-GCM
* Android Keystore-backed encryption key
* PIN verification using PBKDF2
* Credential categories
* Search
* Favorites
* Add, edit, and delete credentials (edit preserves the credential ID and favorite status)
* Password show/hide
* Copy username/password
* Private/visible setting
* Auto-lock when the app leaves the foreground
* Basic failed-PIN cooldown
* Plain-text TXT export with a clear security warning
* Encrypted vault backup/export
* Minimal white/black/lavender UI



## Important security note

This is a personal use project, not a professionally audited password manager.
The project is configured for Java/Kotlin JVM 17.

