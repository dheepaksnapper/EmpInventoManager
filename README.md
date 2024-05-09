# EmpInventoManager

EmpInventoManager is a web-based inventory management system built using ASP .NET Core MVC for the backend and Angular for the frontend. It allows the management of both employees and inventory within a company.

## Features

### User Roles

1. **Admin:**
   - Can manage products (add, edit, delete).
   - Can manage inventory (view stock, add stock, remove stock).
   - Can view transaction history.
   - Can manage users (add, edit, delete).
   - Can assign and deassign inventory items to employees.
   - Can manage employee details.

2. **Branch Manager:**
   - Can view products and inventory.
   - Can make entries for products coming in from another branch office.
   - Can mark products as exit when they go out.
   - Can assign and deassign inventory items to employees for their branch.
   - Can view and manage employee details for their branch.

### Product Management

1. **Add Product:**
   - Fields: Product Name, Description, Category, Unit Price, Quantity.
   - Option to upload product image.

2. **Edit Product:**
   - Allow editing all product details.

3. **Delete Product:**
   - Soft delete (mark as inactive) to preserve transaction history.

### Inventory Management

1. **View Inventory:**
   - List of all products with current stock quantity.
   - Option to search, filter, and sort products.

2. **Add Stock:**
   - Increase stock quantity for a product.
   - Provide quantity and additional details (e.g., source branch office, date).

3. **Remove Stock:**
   - Decrease stock quantity for a product.
   - Provide quantity and additional details (e.g., destination branch office, date).

### Transaction History

1. **View Transactions:**
   - List of all transactions (inward and outward) with details.
   - Option to search, filter, and sort transactions.

### Employee Management

1. **View Employees:**
   - List of all employees with their basic information (e.g., name, email).
   - Show the inventory items currently assigned to each employee.
   - Option to filter employees by branch office, department, or other relevant criteria.
   - Search functionality to find specific employees quickly.
   - Admin can manage employee details, including assigning and deassigning inventory items to employees.

## Technologies Used

### Backend
- ASP .NET Core MVC
- Entity Framework Core (for database operations)
- SQL Server (for data storage)

### Frontend
- Angular
- TypeScript
- HTML/CSS

