---
"tauri-bundler": minor:breaking
---

The macOS notarization now uses `notarytool` as `altool` will be discontinued on November 2023. When authenticating with an API key, the key `.p8` file path must be provided in the `APPLE_API_KEY_PATH` environment variable.
