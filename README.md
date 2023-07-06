# Create-one-application-where-the-following-functionality-should-be-
Should be 1 SuperAdmin
Super Admin will create/Delete/update/Get  a Compony 
Please let me know if you have any confusion or concern about the requirment
 
 Functionality:
 
    User Roles:
        SuperAdmin: Only one SuperAdmin account can exist, responsible for managing the application.
        Admin: Can be created by the SuperAdmin to manage individual companies.
        Employee/User: Can be managed by Admins and assigned to specific companies.
 
    SuperAdmin:
        Login: SuperAdmin can log in using a unique username and password.
        Create Admin: SuperAdmin can create Admin accounts to manage companies.
        Delete Admin: SuperAdmin can delete an Admin account if necessary.
        Update Admin: SuperAdmin can modify Admin account details (e.g., name, email).
        Get Company: SuperAdmin can access the details of any company in the system.
 
    Admin:
        Login: Admins can log in using their unique credentials.
        Create Company: Admins can create a new company with its relevant details.
        Delete Company: Admins can delete an existing company if needed.
        Update Company: Admins can modify company information (e.g., name, address).
        Get Company: Admins can access the details of the companies they manage.
 
    Employee/User:
        Login: Employees/Users can log in using their unique credentials.
        Get Company: Employees/Users can access the details of the company they belong to.
 
Note: Proper validation, authentication, and authorization mechanisms should be implemented to ensure data security and restrict unauthorized access to sensitive operations
