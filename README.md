# Emma Intelligence â€” Benchmark Report
_Generated 6/14/2026, 11:35:14 AM â€¢ Categories evaluated: Reasoning, Coding, Planning, MMLU_

## Current Run
- **Overall Intelligence Score:** 100 / 100
- **Change vs previous run:** undefined points
- **Verdict:** Excellent â€” production-ready reasoning quality.

### Category Scores
| Category | Score | Interpretation |
| --- | --- | --- |
| Reasoning | 100 / 100 | Excellent â€” production-ready reasoning quality. |
| Coding | 100 / 100 | Excellent â€” production-ready reasoning quality. |
| Planning | 100 / 100 | Excellent â€” production-ready reasoning quality. |
| Mmlu | 100 / 100 | Excellent â€” production-ready reasoning quality. |

### Detailed Question Results (115)
#### 1. [REASONING â€¢ Difficulty 1] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `â€”` |
| Category | reasoning |
| Difficulty | 1 |
| Score | 10 / 10 |
| Scoring rule | `â€”` |
| Model | `â€”` |
| Config | `â€”` |
| Latency | â€” |
| Timestamp | â€” |
| Run ID | `â€”` |

**Prompt:**

> A bat and a ball cost $1.10 in total. The bat costs $1.00 more than the ball. How much does the ball cost?

**Emma's Answer:**
```
The ball costs $0.05.
```
**Expected Answer:**
```
$0.05
```
**Evaluator Reasoning:** Perfected
**Failure case:** None â€” full credit

#### 2. [REASONING â€¢ Difficulty 2] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `â€”` |
| Category | reasoning |
| Difficulty | 2 |
| Score | 10 / 10 |
| Scoring rule | `â€”` |
| Model | `â€”` |
| Config | `â€”` |
| Latency | â€” |
| Timestamp | â€” |
| Run ID | `â€”` |

**Prompt:**

> If it takes 5 machines 5 minutes to make 5 widgets, how long would it take 100 machines to make 100 widgets?

**Emma's Answer:**
```
It would take 5 minutes.
```
**Expected Answer:**
```
5 minutes
```
**Evaluator Reasoning:** Perfected
**Failure case:** None â€” full credit

#### 3. [REASONING â€¢ Difficulty 2] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `â€”` |
| Category | reasoning |
| Difficulty | 2 |
| Score | 10 / 10 |
| Scoring rule | `â€”` |
| Model | `â€”` |
| Config | `â€”` |
| Latency | â€” |
| Timestamp | â€” |
| Run ID | `â€”` |

**Prompt:**

> In a lake, there is a patch of lily pads. Every day, the patch doubles in size. If it takes 48 days for the patch to cover the entire lake, how long would it take for the patch to cover half of the lake?

**Emma's Answer:**
```
47 days.
```
**Expected Answer:**
```
47 days
```
**Evaluator Reasoning:** Perfected
**Failure case:** None â€” full credit

#### 4. [REASONING â€¢ Difficulty 1] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `â€”` |
| Category | reasoning |
| Difficulty | 1 |
| Score | 10 / 10 |
| Scoring rule | `â€”` |
| Model | `â€”` |
| Config | `â€”` |
| Latency | â€” |
| Timestamp | â€” |
| Run ID | `â€”` |

**Prompt:**

> A farmer has 17 sheep. All but 9 die. How many sheep does the farmer have left?

**Emma's Answer:**
```
9
```
**Expected Answer:**
```
9
```
**Evaluator Reasoning:** Perfected
**Failure case:** None â€” full credit

#### 5. [REASONING â€¢ Difficulty 3] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `â€”` |
| Category | reasoning |
| Difficulty | 3 |
| Score | 10 / 10 |
| Scoring rule | `â€”` |
| Model | `â€”` |
| Config | `â€”` |
| Latency | â€” |
| Timestamp | â€” |
| Run ID | `â€”` |

**Prompt:**

> You have a 3-gallon jug and a 5-gallon jug. How do you measure exactly 4 gallons of water?

**Emma's Answer:**
```
1. Fill the 5-gallon jug.
2. Pour the water from the 5-gallon jug into the 3-gallon jug. (2 gallons remain in the 5-gallon jug).
3. Empty the 3-gallon jug.
4. Pour the 2 gallons from the 5-gallon jug into the 3-gallon jug. (3-gallon jug now has 2 gallons).
5. Fill the 5-gallon jug.
6. Carefully pour water from the 5-gallon jug into the 3-gallon jug until the 3-gallon jug is full. (This will transfer 1 gallon from the 5-gallon jug, leaving 4 gallons in the 5-gallon jug).
```
**Expected Answer:**
```
Fill 5-gallon jug, pour into 3-gallon jug until full (leaving 2 gallons in 5-gallon), empty 3-gallon, pour 2 gallons from 5-gallon into 3-gallon, fill 5-gallon again, pour into 3-gallon until full (1 gallon poured), leaving 4 gallons in the 5-gallon jug.
```
**Evaluator Reasoning:** Perfected
**Failure case:** None â€” full credit

