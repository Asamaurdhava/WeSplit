# WeSplit

WeSplit is a SwiftUI-based iOS application created as a learning exercise, following the [100 Days of SwiftUI](https://www.hackingwithswift.com/100/swiftui) course by Paul Hudson. The app demonstrates bill splitting with flexible tip calculation, real-time updates, and a clean, modern interface.

---

## Overview

**WeSplit** allows users to:
- Enter a bill amount
- Select the number of people sharing the bill
- Choose any tip percentage (0%–100%)
- Instantly view the total bill (including tip)
- See the amount each person should pay

The app leverages SwiftUI’s latest navigation and form components, providing a seamless and intuitive experience.

---

## Features

- **Flexible Tip Selection:** Choose any tip percentage from 0% to 100% using a navigation-style picker.
- **Dynamic Calculations:** Instantly displays both the total bill (with tip) and per-person amount.
- **Locale-Aware Currency:** All amounts are formatted in the user’s local currency.
- **Keyboard Management:** “Done” button in the toolbar for smooth data entry.
- **Modern UI:** Utilises SwiftUI’s `NavigationStack`, `Form`, and sectioned layout for clarity and ease of use.

---

## Screenshots

*Add screenshots or GIFs here to showcase the app’s interface and features.*

---

## Getting Started

This repository is for demonstration and educational purposes only, as part of the 100 Days of SwiftUI course.  
**The source code is provided for learning and portfolio presentation. It is not intended for commercial use, redistribution, or derivative works without adhering to the original course’s terms and the author’s guidelines.**

If you wish to use or extend this code beyond personal learning, please refer to [Paul Hudson’s licensing and usage policy](https://www.hackingwithswift.com/terms) or contact him directly.

---

## Usage

1. Enter the bill amount in the “Amount” field.
2. Select the number of people sharing the bill.
3. Choose your desired tip percentage (0%–100%).
4. View the “Original Amount plus tip” and “Amount per person” sections for real-time results.

---

## Code Highlights

- **State Management:**  
  Uses `@State` for reactive UI updates and `@FocusState` for keyboard focus.
- **Custom Tip Picker:**  
  Allows selection of any tip percentage from 0 to 100.
- **Real-Time Calculations:**  
  - `originalAmount`: Computes the total bill including tip.
  - `totalPerPerson`: Calculates each person’s share.
- **SwiftUI Best Practices:**  
  Clean, sectioned forms and navigation for a professional look and feel.

---

## Acknowledgements

This project is based on [Paul Hudson](https://twitter.com/twostraws)’s [100 Days of SwiftUI](https://www.hackingwithswift.com/100/swiftui) course.  
All credit for the original concept, structure, and educational content goes to Paul Hudson and the Hacking with Swift community.  
This repository is intended solely for personal learning and demonstration.

---

## Author

**Vishesh Singh Rajput aka specstan**

---

## License & Usage

**Educational Use Only.**

This repository is a student implementation of Paul Hudson’s tutorial and is not licensed for commercial use or redistribution.  
For any other use, please consult the [original course terms](https://www.hackingwithswift.com/terms) or contact Paul Hudson.

---

## Contributing

This project does not accept external contributions.

---

**For queries about this repository, please contact the author. For questions about the original course or code, please refer to Paul Hudson’s official channels.**
