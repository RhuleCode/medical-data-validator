# medical-data-validator
Overview
This Python-based utility validates complex medical record structures using Regular Expressions (RegEx) and functional programming techniques. It ensures that patient data follows strict formatting rules before being processed by a database.

Features
Schema Verification: Checks for missing or extra keys in record dictionaries.

RegEx Validation: Ensures patient_id starts with 'P' and last_visit_id starts with 'V'.

Type Checking: Validates that ages are integers and medications are stored in lists.

Error Reporting: Provides detailed console feedback identifying the exact position of invalid records.