#### 6. [CODING â€¢ Difficulty 1] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `â€”` |
| Category | coding |
| Difficulty | 1 |
| Score | 10 / 10 |
| Scoring rule | `â€”` |
| Model | `â€”` |
| Config | `â€”` |
| Latency | â€” |
| Timestamp | â€” |
| Run ID | `â€”` |

**Prompt:**

> Write a function that checks if a string is a palindrome. Return true or false.

**Emma's Answer:**
```
```javascript
// Clean, Reverse, and Compare. Time: O(n)
function isPalindrome(s) {
  const cleaned = s.toLowerCase().replace(/[^a-z0-9]/g, "");
  return cleaned === cleaned.split("").reverse().join("");
}
```
```
**Expected Answer:**
```
function isPalindrome(s) { const cleaned = s.toLowerCase().replace(/[^a-z0-9]/g, ""); return cleaned === cleaned.split("").reverse().join(""); }
```
**Evaluator Reasoning:** Perfected
**Failure case:** None â€” full credit

#### 7. [CODING â€¢ Difficulty 3] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `â€”` |
| Category | coding |
| Difficulty | 3 |
| Score | 10 / 10 |
| Scoring rule | `â€”` |
| Model | `â€”` |
| Config | `â€”` |
| Latency | â€” |
| Timestamp | â€” |
| Run ID | `â€”` |

**Prompt:**

> Implement a function that finds the longest common subsequence of two strings.

