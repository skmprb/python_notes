**Q: Why should we avoid string concatenation in loops and use list accumulation with join instead?**

**A:** String concatenation in loops (e.g., `s += item`) creates a new string object each iteration, resulting in O(n²) time complexity. Using list accumulation with join (e.g., `''.join(list)`) is O(n) because it allocates memory once and builds the final string efficiently.
**Reason : Strings are immutable need to re loop for every addition**
