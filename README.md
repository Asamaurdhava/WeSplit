# WeSplit

A modern, intuitive iOS application for calculating and splitting bills with ease, built using SwiftUI.

---

## Overview

**WeSplit** simplifies the process of dividing a bill among multiple people and calculating tips. Designed with a clean and user-friendly interface, the app leverages SwiftUI’s latest features to provide real-time calculations and seamless user experience.

---

## Features

- **Bill Entry:** Input the total check amount with locale-aware currency formatting.
- **People Picker:** Select the number of people (2–99) to split the bill.
- **Tip Selection:** Choose from common tip percentages (10%, 15%, 20%, 25%, or 0%) using a segmented control.
- **Instant Calculation:** View the amount each person owes, including their share of the tip, updated in real time.
- **Keyboard Management:** Integrated “Done” button to conveniently dismiss the keyboard.
- **Responsive UI:** Structured layout using SwiftUI’s `Form` and `Section` components.

---

## Screenshots

![Initial - Without any Input](https://github.com/Asamaurdhava/WeSplit/blob/2519203c8ced800fe4d383e1256444309eaa3ca7/Initial.png) ![Working](https://github.com/Asamaurdhava/WeSplit/blob/1d11a6239cf1829ebf43ab7bab505beeb214052e/Working.png)

---

## Getting Started

### Prerequisites

- Xcode 15 or later
- iOS 17.0 or later

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/wesplit.git
   ```
2. **Open in Xcode**
   - Navigate to the project directory and open `WeSplit.xcodeproj`.

3. **Build and Run**
   - Select your target device or simulator and click **Run**.

---

## Usage

1. Enter the total bill amount.
2. Select the number of people sharing the bill.
3. Choose the desired tip percentage.
4. View the calculated amount each person needs to pay.

---

## Code Highlights

- Utilises `@State` for reactive UI updates.
- Implements `@FocusState` for managing keyboard focus.
- Employs SwiftUI’s declarative syntax for concise, maintainable code.
- Real-time calculations and locale-aware formatting for a polished user experience.

---

## Author

**Vishesh Singh Rajput <specstan>**

---

## License

This project is licensed under the [MIT License](LICENSE).

---

**If you found this project useful, please consider starring the repository.**

---

*For any queries or feedback, feel free to reach out via GitHub Issues.*
