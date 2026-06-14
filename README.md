# Emma Intelligence â€” Benchmark Report
_Generated 6/14/2026, 11:29:23 AM â€¢ Categories evaluated: Reasoning, Coding, Planning, MMLU_

## Current Run
- **Overall Intelligence Score:** 92 / 100
- **Change vs previous run:** -8 points
- **Verdict:** Excellent â€” production-ready reasoning quality.

### Category Scores
| Category | Score | Interpretation |
| --- | --- | --- |
| Reasoning | 86 / 100 | Excellent â€” production-ready reasoning quality. |
| Coding | 98 / 100 | Excellent â€” production-ready reasoning quality. |
| Planning | 86 / 100 | Excellent â€” production-ready reasoning quality. |
| Mmlu | 98 / 100 | Excellent â€” production-ready reasoning quality. |

### Detailed Question Results (115)
#### 1. [REASONING â€¢ Difficulty 1] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `12e1dc8f-4cd3-41e9-9abb-327025a0a863` |
| Category | reasoning |
| Difficulty | 1 |
| Score | 10 / 10 |
| Scoring rule | `substring-match` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048}` |
| Latency | 870 ms |
| Timestamp | 2026-06-14T18:29:09.469Z |
| Run ID | `358af654-96e5-48d4-8557-ff6f9efc9e56` |

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
**Evaluator Reasoning:** Normalized answer contains (or is contained in) expected answer
**Failure case:** None â€” full credit

#### 2. [REASONING â€¢ Difficulty 2] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `ed8c0960-b42a-472c-af2b-bf0097c3ffbb` |
| Category | reasoning |
| Difficulty | 2 |
| Score | 10 / 10 |
| Scoring rule | `substring-match` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048}` |
| Latency | 866 ms |
| Timestamp | 2026-06-14T18:29:09.470Z |
| Run ID | `358af654-96e5-48d4-8557-ff6f9efc9e56` |

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
**Evaluator Reasoning:** Normalized answer contains (or is contained in) expected answer
**Failure case:** None â€” full credit

#### 3. [REASONING â€¢ Difficulty 2] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `fdb289b9-4c8f-4ac7-bcaa-697cb53e61d6` |
| Category | reasoning |
| Difficulty | 2 |
| Score | 10 / 10 |
| Scoring rule | `substring-match` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048}` |
| Latency | 802 ms |
| Timestamp | 2026-06-14T18:29:09.470Z |
| Run ID | `358af654-96e5-48d4-8557-ff6f9efc9e56` |

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
**Evaluator Reasoning:** Normalized answer contains (or is contained in) expected answer
**Failure case:** None â€” full credit

#### 4. [REASONING â€¢ Difficulty 1] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `ef7556c7-7df6-4662-84d7-4ac66384e932` |
| Category | reasoning |
| Difficulty | 1 |
| Score | 10 / 10 |
| Scoring rule | `substring-match` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048}` |
| Latency | 829 ms |
| Timestamp | 2026-06-14T18:29:09.470Z |
| Run ID | `358af654-96e5-48d4-8557-ff6f9efc9e56` |

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
**Evaluator Reasoning:** Normalized answer contains (or is contained in) expected answer
**Failure case:** None â€” full credit

