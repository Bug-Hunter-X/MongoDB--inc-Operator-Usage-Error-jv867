# MongoDB $inc Operator Usage Error
This repository demonstrates a common error when using the MongoDB $inc operator in update operations. The error arises from using an incorrect data type as the increment value, which can lead to unexpected behavior or errors.

## Bug Description
The bug involves using a string value ('1') instead of a numeric value (1) with the $inc operator. This results in the update operation either failing or producing an unexpected result. The correct approach is to provide a numerical value for the increment to ensure proper functionality.

## Solution
The solution demonstrates the correct usage of the $inc operator with a numeric value to avoid errors and ensure accurate results. It involves modifying the update operation to use the numerical increment value instead of the string value.
