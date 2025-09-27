# Contributing Guidelines

Thank you for considering contributing to this project! We welcome contributions from everyone.

## How to Contribute

1. Fork the repository.
2. Clone your fork:

```bash
git clone https://github.com/dhokabhoomi/simple-interest-calculator.git
```

## Create a new branch:

```bash
git checkout -b feature/your-feature-name
Make your changes and commit:
```

```bash
git add .
git commit -m "Describe your changes"
```

## Push your branch:

```bash
git push origin feature/your-feature-name
```

## Open a Pull Request.

### Guidelines

- Write clear commit messages.
- Test your changes before submitting.
- Follow the existing code style.

```bash
---
```

## **5. simple-interest.sh**

```bash
#!/bin/bash
# Simple Interest Calculator

echo "Enter Principal (P):"
read P
echo "Enter Rate of Interest (R in %):"
read R
echo "Enter Time (T in years):"
read T

# Calculate Simple Interest
SI=$((P * R * T / 100))
echo "Simple Interest: $SI"
Make sure to give execute permission to the script:

bash
Copy code
chmod +x simple-interest.sh
```
