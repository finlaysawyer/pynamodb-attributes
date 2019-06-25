<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [pynamodb-attributes](#pynamodb-attributes)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# pynamodb-attributes

This Python 3 library contains compound and high-level PynamoDB attributes:

- `IntegerAttribute` – same as `NumberAttribute` but whose value is typed as `int` (rather than `float`)
- `UnicodeDelimitedTupleAttribute` - a delimiter-separated value, useful for storing composite keys
- `UnicodeEnumAttribute` - serializes a string-valued `Enum` into a Unicode (`S`-typed) attribute
- `TimestampAttribute`, `TimestampMsAttribute`, `TimestampUsAttribute` – serializes `datetime`s as Unix epoch seconds, milliseconds (ms) or microseconds (µs)
- `IntegerDateAttribute` - serializes `date` as an integer representing the Gregorian date (e.g. `20181231`)
