## Complexity Analysis

### Time Complexity

- **Methods in `riceCooker` object**: Each method has a time complexity of O(1). The `delaySync` function has a time complexity of O(n), where n is the input duration in milliseconds.

- **`simulateRiceCooker` function**: The time complexity is O(I), where I is the number of iterations in the loop..

### Space Complexity

1. **`RiceCooker` Object**: O(1) as it contains a fixed set of boolean properties (`ricePresent`, `riceCooked`, `steamingInProgress`, `heatingInProgress`).

2. **Menu Simulation (`simulateRiceCooker`)**: O(1) as it uses a constant amount of memory for variables like `input`, `condition`, and `choice`.


**As the differences between `refactor.js` and `to_refactor.js` and the use of switch case and delete unnecessary variables, the complexity is not affected approximately**
