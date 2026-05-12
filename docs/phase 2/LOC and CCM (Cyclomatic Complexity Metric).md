Explanation

LOC (Lines of Code): This counts only non-blank, non-comment lines inside the function body. It measures the size of the function.

CCM (Cyclomatic Complexity Metric): This is calculated as the number of decision points (keywords like `if`, `elseif`, `foreach`, `while`, `case`, and operators like `&&`, `||`) plus 1. It indicates the complexity based on branching logic.

| Function              | Class     | LOC | CCM | 
|-----------------------|-----------|-----|-----|
| calculateSettlement   | Itinerary | 31  | 6   |
| applyTransportBuffers | Itinerary | 22  | 4   |
| detectConflicts       | Itinerary | 17  | 4   | 
| getCurrentItinerary   | Itinerary | 18  | 4   |
| getMembers          | Trip      | 38  | 5   |
| splitByPercentage   | Expense   | 5   | 2   |
