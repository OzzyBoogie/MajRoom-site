# MajRoom

MajRoom is a **Rust backend + native apps** Riichi Mahjong scoring project. The core scoring engine is implemented in Rust and exposed to native platforms via UniFFI; iOS is built with SwiftUI and Android uses Jetpack Compose.

## Features

- Riichi scoring: Han/Fu, yaku list, dealer/non-dealer payments
- Wait and shanten calculation
- Native integration: iOS already wired to the Rust library; Android is currently a base UI skeleton

## Privacy Policy

This app does not collect, store, or share any personal data.

### Information Collection
No personal information is collected by this app.

### Data Usage
Since no data is collected, no data is used.

### Third-Party Services
This app does not use any third-party services that collect user data.

### Contact
If you have any questions about this privacy policy, please contact us via the GitHub repository.

## Project Structure

- `Rust/` Rust scoring core and CLI
  - `src/` scoring and hand parsing
  - `generated/` UniFFI generated bindings
  - `Mahc/` Swift Package (includes `RustFramework.xcframework`)
- `iOS/` iOS native app (SwiftUI)
- `Android/` Android native app (Jetpack Compose)
- `Pytorch/` placeholder/experiments (currently empty)

## License

BSD-3-Clause
<img width="1206" height="2622" alt="Simulator Screenshot - iPhone 17 - 2026-02-06 at 19 10 46" src="https://github.com/user-attachments/assets/75f13c3f-db01-4736-8766-bd9c67696df7" />
<img width="1206" height="2622" alt="Simulator Screenshot - iPhone 17 - 2026-02-06 at 19 11 03" src="https://github.com/user-attachments/assets/80ac508e-212e-43de-bff4-5babf28b7401" />
<img width="1206" height="2622" alt="Simulator Screenshot - iPhone 17 - 2026-02-06 at 19 10 24" src="https://github.com/user-attachments/assets/1cdb6a13-a808-4b54-98a6-f6a6dd2892ff" />
<img width="1206" height="2622" alt="Simulator Screenshot - iPhone 17 - 2026-02-06 at 19 10 26" src="https://github.com/user-attachments/assets/2c00828f-307f-4e43-9e11-2c9f3ba5bab4" />
