* Read documentation/MODBUS_C6.md for more information on the register layout of the Komfovent C6/C6M devices.
* Read documentation/MODBUS_C8.md for key differences in the C8 controller.
* Keep documentation and code in sync - when updating one, check and update the other
* Use proper typing and constants instead of magic values
* Create reusable utility functions to avoid code duplication
* Use enums instead of dictionaries for fixed value sets
* Name entities based on their actual function, not generic numbering
* Only create entities when the corresponding hardware/feature exists
* Keep entity initialization consistent across different types
* Do not attempt to subclass EntityDescription
* Remove outdated comments and TODOs once addressed
* Use consistent unique IDs across the codebase
* Base unit handling on device classes where possible
* Organize code into logical blocks by functionality
* Include type annotations in comments for future code generation
* Write proper error handling for external communications
* Follow the platform's integration patterns and conventions
* Write tests to verify functionality
* Create utilities to help with testing (dumps, mocks, etc)
* Keep code clean and maintainable through regular refactoring
* Review changes for consistency across the entire codebase