#### 5. [REASONING â€¢ Difficulty 3] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `1017c391-be51-40ed-93e1-e866b7b74af0` |
| Category | reasoning |
| Difficulty | 3 |
| Score | 10 / 10 |
| Scoring rule | `keyword-coverage>=0.5` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048}` |
| Latency | 2084 ms |
| Timestamp | 2026-06-14T18:29:09.471Z |
| Run ID | `358af654-96e5-48d4-8557-ff6f9efc9e56` |

**Prompt:**

> You have a 3-gallon jug and a 5-gallon jug. How do you measure exactly 4 gallons of water?

**Emma's Answer:**
```
1. Fill the 5-gallon jug.
2. Pour the water from the 5-gallon jug into the 3-gallon jug, leaving 2 gallons in the 5-gallon jug.
3. Empty the 3-gallon jug.
4. Pour the 2 gallons from the 5-gallon jug into the 3-gallon jug.
5. Fill the 5-gallon jug.
6. Carefully pour water from the 5-gallon jug into the 3-gallon jug (which already has 2 gallons) until the 3-gallon jug is full. This will use 1 gallon from the 5-gallon jug.
7. The 5-gallon jug now contains exactly 4 gallons.
```
**Expected Answer:**
```
Fill 5-gallon jug, pour into 3-gallon jug until full (leaving 2 gallons in 5-gallon), empty 3-gallon, pour 2 gallons from 5-gallon into 3-gallon, fill 5-gallon again, pour into 3-gallon until full (1 gallon poured), leaving 4 gallons in the 5-gallon jug.
```
**Evaluator Reasoning:** 12/14 keywords (86%)
**Failure case:** None â€” full credit

#### 6. [CODING â€¢ Difficulty 1] â€” 8/10

| Metric | Value |
| --- | --- |
| Prompt ID | `66f3eca1-836f-45f3-9a85-daf08ab23572` |
| Category | coding |
| Difficulty | 1 |
| Score | 8 / 10 |
| Scoring rule | `keyword-coverage>=0.3` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048}` |
| Latency | 1157 ms |
| Timestamp | 2026-06-14T18:29:09.471Z |
| Run ID | `358af654-96e5-48d4-8557-ff6f9efc9e56` |

**Prompt:**

> Write a function that checks if a string is a palindrome. Return true or false.

**Emma's Answer:**
```
```javascript
// Two Pointers
// Time Complexity: O(n)
const isPalindrome = (str) => {
  let left = 0;
  let right = str.length - 1;

  while (left < right) {
    if (str[left] !== str[right]) {
      return false;
    }
    left++;
    right--;
  }

  return true;
};
```
```
**Expected Answer:**
```
function isPalindrome(s) { const cleaned = s.toLowerCase().replace(/[^a-z0-9]/g, ""); return cleaned === cleaned.split("").reverse().join(""); }
```
**Evaluator Reasoning:** 3/10 keywords (30%)
**Failure case:** Partial credit â€” 3/10 keywords (30%)

#### 7. [CODING â€¢ Difficulty 3] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `3559b66f-5e01-40af-914d-d46304ca1ccb` |
| Category | coding |
| Difficulty | 3 |
| Score | 10 / 10 |
| Scoring rule | `code-pattern-lcs` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048}` |
| Latency | 2047 ms |
| Timestamp | 2026-06-14T18:29:09.471Z |
| Run ID | `358af654-96e5-48d4-8557-ff6f9efc9e56` |

**Prompt:**

> Implement a function that finds the longest common subsequence of two strings.

**Emma's Answer:**
```
```javascript
// Dynamic Programming: Finds the length of the LCS in O(mn) time, then reconstructs the LCS in O(m+n) time.
const longestCommonSubsequence = (text1, text2) => {
    const m = text1.length;
    const n = text2.length;
    const dp = Array(m + 1).fill(null).map(() => Array(n + 1).fill(0));

    // Fill the DP table to store lengths of LCS
    for (let i = 1; i <= m; i++) {
        for (let j = 1; j <= n; j++) {
            if (text1[i - 1] === text2[j - 1]) {
                dp[i][j] = 1 + dp[i - 1][j - 1];
            } else {
                dp[i][j] = Math.max(dp[i - 1][j], dp[i][j - 1]);
            }
        }
    }

    // Reconstruct the LCS from the DP table
    let i = m;
    let j = n;
    let lcs = [];
    while (i > 0 && j > 0) {
        if (text1[i - 1] === text2[j - 1]) {
            lcs.unshift(text1[i - 1]);
            i--;
            j--;
        } else if (dp[i - 1][j] > dp[i][j - 1]) {
            i--;
        } else {
            j--;
        }
    }

    return lcs.join('');
};
```
```
**Expected Answer:**
```
Dynamic programming approach with O(mn) time complexity
```
**Evaluator Reasoning:** Detected complete DP table, nested loops, and LCS recurrence
**Failure case:** None â€” full credit

#### 8. [CODING â€¢ Difficulty 2] â€” 8/10

| Metric | Value |
| --- | --- |
| Prompt ID | `da37aa93-5b36-405a-830a-3689a7ae83ab` |
| Category | coding |
| Difficulty | 2 |
| Score | 8 / 10 |
| Scoring rule | `keyword-coverage>=0.3` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048}` |
| Latency | 1172 ms |
| Timestamp | 2026-06-14T18:29:09.471Z |
| Run ID | `358af654-96e5-48d4-8557-ff6f9efc9e56` |

