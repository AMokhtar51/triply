## Q14 - OO Complexity Metrics

### Equations Used

- **WMC** = sum of CCM of all methods in the class
- **DIT** = depth in inheritance chain (0 = no parent, 1 = extends one class)
- **NOC** = number of direct subclasses of this class in the codebase
- **CBO** = number of distinct external classes this class instantiates or calls
- **RFC** = number of methods defined in class + number of distinct external methods called
- **LCOM** = (number of method pairs sharing NO instance variable) ÷ (total number of method pairs)

### Results

| Class     | WMC | DIT | NOC | CBO | RFC | LCOM |
|-----------|-----|-----|-----|-----|-----|------|
| Itinerary | 18  | 0   | 0   | 3   | 15  | 0.71 |
| Trip      | 20  | 0   | 0   | 3   | 18  | 0.60 |
| Expense   | 14  | 0   | 0   | 2   | 14  | 0.44 |
