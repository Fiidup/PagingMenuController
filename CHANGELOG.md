# 0.4.0 Release notes (2015-07-04)

### Enhancements

- Change PagingMenuOptions structure from class to struct
- Support delegate methods to handle menu transition state

### Breaking changes

- Merge validator into PagingMenuController class

# 0.3.4 Release notes (2015-06-05)

### Enhancements

- Displaying only two menu items is now supported thanks to jeksys
- Small improvements

### Bugfixes

- Changed framework's deployment target to 8.0 for Carthage users thanks to alexcurylo
- Fixed AutoLayout constraints bug for rotating with SegmentedControl

# 0.3.3 Release notes (2015-05-29)

### Enhancements

- Separate RoundRect scale into horizontal and vertical one
- Add Validator class to validate options value

# 0.3.2 Release notes (2015-05-29)

### Enhancements

- Added new item mode, RoundRect
- Revert animation duration default value to 0.3
- Added CHANGELOG.md

# 0.3.1 Release notes (2015-05-17)

### Enhancements

- Created `PagingMenuOptions.swift` to separate class declaration from `PagingMenuController.swift`
- Added validator for `default page` option

### Bugfixes

- Fixed unexpected behavior of `default page` option

# 0.3.0 Release notes (2015-05-16)

### Enhancements

- Added `MenuItemMode` to change menu item design (`RoundRect` mode is not supported yet at this time)

# 0.2.3 Release notes (2015-05-15)

### Bugfixes

- Fixed `self` in closure to resolve strong reference cycle

# 0.2.2 Release notes (2015-05-11)

### Bugfixes

- Fixed incorrect accessors for some methods

# 0.2.1 Release notes (2015-05-11)

### Bugfixes

- Added some files for Carthage

# 0.2.0 Release notes (2015-05-11)

### Enhancements

- Support Carthage

# 0.1.0 Release notes (2015-05-10)

### Enhancements

- Support CocoaPods
- Created demo project
