# MongoDB $inc Operator Error: Incorrect data type

This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries. The error arises from providing a string value to `$inc` instead of a number.

## Bug Description
The provided code attempts to increment the `counter` field in a document by 1. However, due to the use of a string value ('1') instead of a numeric value (1), the `$inc` operator fails to update the field correctly.

## Bug Solution
The solution involves correcting the update query to provide a numeric value to the `$inc` operator.