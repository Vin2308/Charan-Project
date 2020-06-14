# Charan-Project
# Employee Leave Management System 
Users
1. Admin
2. Manager
3. Employee
4. HR

Use cases
  1. Admin should be able to login and add Employees
  2. Manager should be able to login and view employees under him and approve/reject leaves
  3. Employee can login and View available leaves and can apply for leave with a comment so that his manager gets when he logs in
  4. Admin should be able to generate report of all leave data of all employess and also report specific to a manager based on the period he specifies.
  
  Leaves per year (JAN - DEC)
  CASUAL LEAVES -6
  SICK LEAVE - 6
  PRIVILEGED - 12
  
  # Employee Table
  EMP_ID
  PASSWORD
  FIRSTNAME
  LASTNAME
  EMAIL
  PHONE
  DOB
  GENDER
  MANAGER_ID
  
  # LeaveBalanceTable
  EMP_ID
  YEAR
  CLBALANCE
  SLBLANACE
  PLBALANCE
  
  
  # LeaveApplied Table
  LEAVE_ID
  EMP_ID
  TYPEOFLEAVE
  NOOFDAYS
  COMMENTS
  STATUS
  
  
  
  
  
  
  
  
