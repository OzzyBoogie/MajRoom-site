# MajRoom

MajRoom is a **Rust backend + native apps** Riichi Mahjong scoring project. The core scoring engine is implemented in Rust and exposed to native platforms via UniFFI; iOS is built with SwiftUI and Android uses Jetpack Compose.

## Features

- Riichi scoring: Han/Fu, yaku list, dealer/non-dealer payments
- Wait and shanten calculation
- Native integration: iOS already wired to the Rust library; Android is currently a base UI skeleton

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