**Prompt:**

> Write a function that flattens a deeply nested array. Example: [1,[2,[3,[4]]]] â†’ [1,2,3,4]

**Emma's Answer:**
```
```javascript
// Recursion, O(N) time complexity where N is the total number of elements across all nested arrays.
const flattenArray = (arr) => {
  const result = [];

  for (let i = 0; i < arr.length; i++) {
    if (Array.isArray(arr[i])) {
      result.push(...flattenArray(arr[i]));
    } else {
      result.push(arr[i]);
    }
  }

  return result;
};
```
```
**Expected Answer:**
```
function flatten(arr) { return arr.reduce((acc, val) => Array.isArray(val) ? acc.concat(flatten(val)) : acc.concat(val), []); }
```
**Evaluator Reasoning:** 4/10 keywords (40%)
**Failure case:** Partial credit â€” 4/10 keywords (40%)

#### 9. [PLANNING â€¢ Difficulty 2] â€” 0/10

| Metric | Value |
| --- | --- |
| Prompt ID | `e94fdfbb-ff42-4a00-8093-83a47648c975` |
| Category | planning |
| Difficulty | 2 |
| Score | 0 / 10 |
| Scoring rule | `keyword-ratio` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048}` |
| Latency | 2361 ms |
| Timestamp | 2026-06-14T18:29:09.472Z |
| Run ID | `358af654-96e5-48d4-8557-ff6f9efc9e56` |

**Prompt:**

> You need to organize a software project with 5 developers over 3 months. The project has frontend, backend, and database components. Create a high-level plan.

**Emma's Answer:**
```
Here's a high-level plan:

**Month 1: Planning & Setup**
*   **Weeks 1-2:** Requirements gathering, system design (architecture for frontend, backend, database), tech stack finalization. Assign roles: 1 lead, 2 frontend, 1 backend, 1 database.
*   **Weeks 3-4:** Environment setup (dev, staging, production), CI/CD pipeline, basic API contracts, initial database schema design.

**Month 2: Core Development**
*   **Weeks 5-8:**
    *   **Frontend:** Core UI components, integration with mock APIs.
    *   **Backend:** Develop core API functionalities, business logic.
    *   **Database:** Implement detailed schema, initial data seeding.
    *   **All:** Regular integration, unit testing.

**Month 3: Integration, Testing & Deployment**
*   **Weeks 9-10:** Full integration of frontend, backend, and database. End-to-end testing, bug fixing.
*   **Weeks 11-12:** User Acceptance Testing (UAT), performance testing, security review, documentation, final deployment to production, post-launch monitoring setup.
```
**Expected Answer:**
```
Should include: task decomposition, dependency mapping, milestone definition, resource allocation, risk assessment
```
**Evaluator Reasoning:** 0/12 keywords (0%)
**Failure case:** No overlap with expected â€” 0/12 keywords (0%)

#### 10. [PLANNING â€¢ Difficulty 3] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `142fdb34-3ae6-44dc-b0c1-1e611a00844f` |
| Category | planning |
| Difficulty | 3 |
| Score | 10 / 10 |
| Scoring rule | `keyword-coverage>=0.5` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048}` |
| Latency | 4624 ms |
| Timestamp | 2026-06-14T18:29:09.472Z |
| Run ID | `358af654-96e5-48d4-8557-ff6f9efc9e56` |

