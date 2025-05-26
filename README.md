# FarmFusion360

## Smart Farm Management System

FarmFusion360 is an integrated, web-based farm management system designed to help farmers and farm managers streamline operations, track harvests, sales, expenses, debts, laborers, and generate comprehensive financial reports with multi-currency support.

---

## Features

- **Harvest Management:** Record and manage crop harvest data including quantities and units.
- **Sales Management:** Track product sales with detailed quantity, pricing, and totals.
- **Expense & Debt Tracking:** Manage all farm-related expenses, debts, and laborer salaries.
- **Laborer Management:** Maintain laborer records and salary payments.
- **Financial Reporting:** Generate reports filtered by date ranges, with currency conversion functionality using ExchangeRate-API.com.
- **User Authentication:** Secure login and registration with password hashing and session management.
- **Responsive UI:** Modern, clean interface with responsive design and easy navigation.

---

## Technology Stack

- **Backend:** PHP with PDO for secure database interactions.
- **Database:** MySQL for data storage.
- **Frontend:** HTML5, CSS3 (with CSS variables and Flexbox), JavaScript.
- **APIs:** ExchangeRate-API.com for real-time currency exchange rates.
- **Security:** Password hashing, session management, and input validation.

---

## Installation & Setup

1. Clone or download this repository to your local server environment (e.g., XAMPP, WAMP, MAMP).
2. Import the provided `database.sql` file into your MySQL database to create necessary tables.
3. Update the `db.php` configuration file with your database credentials.
4. Obtain an API key from [ExchangeRate-API.com](https://www.exchangerate-api.com/) and add it to the appropriate config or script file.
5. Run the system by navigating to `login.php` on your local server.
6. Register a new user or log in with existing credentials.

---

## Usage

- Log in to access the dashboard.
- Use sidebar navigation to manage harvests, sales, expenses, debts, and laborers.
- Access reports to filter financial data by date and currency.
- Use the "Show Password" checkbox for ease during login and registration.

---

## Currency Conversion

FarmFusion360 integrates the ExchangeRate-API.com to provide real-time currency conversion, allowing users to view financial data in different currencies. Exchange rates are cached for performance and updated hourly.

---

## Future Enhancements

- Mobile app support for on-field farm management.
- Inventory management for seeds, tools, and fertilizers.
- Automated alerts for due payments and low stock.
- Enhanced analytics with charts and graphs.
- Multi-user roles and permissions.

---

## Credits

Developed by [Sigmund James Mejarse].

Icons provided by [FontAwesome](https://fontawesome.com/).

Currency data provided by [ExchangeRate-API.com](https://www.exchangerate-api.com/).

---

## Contact

For questions or feedback, please contact [sigmundjamesm@gmail.com].

