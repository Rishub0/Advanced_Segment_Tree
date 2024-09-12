# Lazy Segment Tree

## Features

### Lazy Propagation
- **Efficient Range Updates**: Supports range updates with lazy propagation. Updates are delayed and applied only when necessary, improving efficiency, especially for large datasets.

### Point Updates
- **Modify Specific Index**: Allows individual element updates at a specific index using `modify(p, v)`.

### Range Queries
- **Query Over a Range**: Supports querying over a range `[l, r]` using `rangeQuery(l, r)`. Ideal for problems like finding sums, minimums, or maximums over a subarray.

### Range Updates
- **Apply Updates Over a Range**: Allows applying updates over a range `[l, r]` using `rangeApply(l, r, v)`. Supports various update operations such as adding, setting, or multiplying values over a subarray.

### Customizable Info and Tag
- **Info Struct**: Defines how the tree stores and combines data, such as sum, max, or min.
- **Tag Struct**: Allows defining how the lazy tags are applied, such as incrementing or setting values.

### First and Last Element Matching Condition
- **Condition-Based Search**: Find the first or last index within a range `[l, r]` that satisfies a certain condition using `findFirst(l, r, pred)` and `findLast(l, r, pred)`. This is useful for binary search-like problems.

### Supports Complex Operations
- **Customizable Info for Advanced Use Cases**: The `Info` struct can be tailored for complex operations like range maximums, range sums, secondary maximums, etc. For example, it can compute the first and second maximums and their frequencies.

### Flexible Template
- **Adaptable for Different Data Types**: The template works with any type of data that supports the `+` operator for combining, making it versatile for various kinds of problems.

## Conclusion
These features make the Lazy Segment Tree a powerful and flexible tool for solving a wide range of range-query and range-update problems efficiently.
