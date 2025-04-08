# Excel Data Analysis Visual Blueprint, 4th Edition, © 2019

## Introducing Data Analysis

### Manipulate Raw Data

By definition, _raw data_ is a mere collection of facts that by themselves tell you little or nothing.

### Data

-   Data Entry
-   Imported Data
-   Table

    If you convert the range into a table, Excel treats the data as a simple flat file database and enables you to apply a number of database-specific analysis techniques to the table.

### Data Models

A _data model_ is a collection of cells designed as a worksheet version of some real-world concept or scenario.

#### Formulas

A _formula_ is a set of symbols and values that perform some kind of calculation and produce a result.

#### Functions

A _function_ is a predefined formula that is built in to Excel. Each function takes one or more inputs called _arguments_, such as numbers or cell references, and then returns a result.

### What-If Analysis

One of the most common data analysis techniques is _what-if analysis_, where you set up worksheet models to analyze hypothentical situations.

#### Data Tables

A _data table_ is a range of cells where one column consists of a series of values, called _input cells_. You can then apply each of the inputs to a single formula, and E xcel displays the results for each case.

#### Goal Seek

You use the Goal Seek tool in Excel when you want to manipulate one formula component, called the _changing cell_, in such a way that the formula produces a specific result. For example, in a _break even analysis_, you can use Goal Seek to determine the number of units of a product that you must sell for the profit to be 0.

#### Solver

You use the Solver tool in E xcel when you want to manipulate multiple formula components, called the _changing cells_, in such a way that the formula produces the optimal result.

#### Scenarios

A _scenario_ is a collection of input values that you plug into formulas within a model to produce a result. The idea is that you make up scenarios for various situations -- for example, best-case, worst-case, and so on -- and the Excel Scenario Manager saves each one. Later you can apply any of the saved scenarios, and E Xcel automatically applies all the input values to the model.

### Introducing Formulas

A _formula_ is a set of symbols and values that perform some kind of calculation and produces a result.

#### Operands

##### Cell and Range References

##### Range Names

_Range names_ are labels applied to a single cell or to a range of cells. You can use a defined name in place of a range.

##### Constants

A _constant_ is a fixed value that you insert into a formula and use as is.
Constants can be named.

##### Worksheet Functions

You can use any of the built-in worksheet functions in Excel as operands in a formula.

#### Operators

The _operators_ are symbols that the formula uses to perform the calculation.

#### Operator Precedence

### Understanding Formula Types

#### Arithmetic Formulas

-   \+ Addition
-   \- Subtraction
-   \- Negation
-   \* Multiplication
-   / Division
-   % Percentage
-   ^ Exponentiation

#### Comparison Formulas

-   = Equal To
-   \< Less than
-   \<= Less than or equal to
-   \> Greater than
-   \>= Greater than or equal to
-   \<\> Not equal to

If a comparison is true, then the formula returns the value 1.

If a comparison is false, then the formula returns the value 0.

#### Text Formulas

-   \& Concatenation operator

#### Reference Formulas

```
Operator    Name            Description
: (colon)   Range           Produces a ramge from two cell references (for example: A1:C5)
, (comma)   Union           Produces a range that is the union of two ranges (A1:C5,B2:E8)
(space)     Intersection    Produces a range that is the intersection of two ranges (A1:C5 B2:E8)
```

### Build a Formula

1.  Click in the cell in which you want to build a formula
2.  Type =

    Your typing also appears in the Formula bar.

3.  ...

#### Apply It

Use parentheses so you don't have problems with operator precedence.

### Add a Range Name to a Formula

You can make your formulas easier to build, more accurate, and easier to read by using range names as operands instead of cell and range addresses. For example, the formula `=SUM(B2:B10)` is difficult to decipher on its own, particularly if you cannot see the range B2:B10 to examine its values. However, if you use the formula `=SUM(Expenses)` instead, it becomes immediately obvious what the formula is meant to do.

The easiest way to define a range name is to select the range and then type the name in the Name box, which appears on the far left of the Excel Formula bar.

#### Add a Range Name to a Formula

1. Click in the cell in which you want to build a formula, type =, and then type any operands and operators you need before adding the range name.
2. Click the Formulas tab.
3. Click Use in Formula
