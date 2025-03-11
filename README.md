# Ramp Transaction Approval Dashboard

A React application that allows financial managers to review and approve employee transactions with intuitive filtering and pagination.

![Project Preview](https://via.placeholder.com/800x400?text=Transaction+Dashboard+Preview)

## Project Overview

This project simulates a financial transaction approval system where managers can:
- View all employee transactions
- Filter transactions by employee
- Approve or decline transactions with a simple checkbox interface
- Load more transactions with pagination

The application demonstrates my ability to identify and fix complex UI/UX bugs in a production-quality React codebase, improving user experience while maintaining the existing architecture.

## Technical Details

The application is built with:
- React 18
- TypeScript
- Custom hooks for data fetching and state management
- CSS modules for styling
- Simulated API endpoints for demonstrating functionality without a backend

## Key Features I Implemented

1. **Fixed dropdown positioning**: Ensured the employee filter dropdown scrolls correctly with the page
2. **Improved form functionality**: Fixed checkbox interactions for approving transactions
3. **Robust state management**: Prevented crashes when switching between filtered views
4. **Enhanced pagination**: Implemented proper data appending for "View More" functionality
5. **Optimized loading states**: Separated loading indicators for different data sources
6. **Responsive UI elements**: Ensured UI elements appear only when appropriate actions are available
7. **Persistent data handling**: Made transaction approval states persist across filter changes

## Getting Started

### Prerequisites
- Node.js (v14 or later)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/your-username/ramp-transaction-dashboard.git
cd ramp-transaction-dashboard
```

2. Install dependencies
```bash
npm install
# or
yarn install
```

3. Start the development server
```bash
npm start
# or
yarn start
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

### Demo on CodeSandbox

You can also view a live demo of this project on [CodeSandbox](https://codesandbox.io/p/sandbox/ramp-fe-challenge-l7t9cs)

## Project Structure

```
src/
├── components/         # UI components
│   ├── InputCheckbox/  # Checkbox component for approvals
│   ├── InputSelect/    # Dropdown component for filtering
│   └── Transactions/   # Transaction listing components
├── hooks/              # Custom React hooks
├── utils/              # Utility functions and types
├── App.tsx             # Main application component
└── index.tsx           # Application entry point
```

## Lessons Learned

Working on this project helped me develop a deeper understanding of:
- React's rendering lifecycle and how to debug it
- Managing complex state interactions in user interfaces
- Implementing proper caching strategies for API data
- Writing maintainable code in a TypeScript environment
- Fixing UI bugs while maintaining existing architecture

## License

[MIT](LICENSE)

## Acknowledgments

This project was part of a coding challenge originally provided by Ramp.
