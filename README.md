![](https://lh3.googleusercontent.com/-SjJCP2AntwI/XoYRxI-hBjI/AAAAAAAABA4/bFi0th7AKGgQFVIOB8L-GiWSZriYhI6MgCK8BGAsYHg/s0/2020-04-02.png)
# Instituto Atlântico QA Challenge
Hi! This is a simple challenge to test your knowledge in skills for the QA Analyst job position here at Atlântico. 

## API service testing

**Context**

This challenge is based on the "Demo Simples de Agenda" Application. To start the application, simply run the command `java -jar agenda.jar` and go to `http://localhost:8080/`.

**Business Rules**
* The user can Add, Remove and List contacts
* A contact is composed of Name and Phone Number
* Name is required, and must be unique and alpha-numeric
* The Phone Number is also alpha-numeric and may have 12 characters max.

**API Definition**
| EndPoint                     |   Functionality         |
| ---------------------------- | -----------------------:|
| GET /agenda                  | List Contacts           |
| POST /agenda                 | Add Contact             |
| POST /apagar_agenda          | Delete Contact          |

**Payload**

```json
{
    "nome":"contato1",
    "telefone":"123456789"
}
```

## Test Scenario
Indentify and create test scenarios based on the business rules of the application (FUncional and non funciontal test scenarios)
At least 5 test scenarios
*(You can use the tool you want to document the test scenarios)

**Create the tests for the application, paying attention to these rules:** 
* Implement tests for at least 3 scenarios
* You can use any tool you want to implement the test scenarios
* Document the proccess to run and execute the tests


## Git

Provide commentary about each of these Git commands and what are they used for:
```
git fetch -p origin

git fetch origin

git remote add origin git@github.com:testia.git | out-null

git remote add upstream origin git@github.com:testia.git | out-null

git checkout master

git pull origin master

git rev-parse --short HEAD
```

## Bonus
* Create the tests with python using pytest
* Configure a pipeline to automatically run the tests
* Run the tests with Docker


## End

If you have any questions, feel free to contact us, and **GOOD LUCK!**
