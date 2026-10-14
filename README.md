# 💱 Live Currency Converter

A real-time currency conversion native macOS and iOS application built with SwiftUI. This project demonstrates modern Swift concurrency, REST API integration, and advanced UI styling using liquid glassmorphism.

## ✨ Features
* **Global Exchange Rates:** Fetches live cross-rates for over 160 circulating currencies using the open ExchangeRate-API.
* **Liquid Glass UI:** Implements a dynamic, animated ambient background utilizing `.ultraThinMaterial` for realistic glass refraction.
* **Automated Polling:** Silently refreshes exchange rates in the background every hour using Combine's `Timer.publish`.
* **Interactive State:** Features a spring-animated currency swap function for rapid bidirectional conversion.

## 🛠 Tech Stack
* **Language:** Swift 5
* **Framework:** SwiftUI
* **Concurrency:** `async/await` and `@MainActor` thread management
* **Networking:** `URLSession` and native `Codable` JSON parsing
* **Reactive Engine:** Combine

## 🚀 Running Locally
1. Clone the repository to your Mac.
2. Open `LiveCurrency.xcodeproj` in Xcode.
3. Select an iOS Simulator destination and press `Cmd + R` to build and run.
