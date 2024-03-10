# Home Work - 1

## Questions

1. Working with the following set of Integers S = {0,1,2,3,4,5,6}. <br />
   What is the result of the following operations ? <br/>
   (a) 4 + 4 <br/>
   (b) 3 x 5 <br/>
   (c) what is the inverse of 3 ? <br/>

2. For S = {0,1,2,3,4,5,6}, can we consider 'S' and the operation '+' to be a group ?

3. What is -13 mod 5 ?

4. For the polynomial x^3 − x^2 + 4x − 12 Find a positive root ? What is the degree of this polynomial ?

### Answers

**1(a)**.

```
4 + 4 = 8
8 % 7 = 1
∴ 4 + 4 ≡ 1 mod 7
```

**1(b)**.

```
3 * 5 = 15
15 % 7 = 1
∴ 3 * 5 ≡ 1 mod 7
```

**1(c)**.

```
Using a^-1 ≡ a^(p-2)(modp)
∴ 3^(7-2) = 3^5 = 243 ≡ 5 mod 7
∴ 3^(5) = 3×3×3×3×3 = 243 mod 7 = 5
So, the inverse of 3 is  5.
```

**2**.

```
Yes, we can consider 'S' and the operation '+' to be a group as it follows all of the group properties.
```

**3**.

```
Since the result cannot be a -ve number, we add 5 to -13 until we get a +ve number.
∴ -13 % 5 ≡ 2 mod 5
```

**4**.

```
Since 2^3 + 2^2 + 4(2) - 12 = 8 - 4 + 8 - 12 = 0
∴ x = 2 is a root.
∴ The degree of polynomial is the highest exponent which is 3.
```

### Uses Cases

1. Have you seen any applications of zero knowledge proofs other than with a blockchain?

   - **Authentication Systems:** ZKPs can be used in authentication systems to prove the identity of a user without revealing their actual credentials or sensitive information. This can be particularly useful for password-less logins and access control systems.
  
   - **Voting Systems:** In electronic voting, ZKPs can ensure that votes are correctly counted without revealing the choice of each voter, thus maintaining ballot secrecy while ensuring a fair election.
  
   - **Secure Multi-party Computation:** ZKPs allow multiple parties to jointly compute a function over their inputs while keeping those inputs private. This has potential applications in private bidding, data sharing among competitors, and more.
  
   - **Privacy-Preserving Data Sharing:** They can enable the sharing of data insights and performing analytics while ensuring that the underlying data remains private, which is crucial in sectors like healthcare and finance.

2. What is to you, the most important feature of zkp technology ?

   - To me, the most significant feature of ZKP technology is its ability to enhance privacy without sacrificing security. In an era where data breaches are common, ZKPs offer a powerful tool for verifying transactions, identities, and other claims without revealing any underlying private information. This balance of privacy and security is essential for building trust in digital interactions.
  
3. Think of some use cases of zero knowledge proofs that you would like to see developed.

   - **Credit Scoring:** Implementing ZKPs in credit scoring could allow individuals to prove their creditworthiness without disclosing their financial history, income, or personal details.
  
   - **Education Credentials:** ZKPs could enable students to prove they have obtained certain qualifications from educational institutions without revealing their entire educational history or personal details.
  
   - **Healthcare Data Research:** Researchers could use ZKPs to access and query medical databases for population studies without compromising patient privacy, thus enabling more robust medical research while adhering to strict confidentiality protocols.
  
   - **Private Identity Verification:** ZKPs could be used for age or eligibility verification for services without revealing any other personal information, such as exact age, name, or other identifiers.
  
   - **Secure Supply Chains:** ZKPs can prove the authenticity and ethical sourcing of products in a supply chain without revealing trade secrets or supplier relationships.
  