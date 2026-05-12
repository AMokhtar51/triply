### Function 2: `getMembers()` - Class: Trip 
**Execution Paths:** 
- P1: No accepted members in trip_members → return `[]` 
- P2: Accepted members exist → fetch user details from accounts DB → return enriched array | Test Case | Input | Expected Output | Path Covered | |-----------|-------|-----------------|--------------| | TC1 | Trip with no accepted members | `[]` | P1 | | TC2 | Trip with 1 accepted member (user_id=2, email=member@example.com) | array with id=2, email, role, trip_role | P2 | ---