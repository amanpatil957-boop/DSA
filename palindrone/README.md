## Palindrome Number (LeetCode)

**Problem:** Check whether an integer reads the same forward and backward.

**Approach:** Reverse the number using the modulo (%) operator to extract digits and integer division (/) to remove digits. Compare the reversed number with the original number. Negative numbers are not palindromes.

**Time Complexity:** O(log n)

**Space Complexity:** O(1)

**Language:** C++