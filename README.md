# SQLCheatSheet
## SELECT Clause 
### —- Using expressions
`SELECT (points * 10 + 20) AS discount_factor`
`FROM customers`

Order of operations: 
- Parenthesis
- Multiplication / division
- Addition / subtraction 
### —- Removing duplicates
`SELECT DISTINCT state`
`FROM customers`

## WHERE Clause 
### We use the WHERE clause to filter data.
#### Comparison operators:
• Greaterthan:>
• Greaterthanorequalto:>= • Lessthan:<
• Lessthanorequalto:<=
• Equal:=
• Notequal:<>
• Notequal:!=
