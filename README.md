# Vault (Folia Support)

This is a custom fork of [Vault](https://github.com/MilkBowl/Vault) updated to support [Folia](https://github.com/PaperMC/Folia) and modern Minecraft versions (1.21.1+).

Vault is a Chat, Permissions & Economy API to allow plugins to more easily hook into these systems without needing to hook each individual system themselves.

## 🚀 Features

*   **Folia Support:** Fully compatible with Folia's regionized threading model.
*   **Modern Server Support:** Updated for Minecraft 1.21.1 and Java 21.
*   **API Compatibility:** Maintains the standard Vault API for seamless plugin integration.

## 📦 Installation

1.  Download the latest `Vault.jar` release.
2.  Place the jar into your server's `plugins` folder.
3.  Ensure you have a compatible Economy, Chat, or Permission plugin installed.
4.  Restart your server.

## 🛠️ Usage for Developers

To use Vault in your plugin, add the following dependency to your `pom.xml`:

```xml
<dependency>
    <groupId>com.github.MilkBowl</groupId>
    <artifactId>VaultAPI</artifactId>
    <version>1.7</version>
    <scope>provided</scope>
</dependency>
```

Add the JitPack repository:

```xml
<repositories>
    <repository>
        <id>jitpack.io</id>
        <url>https://jitpack.io</url>
    </repository>
</repositories>
```

## 🤝 Credits

*   **Original Author:** [MilkBowl](https://github.com/MilkBowl) (The original Vault team)
*   **Folia Support Update:** h2ph

This project is open-source and based on the original Vault repository.
