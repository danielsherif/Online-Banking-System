# Online Banking System - Technical Overview

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Storage**: Browser LocalStorage/SessionStorage
- **No Backend**: Static website with client-side functionality
- **No Database**: Data managed through browser storage

## Project Structure

```
├── unified-banking-app/          # Main entry point
│   ├── index.html               # Landing page
│   ├── css/                     # Shared styles
│   └── js/                      # Shared utilities
├── login_loan-Daniel/           # Authentication & Loans
├── accounts-Rahma/              # Account Management
├── CC-Karim/                    # Credit Cards
├── notis-Dina/                  # Notifications
├── report_pay-Youssef/          # Reports & Payments
└── assets/                      # Shared resources
    ├── images/
    └── icons/
```

## Module Overview

- **Authentication**: Login, signup, and session management
- **Accounts**: Account creation, management, and transactions
- **Loans**: Loan applications, calculator, and status tracking
- **Credit Cards**: Card management, points, and payments
- **Notifications**: System alerts and user notifications
- **Reports & Payments**: Bill payments and transaction reports
