-- Employee table
CREATE TABLE Employees (
    EmployeeID INT PRIMARY KEY,
    Name VARCHAR(100),
    RoleID INT,
    LocationID INT,
    ExperienceYears DECIMAL(3,1),
    Compensation DECIMAL(10,2),
    Status VARCHAR(20) -- Active, Inactive, etc.
);

-- Roles table
CREATE TABLE Roles (
    RoleID INT PRIMARY KEY,
    RoleName VARCHAR(100)
);

-- Locations table
CREATE TABLE Locations (
    LocationID INT PRIMARY KEY,
    LocationName VARCHAR(100)
);
