# Change Log
All notable changes to this project will be documented in this file.

## [2.4.0.7] - 2015-02-21
### Fixed
- Abstract and Varies segments were not having their Description field values populated. (Reported bv TheStephenStanton)

## [2.4.0.6] - 2015-02-21
### Fixed
- ORU_R01 messages for v2.5.1 incorrectly did not support the repeating, optional segments OBX, Timing QTY and Specimen.
- Moved regular expression field validation into it's own StrictValidation opt in validation context.
- Correctly escape \X0A\ as \n (thanks to riaz.ahmad)
- Each field / token was being extracted twice (Reported by AFAde)

## [2.4.0.5] - 2015-02-19
### Fixed
- Nuget Package wasn't deploying the 2.51 dll due to new nuget command line packaging and deployment.
