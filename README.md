# CyberChef PE

## **Disclimer
This is not indorsed by CyberChef nore is it official. If SOme issues are resolved (being able to compile cyberchef source code) then I may make a pull request, but until them use at your own risk. 

## Goals

1) Make a portable cyberchef application that can be used on all platforms
2) Develope scripts or github actions that automate pulling of cyberchef's JavaScript (post build) and build up-to date applications.


## What is this?
This is a simple repository that I utilize to build cyberchef in <a href="https://github.com/tauri-apps/tauri">Tauri</a>. Tauri is a Rust/JavaScript framework for building simple, secure, and fast applications. I currently have a workign GitHub actions that builds applications for Windows, Linux, and IOS. It dose require a copy of the current released CyberChef JavaScript files.

## Building
Local:

Make sure to have node installed on your local machine. 

```bash
git clone https://github.com/Fra3zz/CyberChefPE.git
cd CyberChefPE
bun install # or "bun i"
bun run tauri build #This will build for your loacl OS. npm/Deno/Yarn can be used
```

GitHub Actions
1) Fork my repo (and add to it if you would like)
2) Run github action


## Credits
- CyberChef is an amazing application for all types of cryptography, encryption, decryption, formating and more. Their GitHub can be found <a href="https://github.com/gchq/CyberChef">here</a>. This is where the source code comes from for tuari to compile the applications. Check them out and star them.

# Contributing to the Repo
- Make a pull request with a detailed explination of your changes. Due to time restraints, it might take me some time (Not really long but not really fast) before I approve the pull request.
- Like always, this is open for everyone to use.