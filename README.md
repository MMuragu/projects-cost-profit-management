<img width="478" height="451" alt="image" src="https://github.com/user-attachments/assets/244d1a47-ad17-4209-a5d6-ffdb18c44b53" />
<img width="1919" height="894" alt="image" src="https://github.com/user-attachments/assets/9f4e201f-8473-4897-adf6-c90380c3cdc4" />
<img width="1919" height="894" alt="image" src="https://github.com/user-attachments/assets/dcbb5269-cd6a-4bf5-94ae-8d9ef25aa416" />
<img width="1919" height="894" alt="image" src="https://github.com/user-attachments/assets/11338e94-6bf3-469c-9ab5-f54ba43f83a5" />

### Project Management

Job Costing and Pofitability Tracking

An ERPNext-based Project Management and Job Costing System designed to streamline project operations, manage resources, and monitor financial performance from project initiation to completion.

The system provides a centralized platform for managing projects, clients, employees, tasks, task activities, timesheets, materials, quotations, sales orders, client invoices, payments, and supplier procurement.

### Key Features
- **Project Management:** Create and manage projects, project templates, tasks, and task activities.
- **Team Management:** Manage employees, assign responsibilities, and track project activities.
- **Time Tracking:** Record timesheets to monitor time spent on projects.
- **Materials Management:** Manage project materials, material requests, and supplier quotations.
- **Sales & Billing:** Handle client quotations, sales orders, invoices, and payments.
- **Financial Tracking:** Track project expenses and costs against revenue to understand project profitability.
- **Project Monitoring:** Use dashboards and reports to monitor project progress, financial performance, and identify projects at risk of exceeding their budgets.

The goal is to provide businesses with better visibility and control over their projects, resources, costs, and profitability through one integrated system.

### Installation

You can install this app using the [bench](https://github.com/frappe/bench) CLI:

```bash
cd $PATH_TO_YOUR_BENCH
bench get-app $URL_OF_THIS_REPO --branch version-16
bench install-app project_management
```

### Contributing

This app uses `pre-commit` for code formatting and linting. Please [install pre-commit](https://pre-commit.com/#installation) and enable it for this repository:

```bash
cd apps/project_management
pre-commit install
```

Pre-commit is configured to use the following tools for checking and formatting your code:

- ruff
- eslint
- prettier
- pyupgrade

### License

mit
# projects-cost-profit-management
