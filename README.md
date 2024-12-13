# passwordgeneratorc-

Overview
The Advanced Password Generator is a robust Windows Forms (.NET Framework) application designed to create highly secure and customizable passwords. This final iteration includes multiple enhancements over a standard password generator by offering multilingual support, advanced password selection criteria, improved UI/UX, accessibility options for color-blind users, and additional features to aid in user understanding and convenience.

Key Features
Rich Character Set Configuration

Multiple Character Types: Easily include or exclude uppercase letters, lowercase letters, digits, and special characters.
User-Defined Characters: Add custom characters or symbols to tailor your password to specific requirements.
Exclude Similar and Ambiguous Characters: Improve readability and reduce errors by removing characters that look alike or are often confused.
Enhanced Password Quality and Professional Logic

Secure Random Generation: Uses cryptographically secure RNG for generating truly random passwords.
Guaranteed Character Inclusion: Ensures that if a category (e.g., uppercase) is selected, at least one character from that category will appear in the final password.
Entropy Calculation: Displays entropy (in bits) to gauge the true complexity and unpredictability of the generated password.
Complexity Scoring: A numerical complexity score, combined with a progress bar, provides quick visual feedback on the strength of the password.
Memorable Passphrase Suggestion

Passphrase Generation: Offers an alternative method to generate memorable, phrase-like passwords composed of randomly chosen words separated by a dash.
Simple Word List Integration: Drawn from an internal dictionary of words, making it easy to remember yet still secure.
Multilingual Support

Language Options: Seamlessly switch between English, Spanish, and Bulgarian through a language drop-down menu.
Dynamic UI Updates: All labels, buttons, and hints update instantly when changing the language.
Improved User Interface and Accessibility

Show/Hide Password: Toggle between masked and unmasked password display to prevent shoulder-surfing and to verify password correctness.
Color-Blind Friendly Themes: Choose from "Default," "High Contrast," and "Color-Blind Friendly" themes to enhance readability and accessibility.
Tooltips: Hover over key UI elements (like complexity score and entropy) to get concise explanations.
Organized Layout: A clearly structured layout groups related settings together and uses intuitive labels and controls.
Utility Features

Password History: A running list of previously generated passwords allows you to revisit, reuse, or compare them.
Copy to Clipboard: Quickly copy the currently displayed password to the clipboard.
Save to File: Save the generated password to a text file for future reference or secure storage.
Robust Error Handling and Logging

Graceful Error Reporting: Catches exceptions and informs the user with an error message while continuing program execution.
Backend Logging: Logs detailed error information to error_log.txt, enabling developers to diagnose and fix issues without disturbing the user experience.
How It Works
Select Your Criteria:
Choose your desired password length and character types. Optionally, add your own characters and decide whether to exclude confusing or ambiguous ones.

Generate Password:
Click "Generate Password" to produce a random, secure password that meets your specified criteria. The application ensures each selected character category is represented.

Evaluate Complexity:
View the complexity score and entropy to understand how strong the password is. The complexity progress bar and color-coded score give instant visual feedback.

Theme & Accessibility:
Change the interface theme to accommodate color-blindness or switch to high contrast for better visibility. Language and theme changes apply instantly to the UI.

Save, Copy, or Review History:
Copy the password to your clipboard, save it to a file, or browse through the history of previously generated passwords. Choose the passphrase option to generate a more memorable password if desired.

Code Structure and Quality
Modern C# Conventions: Follows C# coding standards with clear naming conventions, logical code grouping, and partial classes for form and designer code.
Extensible and Maintainable: The architecture allows easy updates to supported languages, character sets, or UI theming options.
Secure Practices: Uses RNGCryptoServiceProvider for cryptographically strong random number generation and avoids predictable patterns.
System Requirements
Platform: Windows, .NET Framework (4.7.2 or later recommended)
IDE: Visual Studio (2017 or later), or equivalent .NET Framework-compatible environment.
