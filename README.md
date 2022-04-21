# Tauri Build Failure with Framework

When a macOS framework is added, and that framework contains symlinks, the build fails when the updater tries to build a .tar.gz

- Clone this repo
- yarn install
- yarn build
- It should fail

This repo links to a framework in Chrome under "/Applications/Google Chrome.app". If you don't have Chrome installed, linking to any other framework will work fine to demonstrate the problem.