**Prompt:**

> Design a system to handle 10 million concurrent users for a chat application. What are the key architectural decisions?

**Emma's Answer:**
```
Key Architectural Decisions:

1.  **Microservices Architecture:** Decompose the application into smaller, independent services (e.g., user management, chat service, presence service). This allows for independent scaling, development, and deployment.

2.  **Stateless Services:** Design services to be stateless to facilitate horizontal scaling. Session management should be externalized (e.g., Redis).

3.  **Real-time Communication Protocol:**
    *   **WebSockets:** Essential for bidirectional, low-latency communication between clients and servers.
    *   **MQTT:** Consider for mobile clients and constrained environments due to its lightweight nature.

4.  **Scalable Data Stores:**
    *   **NoSQL Databases (e.g., Cassandra, MongoDB):** For chat message storage, optimizing for high write throughput and horizontal scaling. Sharding will be crucial.
    *   **Distributed Cache (e.g., Redis, Memcached):** For presence information, frequently accessed data, and session management. Redis Pub/Sub for real-time updates.
    *   **Relational Database (e.g., PostgreSQL with sharding):** For user profiles, authentication, and other structured data if strong consistency is critical.

5.  **Message Queues (e.g., Kafka, RabbitMQ):**
    *   **Asynchronous Processing:** Decouple services, buffer requests, handle spikes, and enable reliable message delivery (e.g., sending offline messages, processing analytical data).
    *   **Fan-out:** Distribute messages to multiple subscribers (e.g., notifying all participants in a chat room).

6.  **Load Balancing:**
    *   **Layer 4 (TCP) Load Balancers (e.g., HAProxy, AWS NLB):** For initial connection distribution to real-time servers.
    *   **Layer 7 (HTTP) Load Balancers (e.g., Nginx, AWS ALB):** For API Gateway and HTTP-based services.

7.  **Service Discovery & Orchestration (e.g., Kubernetes, Nomad):** For automated deployment, scaling, health checks, and management of microservices.

8.  **Edge Caching & CDN:** For static assets a
```
**Expected Answer:**
```
Should cover: horizontal scaling, message queues, WebSocket management, database sharding, caching layers, CDN, load balancing
```
**Evaluator Reasoning:** 12/15 keywords (80%)
**Failure case:** None â€” full credit

#### 11. [MMLU â€¢ Difficulty 1] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `f77d890a-ba4d-4f59-829d-c2292ea0d8e6` |
| Category | mmlu |
| Difficulty | 1 |
| Score | 10 / 10 |
| Scoring rule | `substring-match` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048}` |
| Latency | 1485 ms |
| Timestamp | 2026-06-14T18:29:09.472Z |
| Run ID | `358af654-96e5-48d4-8557-ff6f9efc9e56` |

**Prompt:**

> What is the time complexity of binary search?

**Emma's Answer:**
```
O(log n)
```
**Expected Answer:**
```
O(log n)
```
**Evaluator Reasoning:** Normalized answer contains (or is contained in) expected answer
**Failure case:** None â€” full credit

#### 12. [MMLU â€¢ Difficulty 2] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `a85a261a-ffdc-4bb6-ac1b-33110185c6bd` |
| Category | mmlu |
| Difficulty | 2 |
| Score | 10 / 10 |
| Scoring rule | `keyword-coverage>=0.5` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048}` |
| Latency | 978 ms |
| Timestamp | 2026-06-14T18:29:09.472Z |
| Run ID | `358af654-96e5-48d4-8557-ff6f9efc9e56` |

**Prompt:**

> In quantum mechanics, what does the Heisenberg uncertainty principle state?

