# 📊 Incubyte TDD Assessment

A **String Calculator** built with **Ruby** using **Test-Driven Development (TDD)** methodology.

## 🌟 Features

- **Returns `0`** for an *empty string*  
- **Computes the sum** of *comma-separated numbers*  
- **Supports multiple numbers** and *newline (`\n`) delimiters*  
- **Allows custom delimiters** using the format: `//[delimiter]\n[numbers]`  
- **Raises an exception** for *negative numbers*, displaying the invalid inputs  

## 🛠️ Installation & Usage

### 1. Clone the Repository

```bash
git clone https://github.com/sauravgr458/incubyte-assessment-tdd.git
cd incubyte-assessment-tdd
```

### 2. Install Dependencies

```bash
bundle install
```

### 3. Run Tests

```bash
rspec spec/
```

## 📚 How It Works

1. *Input a string of numbers* (e.g., `"1,2,3"`).
2. *The calculator sums the numbers* and returns the result.
3. *Custom delimiters* can be specified using the `//[delimiter]` syntax.
4. *Negative numbers raise an error*, listing all invalid inputs.

## 📌 Example Inputs & Outputs

| **Input**              | **Output** | **Notes**                        |
|------------------------|------------|----------------------------------|
| `""`                   | `0`        | *Empty input returns zero*       |
| `"1,2,3"`              | `6`        | *Sums comma-separated numbers*   |
| `"1\n2,3"`             | `6`        | *Supports newlines as delimiters*|
| `"//;\n1;2;3"`         | `6`        | *Custom delimiter (`;`)*         |
| `"-1,2,-3"`            | *Error*    | *Lists negative numbers: `-1, -3`* |

## 📣 Contributions

Feel free to *fork the repository*, open *issues*, or submit *pull requests* to enhance the project!

---

💡 **Happy Coding!**
