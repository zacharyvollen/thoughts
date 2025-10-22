# Configuration

Allowing configuration for each system rule should be carefully considered. The more variable a configuration can be expressed the more likely developments will design configurations that are undesirable in someway.

Default values for configuration should be considered when the complexity of configuration increases and a default value wouldn't be sufficient in all use cases. By introducing defaults you may be intentenionally obfuscating a user's understanding of the system and have their expectations mismatch reality.

Configuration values that are dependent on one another are best expressed in a structural grouping, a prefix indicating their association, or be embedded into the same value with a specified format.

Complete configuration examples for all file formats with documentation of each variable should be provided and kept up to date. Without comprehensive examples your users are left guessing on what's expected of them.