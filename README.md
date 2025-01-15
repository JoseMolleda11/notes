# SQL
## Elements of language T-SQL
| Elementos             | Predicates and operators |
|------------------------|-------------------------|
| Predicates            | IN, BETWEEN, LIKE      |
| Comparison Operators  | =, >, <, >=, <=, <>, !=, !>, !< |
| Logical Operators     | AND, OR, NOT           |
| Arithmetic Operators  | +, -, *, /, %          |
| Concatenation         | +                      |

| Evaluation order| Operators                                      |
|----------------------|------------------------------------------------|
| 1                    | () Parentheses                                |
| 2                    | *, /, % (Multiply, divide, module)        |
| 3                    | +, - (Add / Positive / Concatenate, Subtract / Negative) |
| 4                    | =, <, >, >=, <=, !=, !>, !< (Comparison) NO  |
| 5                    | Y                                             |
| 6                    | BETWEEN, IN, LIKE, OR                         |
| 7                    | = (Assignment)                                |
