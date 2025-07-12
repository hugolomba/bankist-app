# 💳 Bankist App

A **fictional digital banking** project built in **JavaScript**, simulating real-world banking operations like login, transfers, loan requests, and account closure. This app was developed studying **array methods**, **DOM manipulation**, **event handling**, and modern JavaScript best practices.

## 🚀 Features

- **Login with username and PIN**
- **Dynamic balance and transaction display**
- **Money transfers between accounts**
- **Loan request with eligibility check**
- **Account closure functionality**
- **Financial summary** (incomes, expenses, and interest)
- **Sort transactions in ascending/descending order**
- **Logout timer** (in progress)

## 🛠️ Technologies and Skills Demonstrated

### 📌 HTML & CSS

- Semantic HTML structure
- Interactive forms and buttons
- Clean layout with top navigation and operation sections
- External fonts and favicon integration

### 📌 JavaScript (ES6+)

- **DOM manipulation**: `querySelector`, `textContent`, `insertAdjacentHTML`, `style.opacity`, etc.
- **User interactions and event handling**: `addEventListener` for login, transfer, loan, close actions
- **Advanced array methods**:
  - `map`, `filter`, `reduce`, `find`, `some`, `every`, `includes`, `sort`, `slice`, `splice`
  - Applied with real banking logic
- **Reusability**: clean and modular code with helper functions (`updateUI`, `calcDisplayBalance`, etc.)
- **Form validation** and basic input protection
- **Dynamic username generation** based on user’s full name
- **UI updates tied to user actions**

### 📊 Business logic implemented:

- Transfers only happen if:
  - Amount is positive
  - Sufficient balance is available
  - Receiver account exists and is not the sender
- Loans are approved only if:
  - At least one previous deposit is ≥ 10% of requested loan
- Account closure requires:
  - Matching username and PIN

## 📸 Screenshots

![screenshot of the project](/images/screenshot.png)

## 🧪 How to Test the App

1. **Clone or download** the project files to your computer.
2. Open the `index.html` file directly in your browser (no server needed).
3. Log in using one of the pre-registered demo accounts listed below.
4. Once logged in, you can:
   - View account balance and transaction history
   - Transfer money to another user
   - Request a loan (based on eligibility)
   - Close your account
   - Sort transactions
   - Log out (manual only — logout timer coming soon)

---

## 👤 Demo Accounts

| Owner                  | Username | PIN    |
| ---------------------- | -------- | ------ |
| Hugo Miranda           | **hm**   | `1111` |
| Jessica Davis          | **jd**   | `2222` |
| Steven Thomas Williams | **stw**  | `3333` |
| Sarah Smith            | **ss**   | `4444` |

> 💡 The username is automatically generated using the **initials of the full name**, all lowercase
