📌 LINQ Scenarios – C# Practice Project

This project contains a set of real-time LINQ query scenarios implemented using C# Console Application in .NET.
It demonstrates how to apply LINQ for Join, GroupBy, Filtering, Aggregation, and Date Range operations using in-memory collections.

🧱 Data Models Used
Class	Properties	Description
Employee	Id, Name, DeptId, Salary	Employee records
Department	DeptId, DeptName	Department details
LeaveRequest	EmpId, StartDate, EndDate, Status	Employee leave data

🔍 LINQ Queries Implemented (8 Scenarios)
#	Query Description	Concepts Used
1️⃣	Employee + Department Join (Print DeptName)	Inner Join
2️⃣	Employees with no leaves	Left Join + Null filter
3️⃣	Department-wise employee count	Group Join + Count
4️⃣	Pending leave count by department	Multi-Join + GroupBy
5️⃣	Employees with salary > team avg	Nested LINQ + Let Keyword
6️⃣	Highest salary per department	GroupBy + Max
7️⃣	Employee Name + Leave request count	Group Join + Aggregation
8️⃣	Leaves overlapping a date range	Date filter + Join

🧠 Key LINQ Concepts Covered

from ... where ... select
join, group join
DefaultIfEmpty() for Left Join
group ... by
Average(), Count(), Max()
Anonymous type creation
Conditional filtering using dates

▶ How to Run

Open the solution in Visual Studio
Build the project:
Build → Build Solution
Run:
Ctrl + F5

Console output displays results for all 8 queries

🎯 Purpose of the Project

✔ Practice LINQ for interview preparation
✔ Understand relationships like Employees ↔ Departments ↔ Leaves
✔ Learn both Joins and Aggregations in C#
✔ Helps in real-world HR / Employee Management systems

🧑‍💻 Author

P. Akash Dhapte
.NET Developer