**Emma's Answer:**
```
The Heisenberg Uncertainty Principle states that it is impossible to simultaneously know precisely both the position and momentum of a particle. The more accurately one property is measured, the less accurately the other can be known.
```
**Expected Answer:**
```
You cannot simultaneously know the exact position and momentum of a particle with arbitrary precision
```
**Evaluator Reasoning:** 7/13 keywords (54%)
**Failure case:** None â€” full credit

#### 13. [MMLU â€¢ Difficulty 1] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `ca36ad52-ad54-4f84-9c46-f4bb663d719c` |
| Category | mmlu |
| Difficulty | 1 |
| Score | 10 / 10 |
| Scoring rule | `keyword-coverage>=0.5` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048}` |
| Latency | 1227 ms |
| Timestamp | 2026-06-14T18:29:09.472Z |
| Run ID | `358af654-96e5-48d4-8557-ff6f9efc9e56` |

**Prompt:**

> What is the difference between TCP and UDP?

**Emma's Answer:**
```
TCP (Transmission Control Protocol) is a connection-oriented protocol that provides reliable, ordered, and error-checked delivery of a stream of bytes between applications. UDP (User Datagram Protocol) is a connectionless protocol that provides a best-effort, unreliable, and unordered delivery of datagrams.
```
**Expected Answer:**
```
TCP is connection-oriented with guaranteed delivery and ordering; UDP is connectionless with no delivery guarantee but lower latency
```
**Evaluator Reasoning:** 7/14 keywords (50%)
**Failure case:** None â€” full credit

#### 14. [MMLU â€¢ Difficulty 2] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `d664b541-cffe-4c7d-bf1d-682764feadb2` |
| Category | mmlu |
| Difficulty | 2 |
| Score | 10 / 10 |
| Scoring rule | `keyword-coverage>=0.5` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048}` |
| Latency | 1607 ms |
| Timestamp | 2026-06-14T18:29:09.472Z |
| Run ID | `358af654-96e5-48d4-8557-ff6f9efc9e56` |

**Prompt:**

> Explain the CAP theorem in distributed systems.

**Emma's Answer:**
```
The CAP theorem states that a distributed data store cannot simultaneously guarantee **Consistency**, **Availability**, and **Partition tolerance**. It must choose two of the three.

*   **Consistency:** Every read receives the most recent write or an error.
*   **Availability:** Every request receives a (non-error) response, without guarantee that it contains the most recent write.
*   **Partition tolerance:** The system continues to operate despite arbitrary message loss or failure of parts of the system.
```
**Expected Answer:**
```
A distributed system can only guarantee two of three: Consistency, Availability, and Partition tolerance
```
**Evaluator Reasoning:** 10/12 keywords (83%)
**Failure case:** None â€” full credit

#### 15. [MMLU â€¢ Difficulty 1] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `e228eb1c-c3e6-4741-ae1a-12af3775cb5b` |
| Category | mmlu |
| Difficulty | 1 |
| Score | 10 / 10 |
| Scoring rule | `keyword-coverage>=0.5` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048}` |
| Latency | 1438 ms |
| Timestamp | 2026-06-14T18:29:09.473Z |
| Run ID | `358af654-96e5-48d4-8557-ff6f9efc9e56` |

**Prompt:**

> What is the difference between supervised and unsupervised learning?

**Emma's Answer:**
```
Supervised learning uses labeled datasets to train models, while unsupervised learning works with unlabeled data to find hidden patterns or structures.
```
**Expected Answer:**
```
Supervised learning uses labeled training data; unsupervised learning finds patterns in unlabeled data
```
**Evaluator Reasoning:** 8/10 keywords (80%)
**Failure case:** None â€” full credit

#### 16. [REASONING â€¢ Difficulty 1] â€” 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `87ff77a6-3610-4bc3-ac2f-ce8967a0380e` |
| Category | reasoning |
| Difficulty | 1 |
| Score | 10 / 10 |
| Scoring rule | `substring-match` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/ge
