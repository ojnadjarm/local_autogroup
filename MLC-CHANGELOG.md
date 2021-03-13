# Changelog
All notable changes to this project by My Learning Consultants will be documented in this file. Commit hash is the original local_autogroup commit this code is based on.

## Commit hash
6b2a10cc130dcd77a96714e5e4b8620f12e610da

## [CRU-119 - 2021-03-12]
### Changed
- Added option for profile field to contain multiple groups
### Unit test
- The multiple_profile_values_test in local_autogroup_lib_testcase in local/autogroup/tests/lib_test.php
### Manual test instructions
- Create a profile text field
- On Site Admin -> Plugins -> Local Plugins
1. Check Enabled
2. Set Group by to be the new profile field
3. Under Event Triggers, enable user profiles
- Create a user
- Create a course
- Enroll the user in the course
- Add a value to the user's profile field that contains comma separated values (eg Test 1, Test 2, Test 3)
- Confirm the user is added to multiple groups based on the values in the field
