# Projektstruktur

Hier ist die vollständige Ordner- und Dateistruktur des Projekts.

## mh-expenses-app-backend

```
mh-expenses-app-backend/
├── .env
├── .gitignore
├── count_budgets.js
├── package.json
├── README.md
├── test-gemini.js
├── docs/
│   ├── logging.md
│   ├── mainFeatures.md
│   ├── overview.md
│   ├── security.md
│   └── user-management.md
├── logs/
│   ├── .68407aa9f9258831f702db836443b9077eaeec6a-audit.json
│   ├── .95ab41a1aec5a022e1f5a280434ba61a9899dab0-audit.json
│   ├── .e5210eccd550f9edac74ec60024b73718af4e4e8-audit.json
│   ├── application-2025-08-07.log
│   ├── application-2025-08-13.log
│   ├── application-2025-08-28.log
│   ├── database-2025-08-07.log
│   ├── database-2025-08-13.log
│   ├── database-2025-08-28.log
│   ├── error-2025-08-07.log
│   ├── error-2025-08-13.log
│   ├── error-2025-08-28.log
│   └── exceptions.log
├── reports/
│   └── temp/
├── scripts/
│   └── logs.sh
├── src/
│   ├── server.js
│   ├── config/
│   │   ├── config.js
│   │   └── db.js
│   ├── controllers/
│   │   ├── advancedReporting.js
│   │   ├── analytics.js
│   │   ├── auth.js
│   │   ├── budgets.js
│   │   ├── categories.js
│   │   ├── expense.controller.js
│   │   ├── expenses.js
│   │   ├── maps.js
│   │   ├── reports.js
│   │   ├── settings.js
│   │   └── users.js
│   ├── middleware/
│   │   ├── auth.js
│   │   ├── error.js
│   │   └── validate.js
│   ├── models/
│   │   ├── Budget.js
│   │   ├── Category.js
│   │   ├── Expense.js
│   │   ├── QuarterlyReport.js
│   │   ├── Report.js
│   │   ├── Setting.js
│   │   └── User.js
│   ├── routes/
│   │   ├── advancedReporting.js
│   │   ├── analytics.js
│   │   ├── auth.js
│   │   ├── budgets.js
│   │   ├── categories.js
│   │   ├── expenses.js
│   │   ├── maps.js
│   │   ├── reports.js
│   │   ├── settings.js
│   │   └── users.js
│   ├── utils/
│   │   ├── emailService.js
│   │   ├── errorResponse.js
│   │   ├── formatters.js
│   │   ├── googleMaps.js
│   │   ├── logger.js
│   │   ├── morganLogger.js
│   │   ├── reportGenerator.js
│   │   └── seeder.js
│   └── validations/
│       ├── auth.js
│       ├── expense.js
│       └── report.js
```

## mh-expenses-app-frontend

