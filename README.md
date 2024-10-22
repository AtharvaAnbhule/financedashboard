

# Finance Dashboard

A comprehensive finance dashboard that allows users to manage transactions, accounts, and track expenditures with visual charts. The dashboard provides a clean and efficient way to monitor your financial activities. The project is built with modern web technologies including **TypeScript**, **Clerk** for authentication, **NeonDB**, **Drizzle ORM**, and styled using **Tailwind CSS**.

## Features

- **Transaction Management**: Add, edit, and delete financial transactions.
- **Account Management**: Keep track of multiple accounts and their balances.
- **Balance Display**: View your current balances across accounts.
- **Expenditure Charts**: Visual representation of your spending using charts.
- **Authentication**: User authentication handled by **Clerk**.
- **Responsive Design**: Fully responsive UI powered by **Tailwind CSS** for a smooth experience on all devices.

## Tech Stack

- **TypeScript**: For static typing and enhancing development experience.
- **Clerk**: For secure and robust authentication.
- **NeonDB**: For the database, providing scalable and efficient storage.
- **Drizzle ORM**: Type-safe ORM for database operations.
- **Tailwind CSS**: For rapid and modern UI development.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AtharvaAnbhule/financedashboard.git
   cd finance-dashboard
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure environment variables:

   Create a `.env` file in the root directory and add the following:

   ```bash
   CLERK_FRONTEND_API=<your_clerk_frontend_api>
   CLERK_API_KEY=<your_clerk_api_key>
   NEON_DB_URL=<your_neon_db_url>
   ```

4. Run the development server:
   ```bash
   npm run dev
   ```

5. Visit the app in your browser:
   ```
   http://localhost:3000
   ```

## Usage

- **Add Transaction**: Go to the transactions section and fill out the form to add a new transaction.
- **Manage Accounts**: View, add, or delete accounts and track the balance of each account.
- **View Charts**: Get an overview of your expenditure using dynamic charts.


## Future Enhancements

- Budgeting tools to help users set and track financial goals.
- Additional chart types for deeper financial insights.
- Integration with external APIs for real-time data syncing.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an issue.


## Acknowledgments

- [Clerk](https://clerk.dev/) for authentication.
- [NeonDB](https://neon.tech/) for database support.
- [Drizzle ORM](https://github.com/drizzle-team/drizzle-orm) for making database interactions easier.
- [Tailwind CSS](https://tailwindcss.com/) for the beautiful and responsive design.

