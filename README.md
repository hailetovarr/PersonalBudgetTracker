# Personal Budget Tracker

A modern, user-friendly web application built with Angular that helps users track their income and expenses to better manage their finances.

## Features

- **Income Management**: Add and track multiple income sources
- **Expense Tracking**: Categorize and monitor expenses across different categories
- **Budget Summary**: Real-time overview of financial status
- **Category Management**: Pre-defined expense categories (Food & Dining, Transportation, Entertainment, etc.)
- **Data Persistence**: Local storage to save your financial data
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Form Validation**: Comprehensive input validation and error handling

## Technology Stack

- **Frontend Framework**: Angular 17
- **Language**: TypeScript
- **Styling**: CSS3 with modern design patterns
- **Icons**: Font Awesome
- **Fonts**: Inter (Google Fonts)
- **Data Storage**: Browser Local Storage

## Project Structure

```
Final Project/
├── src/
│   ├── app/
│   │   ├── components/
│   │   │   ├── summary/           # Budget overview component
│   │   │   ├── income/            # Income management component
│   │   │   └── expenses/          # Expense management component
│   │   ├── services/
│   │   │   └── budget.service.ts  # Core business logic and data management
│   │   ├── app.component.ts       # Main app component with navigation
│   │   └── app.routes.ts          # Application routing configuration
│   ├── styles.css                 # Global styles and design system
│   ├── index.html                 # Main HTML template
│   └── main.ts                    # Application bootstrap
├── angular.json                   # Angular CLI configuration
├── package.json                   # Dependencies and scripts
└── tsconfig.json                  # TypeScript configuration
```

## Getting Started

### Prerequisites

- Node.js (version 18 or higher)
- npm (comes with Node.js)
- Angular CLI (optional, for development)

### Installation

1. **Clone or download the project**
   ```bash
   cd "Final Project"
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Install Angular CLI globally (if not already installed)**
   ```bash
   npm install -g @angular/cli
   ```

### Running the Application

1. **Development server**
   ```bash
   npm start
   # or
   ng serve
   ```

2. **Open your browser and navigate to**
   ```
   http://localhost:4200
   ```

The application will automatically reload when you make changes to the source files.

### Building for Production

```bash
npm run build
# or
ng build
```

The build artifacts will be stored in the `dist/` directory.

## Usage Guide

### 1. Summary Dashboard
- View your total income, expenses, and remaining budget
- See expenses broken down by category
- Monitor recent transactions
- Get budget alerts when overspending

### 2. Income Management
- Add income from various sources (salary, freelance, investments, etc.)
- View income history with dates
- Delete income entries
- See total income calculation

### 3. Expense Tracking
- Add expenses with descriptions and amounts
- Categorize expenses for better organization
- Filter expenses by category
- View expense history and totals
- Delete unwanted expense entries

### 4. Categories
The application includes the following expense categories:
- Food & Dining
- Transportation
- Entertainment
- Utilities
- Healthcare
- Shopping
- Education
- Other

## Features in Detail

### Data Persistence
- All data is stored locally in your browser
- Data persists between sessions
- No external database required
- Privacy-focused approach

### Form Validation
- Required field validation
- Minimum value validation for amounts
- Date validation
- Real-time error feedback
- User-friendly error messages

### Responsive Design
- Mobile-first approach
- Adapts to different screen sizes
- Touch-friendly interface
- Modern, clean design

### Budget Alerts
- Automatic detection of overspending
- Visual warnings when budget is exceeded
- Clear indication of budget status

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Contributing

This is a student project for educational purposes. If you'd like to enhance the application:

1. Fork the project
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## Future Enhancements

Potential features for future versions:
- Data export/import functionality
- Budget goals and targets
- Expense trends and analytics
- Multiple currency support
- Cloud synchronization
- Receipt photo uploads
- Recurring income/expense tracking

## License

This project is created for educational purposes as part of a computer science course.

## Support

For questions or issues related to this project, please refer to the course materials or contact the instructor.

---

**Note**: This application stores data locally in your browser. Clearing browser data will remove all financial records. Consider exporting important data before clearing browser storage.