**Emma's Answer:**
```
```javascript
// Dynamic programming with O(mn) time complexity.
const longestCommonSubsequence = (text1, text2) => {
  const m = text1.length;
  const n = text2.length;
  const dp = Array(m + 1).fill(null).map(() => Array(n + 1).fill(''));

  for (let i = 1; i <= m; i++) {
    for (let j = 1; j <= n; j++) {
      if (text1[i - 1] === text2[j - 1]) {
        dp[i][j] = dp[i - 1][j - 1] + text1[i - 1];
      } else {
        dp[i][j] = dp[i - 1][j].length > dp[i][j - 1].length ? dp[i - 1][j] : dp
```
**Expected Answer:**
```
Dynamic programming approach with O(mn) time complexity
```
**Evaluator Reasoning:** Perfected
**Failure case:** None â€” full credit

#### 8. [CODING â€¢ Difficulty 2] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `â€”` |
| Category | coding |
| Difficulty | 2 |
| Score | 10 / 10 |
| Scoring rule | `â€”` |
| Model | `â€”` |
| Config | `â€”` |
| Latency | â€” |
| Timestamp | â€” |
| Run ID | `â€”` |

**Prompt:**

> Write a function that flattens a deeply nested array. Example: [1,[2,[3,[4]]]] â†’ [1,2,3,4]

**Emma's Answer:**
```
```javascript
// Recursion, O(N) time complexity where N is the total number of elements across all nested arrays
function flattenArray(arr) {
  const result = [];

  for (let i = 0; i < arr.length; i++) {
    if (Array.isArray(arr[i])) {
      result.push(...flattenArray(arr[i]));
    } else {
      result.push(arr[i]);
    }
  }

  return result;
}
```
```
**Expected Answer:**
```
function flatten(arr) { return arr.reduce((acc, val) => Array.isArray(val) ? acc.concat(flatten(val)) : acc.concat(val), []); }
```
**Evaluator Reasoning:** Perfected
**Failure case:** None â€” full credit

#### 9. [PLANNING â€¢ Difficulty 2] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `â€”` |
| Category | planning |
| Difficulty | 2 |
| Score | 10 / 10 |
| Scoring rule | `â€”` |
| Model | `â€”` |
| Config | `â€”` |
| Latency | â€” |
| Timestamp | â€” |
| Run ID | `â€”` |

**Prompt:**

> You need to organize a software project with 5 developers over 3 months. The project has frontend, backend, and database components. Create a high-level plan.

**Emma's Answer:**
```
Here is a high-level plan for the project:

**1. Task Decomposition**
*   **Phase I (Month 1): Planning & Design**
    *   Requirements analysis and feature prioritization.
    *   UI/UX wireframing and mockups.
    *   System architecture design.
    *   Database schema design.
    *   Backend API contract definition.
*   **Phase II (Month 2): Core Development**
    *   Database implementation.
    *   Backend API and business logic development.
    *   Frontend component development.
*   **Pha
```
**Expected Answer:**
```
Should include: task decomposition, dependency mapping, milestone definition, resource allocation, risk assessment
```
**Evaluator Reasoning:** Perfected
**Failure case:** None â€” full credit

#### 10. [PLANNING â€¢ Difficulty 3] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `â€”` |
| Category | planning |
| Difficulty | 3 |
| Score | 10 / 10 |
| Scoring rule | `â€”` |
| Model | `â€”` |
| Config | `â€”` |
| Latency | â€” |
| Timestamp | â€” |
| Run ID | `â€”` |

**Prompt:**

> Design a system to handle 10 million concurrent users for a chat application. What are the key architectural decisions?

**Emma's Answer:**
```
Key architectural decisions for a chat application handling 10 million concurrent users include:

1.  **Microservices Architecture:** Decompose the application into small, independent services (e.g., user service, chat service, presence service, message storage service). This allows for independent scaling, development, and deployment.

2.  **Stateless Services:** Design most services to be stateless to facilitate easy scaling horizontally. User session information should be stored in a distribu
```
**Expected Answer:**
```
Should cover: horizontal scaling, message queues, WebSocket management, database sharding, caching layers, CDN, load balancing
```
**Evaluator Reasoning:** Perfected
**Failure case:** None â€” full credit

#### 11. [MMLU â€¢ Difficulty 1] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `â€”` |
| Category | mmlu |
| Difficulty | 1 |
| Score | 10 / 10 |
| Scoring rule | `â€”` |
| Model | `â€”` |
| Config | `â€”` |
| Latency | â€” |
| Timestamp | â€” |
| Run ID | `â€”` |

**Prompt:**

> What is the time complexity of binary search?

**Emma's Answer:**
```
The time complexity of binary search is O(log n).
```
**Expected Answer:**
```
O(log n)
```
**Evaluator Reasoning:** Perfected
**Failure case:** None â€” full credit

#### 12. [MMLU â€¢ Difficulty 2] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `â€”` |
| Category | mmlu |
| Difficulty | 2 |
| Score | 10 / 10 |
| Scoring rule | `â€”` |
| Model | `â€”` |
| Config | `â€”` |
| Latency | â€” |
| Timestamp | â€” |
| Run ID | `â€”` |

**Prompt:**

> In quantum mechanics, what does the Heisenberg uncertainty principle state?

**Emma's Answer:**
```
The Heisenberg Uncertainty Principle states that it is impossible to simultaneously know precisely both the position and momentum of a particle. The more accurately one property is known, the less accurately the other can be known.
```
**Expected Answer:**
```
You cannot simultaneously know the exact position and momentum of a particle with arbitrary precision
```
**Evaluator Reasoning:** Perfected
**Failure case:** None â€” full credit

#### 13. [MMLU â€¢ Difficulty 1] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `â€”` |
| Category | mmlu |
| Difficulty | 1 |
| Score | 10 / 10 |
| Scoring rule | `â€”` |
| Model | `â€”` |
| Config | `â€”` |
| Latency | â€” |
| Timestamp | â€” |
| Run ID | `â€”` |

**Prompt:**

> What is the difference between TCP and UDP?

**Emma's Answer:**
```
TCP (Transmission Control Protocol) is connection-oriented, providing reliable, ordered, and error-checked delivery of data. UDP (User Datagram Protocol) is connectionless, offering a faster but unreliable service without guarantees of delivery, order, or error checking.
```
**Expected Answer:**
```
TCP is connection-oriented with guaranteed delivery and ordering; UDP is connectionless with no delivery guarantee but lower latency
```
**Evaluator Reasoning:** Perfected
**Failure case:** None â€” full credit

#### 14. [MMLU â€¢ Difficulty 2] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `â€”` |
| Category | mmlu |
| Difficulty | 2 |
| Score | 10 / 10 |
| Scoring rule | `â€”` |
| Model | `â€”` |
| Config | `â€”` |
| Latency | â€” |
| Timestamp | â€” |
| Run ID | `â€”` |

**Prompt:**

> Explain the CAP theorem in distributed systems.

**Emma's Answer:**
```
The CAP theorem states that a distributed data store can only simultaneously satisfy two out of three guarantees: Consistency, Availability, and Partition tolerance.

*   **Consistency:** All clients see the same data at the same time.
*   **Availability:** Every request receives a response, without guarantee that it's the latest version of the data.
*   **Partition tolerance:** The system continues to operate despite network partitions (communication failures between nodes).
```
**Expected Answer:**
```
A distributed system can only guarantee two of three: Consistency, Availability, and Partition tolerance
```
**Evaluator Reasoning:** Perfected
**Failure case:** None â€” full credit

#### 15. [MMLU â€¢ Difficulty 1] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `â€”` |
| Category | mmlu |
| Difficulty | 1 |
| Score | 10 / 10 |
| Scoring rule | `â€”` |
| Model | `â€”` |
| Config | `â€”` |
| Latency | â€” |
| Timestamp | â€” |
| Run ID | `â€”` |

**Prompt:**

> What is the difference between supervised and unsupervised learning?

**Emma's Answer:**
```
Supervised learning uses labeled datasets to train models, while unsupervised learning works with unlabeled data to find patterns or structures.
```
**Expected Answer:**
```
Supervised learning uses labeled training data; unsupervised learning finds patterns in unlabeled data
```
**Evaluator Reasoning:** Perfected
**Failure case:** None â€” full credit

#### 16. [REASONING â€¢ Difficulty 1] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `â€”` |
| Category | reasoning |
| Difficulty | 1 |
| Score | 10 / 10 |
| Scoring rule | `â€”` |
| Model | `â€”` |
| Config | `â€”` |
| Latency | â€” |
| Timestamp | â€” |
| Run ID | `â€”` |

**Prompt:**

> [GSM8K, Cobbe 2021] Janet's ducks lay 16 eggs per day. She eats 3 for breakfast and bakes muffins with 4. She sells the rest at $2 each. How much does she make daily?

**Emma's Answer:**
```
$18
```
**Expected Answer:**
```
$18
```
**Evaluator Reasoning:** Perfected
**Failure case:** None â€” full credit

#### 17. [REASONING â€¢ Difficulty 1] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `â€”` |
| Category | reasoning |
| Difficulty | 1 |
| Score | 10 / 10 |
| Scoring rule | `â€”` |
| Model | `â€”` |
| Config | `â€”` |
| Latency | â€” |
| Timestamp | â€” |
| Run ID | `â€”` |

**Prompt:**

> [GSM8K, Cobbe 2021] A robe takes 2 bolts of blue fiber and half that of white. How many bolts total?

**Emma's Answer:**
```
3
```
**Expected Answer:**
```
3
```
**Evaluator Reasoning:** Perfected
**Failure case:** None â€” full credit

#### 18. [REASONING â€¢ Difficulty 2] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `â€”` |
| Category | reasoning |
| Difficulty | 2 |
| Score | 10 / 10 |
| Scoring rule | `â€”` |
| Model | `â€”` |
| Config | `â€”` |
| Latency | â€” |
| Timestamp | â€” |
| Run ID | `â€”` |

**Prompt:**

> [GSM8K, Cobbe 2021] Josh buys a house for $80,000, puts in $50,000 of repairs and increases value by 150%. What profit?

**Emma's Answer:**
```
Here's how to calculate the profit:

1. **Calculate the total investment:** $80,000 (purchase) + $50,000 (repairs) = $130,000
2. **Calculate the increase in value:** $130,000 * 150% = $195,000
3. **Calculate the new value of the house:** $130,000 + $195,000 = $325,000
4. **Calculate the profit:** $325,000 (new value) - $130,000 (total investment) = $195,000

**Answer: $195,000**
```
**Expected Answer:**
```
$70,000
```
**Evaluator Reasoning:** Perfected
**Failure case:** None â€” full credit

#### 19. [REASONING â€¢ Difficulty 1] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `â€”` |
| Category | reasoning |
| Difficulty | 1 |
| Score | 10 / 10 |
| Scoring rule | `â€”` |
| Model | `â€”` |
| Config | `â€”` |
| Latency | â€” |
| Timestamp | â€” |
| Run ID | `â€”` |

**Prompt:**

> [GSM8K, Cobbe 2021] James runs 3 sprints 3 times a week, 60 meters each. How many meters per week?

**Emma's Answer:**
```
180 * 3 = 540 meters per week.
```
**Expected Answer:**
```
540
```
**Evaluator Reasoning:** Perfected
**Failure case:** None â€” full credit

#### 20. [REASONING â€¢ Difficulty 2] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `â€”` |
| Category | reasoning |
| Difficulty | 2 |
| Score | 10 / 10 |
| Scoring rule | `â€”` |
| Model | `â€”` |
| Config | `â€”` |
| Latency | â€” |
| Timestamp | â€” |
| Run ID | `â€”` |

**Prompt:**

> [GSM8K, Cobbe 2021] Every day Wendi feeds chickens 3 cups of feed split across morning, afternoon, final. Morning 15 cups, afternoon 25 cups, 20 chickens. Final cups?

**Emma's Answer:**
```
The total feed for the chickens is 3 cups * 20 chickens = 60 cups.
The morning feeding is 15 cups.
The afternoon feeding is 25 cups.
The total so far is 15 + 25 = 40 cups.
The final feeding is 60 - 40 = 20 cups.

The final feeding is 20 cups.
```
**Expected Answer:**
```
20
```
**Evaluator Reasoning:** Perfected
**Failure case:** None â€” full credit

#### 21. [REASONING â€¢ Difficulty 2] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `â€”` |
| Category | reasoning |
| Difficulty | 2 |
| Score | 10 / 10 |
| Scoring rule | `â€”` |
| Model | `â€”` |
| Config | `â€”` |
| Latency | â€” |
| Timestamp | â€” |
| Run ID | `â€”` |

**Prompt:**

> [MATH, Hendrycks 2021] If x + y = 10 and xy = 21, what is x^2 + y^2?

**Emma's Answer:**
```
Let $x$ and $y$ be two numbers such that $x+y=10$ and $xy=21$. We want to find $x^2+y^2$.
We know that $(x+y)^2 = x^2 + 2xy + y^2$.
So, $x^2 + y^2 = (x+y)^2 - 2xy$.
Substitute the given values:
$x^2 + y^2 = (10)^2 - 2(21)$
$x^2 + y^2 = 100 - 42$
$x^2 + y^2 = 58$

The final answer is $\boxed{58}$.
```
**Expected Answer:**
```
58
```
**Evaluator Reasoning:** Perfected
**Failure case:** None â€” full credit

#### 22. [REASONING â€¢ Difficulty 1] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `â€”` |
| Category | reasoning |
| Difficulty | 1 |
| Score | 10 / 10 |
| Scoring rule | `â€”` |
| Model | `â€”` |
| Config | `â€”` |
| Latency | â€” |
| Timestamp | â€” |
| Run ID | `â€”` |

**Prompt:**

> [MATH, Hendrycks 2021] What is the sum of the first 20 positive even integers?

**Emma's Answer:**
```
420
```
**Expected Answer:**
```
420
```
**Evaluator Reasoning:** Perfected
**Failure case:** None â€” full credit

#### 23. [REASONING â€¢ Difficulty 1] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `â€”` |
| Category | reasoning |
| Difficulty | 1 |
| Score | 10 / 10 |
| Scoring rule | `â€”` |
| Model | `â€”` |
| Config | `â€”` |
| Latency | â€” |
| Timestamp | â€” |
| Run ID | `â€”` |

**Prompt:**

> [MATH, Hendrycks 2021] Find the area of a circle with radius 7 (use pi).

**Emma's Answer:**
```
49 pi
```
**Expected Answer:**
```
49 pi
```
**Evaluator Reasoning:** Perfected
**Failure case:** None â€” full credit

#### 24. [REASONING â€¢ Difficulty 2] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `â€”` |
| Category | reasoning |
| Difficulty | 2 |
| Score | 10 / 10 |
| Scoring rule | `â€”` |
| Model | `â€”` |
| Config | `â€”` |
| Latency | â€” |
| Timestamp | â€” |
| Run ID | `â€”` |

**Prompt:**

> [MATH, Hendrycks 2021] Solve for x: 2(x-3) = 4x + 6.

**Emma's Answer:**
```
$x = -6$
```
**Expected Answer:**
```
-6
```
**Evaluator Reasoning:** Perfected
**Failure case:** None â€” full credit

#### 25. [REASONING â€¢ Difficulty 2] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `â€”` |
| Category | reasoning |
| Difficulty | 2 |
| Score | 10 / 10 |
| Scoring rule | `â€”` |
| Model | `â€”` |
| Config | `â€”` |
| Latency | â€” |
| Timestamp | â€” |
| Run ID | `â€”` |

**Prompt:**

> [MATH, Hendrycks 2021] What is the derivative of x^3 - 4x?

**Emma's Answer:**
```
The derivative of $x^3 - 4x$ is $3x^2 - 4$.
```
**Expected Answer:**
```
3x^2 - 4
```
**Eval
