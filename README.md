# Dart Reduce Method Error Handling

This repository demonstrates an uncommon error that can occur when using the `reduce` method in Dart.  The `reduce` method requires at least one element in the list; otherwise, it throws a `StateError`. This example highlights the importance of adding error handling to prevent unexpected crashes.

## Bug
The provided Dart code uses the `reduce` method to calculate the sum of elements in a list.  However, when an empty list is passed, it throws a `StateError` because the reduce method cannot operate without elements.

## Solution
The solution involves adding a check to ensure the list is not empty before calling `reduce`.  If the list is empty, a default value (in this case, 0) is returned, preventing the error.

Feel free to contribute and improve upon this example.  This is important for robust error handling in any Dart application.