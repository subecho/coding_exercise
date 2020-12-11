# Programming Exercise

## Objective
Using whatever appropriate means, create a Python file that will interact with a
theoretical REST API endpoint as defined below. You will need to do the following
tasks:

1. Create an employee.
2. Get information about all employees.
3. Get information about the employee from Step 1.
4. Change the name of the employee from Step 1.
5. Delete the employee from Step 1.

## Endpoint Details
Assume that the REST API endpoint is at https://example.com/api/v1/employee and that
employees have the following JSON structure:

```json
{
  name: <string>,
  id: <int>  # Starts at 0, assigned by server on creation.
}
```
