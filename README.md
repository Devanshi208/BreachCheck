🔐 BreachCheck: Password Strength & Breach Checker

BreachCheck is a browser based security tool that checks whether a password is strong and whether it has ever appeared in a real, known data breach, without your actual password ever leaving your browser.

🚀 Live Demo

See it in action here:  https://devanshi208.github.io/BreachCheck/

✨ Features
Live Strength Meter: Real entropy-based scoring (measured in bits), not a fake progress bar, penalizes common passwords and keyboard-walk patterns, rewards length and character variety.

Real Breach Lookup: Checks against Have I Been Pwned's Pwned Passwords database, over 555 million real passwords from actual historical breaches.

Zero Plaintext Transmission: Uses k-anonymity, your password is hashed locally in-browser, and only the first 5 characters of that hash are ever sent over the network.

Transparent by Design: An expandable panel shows your password's hash being generated live, visually splitting it into the "sent" and "kept private" portions.

🛠 Built With
HTML5
CSS3 (Responsive UI)
JavaScript
Web Crypto API (SHA-1 hashing)
Have I Been Pwned Pwned Passwords API

👤 Author
Devanshi - GitHub Profile
