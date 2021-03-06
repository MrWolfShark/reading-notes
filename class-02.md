# Evaluations: A Quick guide

**Evaluation**
: Analyzes values against match criteria and returns value of True or False

## **Comparison Operators**
- Compare two oprands and return single value (True or False)
  - `>` Greater Than
  - `<` Less Than
  - `==` Equal To
  - `!=` Not Equal To
  - `>=` Greater Than or Equal To
  - `<=` Less Than or Equal To
    
### **Example:**

 ```javascript 
let eval = (true) != (false)
```

In the above example, two seperate values are being evaluated to see if they are not equal to each other (!=).
Since `true` is not equal to `false`, the variable eval with now return as `true`. This can be useful when evaluating 
values to guide the flow of a script using conditions.

## Logical Operators
- Compare the values of two or more comparison operators
  - `&&` AND
  - `||` OR
  - `!`  AND NOT

### **Example:**

```javascript
let eval = (true == true) && (false != true)
```

In the above example, two comparison operators are evaluated. The first evaluates if `true` is equal to `true` (which is `true`)
and is `false` does not equal `true` (which is also `true`). The AND operator compares the two results of the conditional 
operators to see if they match. Since `true` is the same value as `true`, the result of this evaluation would be `true`.

#### [Back to Home Page](/README.md)
