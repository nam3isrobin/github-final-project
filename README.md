# Simple Interest Calculator

A simple and efficient Bash command-line calculator designed to compute simple interest based on user input for principal amount, rate of interest, and time period in years.

---

## 📌 Project Overview

The **Simple Interest Calculator** calculates the accrued simple interest based on the standard financial formula:

$$\text{Simple Interest} = \frac{P \times R \times T}{100}$$

Where:
- **`p`**: Principal amount (the initial sum of money borrowed or invested)
- **`r`**: Annual rate of interest (percentage per year)
- **`t`**: Time period in years

---

## 🧮 Input & Output Specification

```text
Input:
   p, principal amount
   r, annual rate of interest (per year)
   t, time period in years

Output:
   simple interest = (p * t * r) / 100
```

---

## 🚀 Getting Started

### Prerequisites

- Bash shell environment (`bash 4.0+`)
- Standard Unix utilities (`expr`)

### Installation & Execution

1. **Clone the repository:**
   ```bash
   git clone git@github.com:nam3isrobin/github-final-project.git
   cd github-final-project
   ```

2. **Make the script executable:**
   ```bash
   chmod +x simple-interest.sh
   ```

3. **Run the script:**
   ```bash
   ./simple-interest.sh
   ```

---

## 💻 Example Walkthrough

```text
$ ./simple-interest.sh
Enter the principal:
1000
Enter rate of interest per year:
5
Enter time period in years:
2
The simple interest is: 
100
```

---

## 📜 Project Documentation & Standards

- **[LICENSE](LICENSE)**: Licensed under the [Apache 2.0 License](LICENSE).
- **[CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)**: Community standards and enforcement guidelines following the Contributor Covenant.
- **[CONTRIBUTING.md](CONTRIBUTING.md)**: Guidelines for opening issues, submitting pull requests, and contributing to the project.

---

## 👥 Authors

- **Upkar Lidder** (IBM) - Original Author
- **Rabinarayan Sethy** ([@nam3isrobin](https://github.com/nam3isrobin)) - Contributor

---

_© 2026 XYZ, Inc. / IBM Developer Skills Network_