```
mh-expenses-app-frontend/
├── eslint.config.js
├── index.html
├── package.json
├── README.md
├── tailwind.config.js
├── vite.config.js
├── docs/
│   └── docs.md
├── public/
│   ├── google-maps-test-direct.html
│   ├── google-maps-test.html
│   └── vite.svg
└── src/
    ├── App.jsx
    ├── index.css
    ├── main.jsx
    ├── api/
    │   ├── adminApi.js
    │   ├── analyticsApi.js
    │   ├── apiConfig.js
    │   ├── authApi.js
    │   ├── budgetApi.js
    │   ├── expenseApi.js
    │   ├── mockData.js
    │   ├── settingsApi.js
    │   └── userApi.js
    ├── assets/
    │   ├── react.svg
    │   └── styles/
    │       ├── global.css
    │       └── variables.css
    ├── components/
    │   ├── ExpenseFilters.jsx
    │   ├── ExpensesList.jsx
    │   ├── analytics/
    │   │   └── AnalyticsNav.jsx
    │   ├── cards/
    │   │   ├── ExpenseCard.jsx
    │   │   └── StatCard.jsx
    │   ├── charts/
    │   │   └── ExpenseChart.jsx
    │   ├── expenses/
    │   │   ├── ExpenseCalculator.jsx
    │   │   ├── ExpenseFilters.jsx
    │   │   └── ExpenseRateDisplay.jsx
    │   ├── forms/
    │   │   ├── AddressInput.jsx
    │   │   ├── ExpenseForm.jsx
    │   │   └── PlaceAutocomplete.jsx
    │   ├── layout/
    │   │   ├── AdminLayout.jsx
    │   │   ├── Footer.jsx
    │   │   ├── Layout.jsx
    │   │   ├── ReportsLayout.jsx
    │   │   └── SalesRepLayout.jsx
    │   ├── reports/
    │   │   └── ReportsNav.jsx
    │   └── ui/
    │       ├── Alert.jsx
    │       ├── Button.jsx
    │       ├── Card.jsx
    │       ├── GoogleMapComponent.jsx
    │       ├── MapView.jsx
    │       ├── Modal.jsx
    │       ├── Pagination.jsx
    │       └── Stepper.jsx
    ├── config/
    │   └── config.js
    ├── context/
    │   ├── AuthContext.jsx
    │   └── SettingsContext.jsx
    ├── hooks/
    │   └── useSettingsValue.js
    ├── pages/
    │   ├── admin/
    │   │   ├── Analytics.jsx
    │   │   ├── ExpenseManagement.jsx
    │   │   ├── PeriodDetail.jsx
    │   │   ├── Reports.jsx
    │   │   ├── SystemSettings.jsx
    │   │   ├── UserManagement.jsx
    │   │   └── analytics/
    │   │       ├── CategoryBreakdown.jsx
    │   │       ├── ExpenseTrends.jsx
    │   │       ├── PeriodDetail.jsx
    │   │       ├── TimeSummary.jsx
    │   │       └── YearlyComparison.jsx
    │   ├── auth/
    │   │   ├── ForgotPassword.jsx
    │   │   ├── Home.jsx
    │   │   ├── Login.jsx
    │   │   ├── Register.jsx
    │   │   └── ResetPassword.jsx
    │   ├── budgets/
    │   │   ├── BudgetDashboard.jsx
    │   │   ├── BudgetDetails.jsx
    │   │   ├── BudgetList.jsx
    │   │   ├── BudgetsList.jsx
    │   │   ├── CreateBudget.jsx
    │   │   └── EditBudget.jsx
    │   ├── categories/
    │   │   ├── CategoryDetail.jsx
    │   │   ├── CategoryList.jsx
    │   │   ├── CategorySummary.jsx
    │   │   └── CreateCategory.jsx
    │   ├── dashboard/
    │   │   ├── Dashboard.jsx
    │   │   ├── admin/
    │   │   │   └── AdminDashboard.jsx
    │   │   └── salesRep/
    │   │       ├── Dashboard.jsx
    │   │       └── SalesRepDashboard.jsx
    │   ├── documentation/
    │   │   └── Documentation.jsx
    │   ├── error/
    │   │   └── NotFound.jsx
    │   ├── expenses/
    │   │   ├── CreateExpense.jsx
    │   │   ├── EditExpense.jsx
    │   │   ├── ExpenseDetail.jsx
    │   │   ├── ExpenseDetails.jsx
    │   │   ├── ExpenseList.jsx
    │   │   └── ExpensesList.jsx
    │   ├── profile/
    │   │   ├── ChangePassword.jsx
    │   │   ├── Profile.jsx
    │   │   └── UpdateProfile.jsx
    │   ├── public/
    │   │   └── Features.jsx
    │   ├── reports/
    │   │   ├── AdvancedFilteredExpenses.jsx
    │   │   ├── AllBudgetsReport.jsx
    │   │   ├── BudgetComparison.jsx
    │   │   ├── BudgetSummaryReport.jsx
    │   │   ├── ChartData.jsx
    │   │   ├── ExpenseForecasting.jsx
    │   │   ├── Forecast.jsx
    │   │   ├── Reports.jsx
    │   │   └── YTDReports.jsx
    │   └── settings/
    │       └── Settings.jsx
    ├── routes/
    │   ├── AdminRoutes.jsx
    │   ├── PublicRoutes.jsx
    │   └── SalesRepRoutes.jsx
    └── utils/
        ├── export.js
        ├── formatters.js
        ├── googleMaps.js
        ├── roleGuard.jsx
        ├── routeHelpers.js
        └── validators.js
```
