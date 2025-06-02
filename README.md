<p align="center">
  <img src="./images/secure-vault-logo-3x.png" alt="secure vault brand" width="400"/>
</p>

<h1 align="center">SECURE VAULT - THE ONLY KEY IS YOU</h1>

<br>

**Secure Vault** is a privacy-focused application designed to safeguard your passwords, documents, and other confidential information. It's built with end-to-end encryption, ensuring that only you have access to your data. We never have access to your passwords or sensitive information. 

This project is built with full-stack ownership and security-first architecture, combining:

- A responsive **React + Next.js** web app
- A robust **Spring Boot + Java** backend with Redis caching
- JWT-based authentication and OAuth2 support
- Modular codebase structured for future extensibility (e.g., mobile client, multi-device sync)

> 🛠️ **Status**: Actively in development — core features are live, and I’m continuing to add secure sharing, MFA, vault tagging, and mobile client support.

## ⚗️ Key Features:

* **Zero-Knowledge Encryption**: All data is encrypted client-side and remains unreadable even to the server.
* **Master Password Security:** Your master password is the only key to unlocking your vault.
* **Secure Storage:** Keep all your valuable data safe and organized in one place.
* **Internationalization (i18n)**: Designed for global use with localized support.
* **Secure Sharing (In Progress)**: Share vault items safely using time-bound, encrypted share links.
* **Multi-Platform Support (In Progress)**: Works on web, and mobile support is being developed with React Native.

## Why Choose Secure Vault?

* **Ultimate Privacy:** Your data is your business. We don't have access to it.
* **Peace of Mind:** Securely store and manage your most important information.
* **Easy to Use:**  A user-friendly interface makes it simple to manage your vault.
* **Open Source:**  We welcome community contributions to make Secure Vault even better.

## Repository Structure

This repository is the umbrella project containing:

* [Secure Vault Server](https://github.com/puneetkakkar/secure-vault-server) - Spring Boot backend

* [Secure Vault Web](https://github.com/puneetkakkar/secure-vault-web) - Next.js + React web frontend

* [Secure Vault Mobile](https://github.com/puneetkakkar/secure-vault-mobile) - React Native mobile app (WIP)

Each repo is independently deployable and designed for modular, team-based development.

## Getting Started:

To set up and run the Secure Vault application, navigate to the respective repository and follow the installation steps outlined in its README file.

**Cloning All Repositories:**
If you wish to clone all repositories together, run:

```bash
# Clone the main repository
git clone https://github.com/puneetkakkar/secure-vault
cd secure-vault

# Clone submodules (each component)
git submodule update --init --recursive
```
Alternatively, you can navigate to each repository and clone them individually.

## Contributing

We encourage you to contribute to Secure Vault's development!

* **Report issues:** Find a bug or have a suggestion. Please submit an issue on GitHub.
* **Submit pull requests:**  Want to add a feature or fix a bug? Submit a pull request to our repository.
* **Join the community:**  Connect with other developers.

**Before contributing:**

* Please read our [Contributing Guidelines](CONTRIBUTING.md) for a detailed guide.
* Ensure you have signed our Contributor License Agreement (CLA). 

## License

This project is licensed under the [License Name] License - see the [LICENSE](LICENSE) file for details.

**Together, let's make Secure Vault the ultimate solution for protecting your digital secrets!**
