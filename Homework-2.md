# Home Wwork - 2

## Questions

1. Modular arithmetic - you just need to find examples, you don't need to prove anything. <br />
    (a) Is it true that all odd squares are ≡ 1 (mod 8) ? <br />
    (b) what about even squares (mod 8) ?
2. What do you understand by
    1. O(n)
    2. O(1)
    3. O(log n)

## Answer for Proof Modular

**1. Modular Arithmetic:**
  (a). Is it true that all odd squares are ≡ 1 (mod 8) ?

   ```
   Assuming that k is in Z and n is odd for n = (2k+1)
   The square of n^2, (2k+1)^2 = 4k^2+4k+1 = 4k(k+1)+1
   Since k is odd and k+1 is even, then 4k(k+1) will be equal 0 and +1 will be equal to 1.
   ∴ (2k+1)^2 ≡ 1 mod 8 is true for all odd squares.
   ```
   
   (b) what about even squares (mod 8) ?

   ```
   Assuming that n is even and k can be even or odd, we can let n = 2k.
   Then n^2 = (2k)^2 = 4k^2
   Let's say k is odd, k^2 is still odd.
   Knowing that k^2 is odd, we can let k^2 = 2n+1, then 4k^2 = 4(2n+1) = 8n+4 ≡ 0 mod 8
   ∴ (2k)^2 ≡ 0 mod 8 is NOT true for all even squares.
   ```

**2. Complexity Understanding:**

   (a). **O(n):** denotes linear time complexity. An algorithm is said to have O(n) complexity if the time to complete the task grows linearly with the size of the input data set.

   (b). **O(1):** denotes constant time complexity. This implies that the algorithm takes the same amount of time to complete, regardless of the size of the input data set.

   (c). **O(log n):** denotes logarithmic time complexity. An algorithm has O(log n) complexity if the time to complete the task increases logarithmically as the input size increases. This is typical of algorithms that divide the problem space in half each time, such as binary search.
