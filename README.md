1-get all employees
link:- "http://localhost:10000/api/v1/employee",
method:"GET"
----------------------------------------------------------------------------------------------
2-delete one employee
link:- "http://localhost:10000/api/v1/employee/delete/${employee_id}",
method: "DELETE"
----------------------------------------------------------------------------------------------
3-add new employee
link:- "http://localhost:10000/api/v1/employee/",
method:"POST",
headers: {
            'Content-Type': 'application/json',
        },
        body: JSON.stringify({
            name: "",
            email: "",
            country: "",
            phone: "",
        })
---------------------------------------------------------------------------------------------
4-update employee
link:- "http://localhost:10000/api/v1/employee/update/:${employee_id}",
method:"PUT",
headers: {
            'Content-Type': 'application/json',
        },
        body: JSON.stringify({
            name: "",
            email: "",
            country: "",
            phone: "",
        })
-------------------------------------------------------------------------------------------
5-delete all
link:- "http://localhost:10000/api/v1/employee/",
method:"DELETE"
