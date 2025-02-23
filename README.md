# Lua Implicit Type Conversion Bug

This repository demonstrates an uncommon Lua error related to implicit type conversion. When performing arithmetic operations, Lua expects numeric values. If you try to perform arithmetic on a string, it will throw an error.  This is especially tricky when dealing with functions that may receive `nil` values that are then implicitly converted to strings.