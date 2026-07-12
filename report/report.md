# Delta Lake MERGE Implementation

## Objective
Perform incremental data processing using Delta Lake.

## Steps Performed
1. Loaded customer master dataset.
2. Filled null values.
3. Removed duplicate records.
4. Converted data into Delta Table.
5. Loaded incremental dataset.
6. Performed MERGE operation.
7. Updated existing records.
8. Inserted new records.
9. Validated final output.

## Result
The Delta Lake MERGE operation was successfully implemented. Existing customer records were updated while new customer records were inserted into the Delta table.
