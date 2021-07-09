# STUDENT-MARKSHEETEXCEL


// Java Program in which a Class is declared and
// its methods are defined

// Class
class Employee {

	// Member variable of Employee Class
	// Name, Designation and Salary
	private String employeeName;
	private String employeeDesignation;
	private double salary;

	// Constructor of Employee class
	public Employee() {}

	// Method 1
	public String toString()
	{
		return String.format("%s - %s - %f", employeeName,
							employeeDesignation, salary);
	}

	// method 2
	// To get name of an employee
	public String getEmployeeName()
	{

		// Return the name of the employee
		return employeeName;
	}

	// Method - 3
	// To set employee name
	public void setEmployeeName(String employeeName)
	{

		// This keyword refer to the current
		// method or constructor itself
		// Hence, same employee name can be set
		// through this method
		this.employeeName = employeeName;
	}

	// Method - 4
	// To get already assigned designation of
	// the employee over which method is invoked
	public String getEmployeeDesignation()
	{

		// Return the designation of the employee
		// over which the function is called
		return employeeDesignation;
	}

	// Method - 5
	// To assign a designation to an employee
	public void
	setEmployeeDesignation(String employeeDesignation)
	{

		// This keyword refer to the current
		// method or constructor itself
		this.employeeDesignation = employeeDesignation;
	}

	// Method - 6
	// To get salary of an employee
	public double getSalary()
	{

		// Return the salry of the employee for which
		// the function is invoked
		return salary;
	}

	// Method - 7
	// To set salary of the existing employee with
	// assigned name and designation
	public void setSalary(double salary)
	{
		this.salary = salary;
	}
}

