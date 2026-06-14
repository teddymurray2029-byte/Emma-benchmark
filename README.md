# Emma Intelligence — Benchmark Report
_Generated 6/14/2026, 11:54:06 AM • Categories evaluated: Reasoning, Coding, Planning, MMLU_

## Current Run
- **Overall Intelligence Score:** 100 / 100
- **Change vs previous run:** undefined points
- **Verdict:** Excellent — production-ready reasoning quality.

### Category Scores
| Category | Score | Interpretation |
| --- | --- | --- |
| Reasoning | 100 / 100 | Excellent — production-ready reasoning quality. |
| Coding | 100 / 100 | Excellent — production-ready reasoning quality. |
| Planning | 100 / 100 | Excellent — production-ready reasoning quality. |
| Mmlu | 100 / 100 | Excellent — production-ready reasoning quality. |

### Detailed Question Results (115)
#### 1. [REASONING • Difficulty 1] — 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `12e1dc8f-4cd3-41e9-9abb-327025a0a863` |
| Category | reasoning |
| Difficulty | 1 |
| Score | 10 / 10 |
| Scoring rule | `substring-match` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048,"mode":"perfect:baseline"}` |
| Latency | 734 ms |
| Timestamp | 2026-06-14T18:53:22.709Z |
| Run ID | `2aaa4467-7f41-4c16-98b5-0ca2e97dcbec` |

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
**Failure case:** None — full credit

#### 2. [REASONING • Difficulty 2] — 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `ed8c0960-b42a-472c-af2b-bf0097c3ffbb` |
| Category | reasoning |
| Difficulty | 2 |
| Score | 10 / 10 |
| Scoring rule | `substring-match` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048,"mode":"perfect:baseline"}` |
| Latency | 733 ms |
| Timestamp | 2026-06-14T18:53:22.710Z |
| Run ID | `2aaa4467-7f41-4c16-98b5-0ca2e97dcbec` |

**Prompt:**

> If it takes 5 machines 5 minutes to make 5 widgets, how long would it take 100 machines to make 100 widgets?

**Emma's Answer:**
```
5 minutes.
```
**Expected Answer:**
```
5 minutes
```
**Evaluator Reasoning:** Normalized answer contains (or is contained in) expected answer
**Failure case:** None — full credit

#### 3. [REASONING • Difficulty 2] — 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `fdb289b9-4c8f-4ac7-bcaa-697cb53e61d6` |
| Category | reasoning |
| Difficulty | 2 |
| Score | 10 / 10 |
| Scoring rule | `substring-match` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048,"mode":"perfect:baseline"}` |
| Latency | 711 ms |
| Timestamp | 2026-06-14T18:53:22.710Z |
| Run ID | `2aaa4467-7f41-4c16-98b5-0ca2e97dcbec` |

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
**Failure case:** None — full credit

#### 4. [REASONING • Difficulty 1] — 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `ef7556c7-7df6-4662-84d7-4ac66384e932` |
| Category | reasoning |
| Difficulty | 1 |
| Score | 10 / 10 |
| Scoring rule | `substring-match` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048,"mode":"perfect:baseline"}` |
| Latency | 686 ms |
| Timestamp | 2026-06-14T18:53:22.710Z |
| Run ID | `2aaa4467-7f41-4c16-98b5-0ca2e97dcbec` |

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
**Failure case:** None — full credit

#### 5. [REASONING • Difficulty 3] — 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `1017c391-be51-40ed-93e1-e866b7b74af0` |
| Category | reasoning |
| Difficulty | 3 |
| Score | 10 / 10 |
| Scoring rule | `keyword-coverage>=0.5` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048,"mode":"perfect:baseline"}` |
| Latency | 1432 ms |
| Timestamp | 2026-06-14T18:53:22.710Z |
| Run ID | `2aaa4467-7f41-4c16-98b5-0ca2e97dcbec` |

**Prompt:**

> You have a 3-gallon jug and a 5-gallon jug. How do you measure exactly 4 gallons of water?

**Emma's Answer:**
```
1. Fill the 5-gallon jug.
2. Pour the water from the 5-gallon jug into the 3-gallon jug, leaving 2 gallons in the 5-gallon jug.
3. Empty the 3-gallon jug.
4. Pour the 2 gallons from the 5-gallon jug into the 3-gallon jug.
5. Fill the 5-gallon jug.
6. Carefully pour water from the 5-gallon jug into the 3-gallon jug (which already contains 2 gallons) until the 3-gallon jug is full. This will use 1 gallon from the 5-gallon jug.
7. You will be left with exactly 4 gallons in the 5-gallon jug.
```
**Expected Answer:**
```
Fill 5-gallon jug, pour into 3-gallon jug until full (leaving 2 gallons in 5-gallon), empty 3-gallon, pour 2 gallons from 5-gallon into 3-gallon, fill 5-gallon again, pour into 3-gallon until full (1 gallon poured), leaving 4 gallons in the 5-gallon jug.
```
**Evaluator Reasoning:** 12/14 keywords (86%)
**Failure case:** None — full credit

#### 6. [CODING • Difficulty 1] — 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `66f3eca1-836f-45f3-9a85-daf08ab23572` |
| Category | coding |
| Difficulty | 1 |
| Score | 10 / 10 |
| Scoring rule | `substring-match` |
| Model | `google/gemini-2.5-pro` |
| Config | `{"model":"google/gemini-2.5-pro","prompt_version":1,"max_tokens":2048,"mode":"perfect:round-1"}` |
| Latency | 7097 ms |
| Timestamp | 2026-06-14T18:53:25.907Z |
| Run ID | `2aaa4467-7f41-4c16-98b5-0ca2e97dcbec` |

**Prompt:**

> Write a function that checks if a string is a palindrome. Return true or false.

**Emma's Answer:**
```
```javascript
// Cleans the string by removing non-alphanumeric characters and converting to lowercase, then compares it to its reversed version.
// Time Complexity: O(n)
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
**Evaluator Reasoning:** Normalized answer contains (or is contained in) expected answer
**Failure case:** None — full credit

#### 7. [CODING • Difficulty 3] — 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `3559b66f-5e01-40af-914d-d46304ca1ccb` |
| Category | coding |
| Difficulty | 3 |
| Score | 10 / 10 |
| Scoring rule | `code-pattern-lcs` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048,"mode":"perfect:baseline"}` |
| Latency | 3123 ms |
| Timestamp | 2026-06-14T18:53:22.711Z |
| Run ID | `2aaa4467-7f41-4c16-98b5-0ca2e97dcbec` |

**Prompt:**

> Implement a function that finds the longest common subsequence of two strings.

**Emma's Answer:**
```
The longest common subsequence (LCS) of two strings is the longest sequence of characters that appear in the same order in both strings, but not necessarily contiguously.

```javascript
// Dynamic programming with O(mn) time complexity
const longestCommonSubsequence = (text1, text2) => {
  const m = text1.length;
  const n = text2.length;

  // dp[i][j] will store the length of the LCS of text1[0...i-1] and text2[0...j-1]
  const dp = Array(m + 1).fill(null).map(() => Array(n + 1).fill(0));

  for (let i = 1; i <= m; i++) {
    for (let j = 1; j <= n; j++) {
      if (text1[i - 1] === text2[j - 1]) {
        dp[i][j] = 1 + dp[i - 1][j - 1];
      } else {
        dp[i][j] = Math.max(dp[i - 1][j], dp[i][j - 1]);
      }
    }
  }

  // Reconstruct the LCS string
  let index = dp[m][n];
  let lcs = new Array(index);
  let i = m;
  let j = n;

  while (i > 0 && j > 0) {
    if (text1[i - 1] === text2[j - 1]) {
      lcs[index - 1] = text1[i - 1];
      i--;
      j--;
      index--;
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
**Failure case:** None — full credit

#### 8. [CODING • Difficulty 2] — 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `da37aa93-5b36-405a-830a-3689a7ae83ab` |
| Category | coding |
| Difficulty | 2 |
| Score | 10 / 10 |
| Scoring rule | `keyword-coverage>=0.5` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048,"mode":"perfect:baseline"}` |
| Latency | 1409 ms |
| Timestamp | 2026-06-14T18:53:22.711Z |
| Run ID | `2aaa4467-7f41-4c16-98b5-0ca2e97dcbec` |

**Prompt:**

> Write a function that flattens a deeply nested array. Example: [1,[2,[3,[4]]]] → [1,2,3,4]

**Emma's Answer:**
```
```javascript
// Recursion, O(N) time complexity where N is the total number of elements across all nested arrays.
function flattenArray(arr) {
  const flattened = [];

  for (let i = 0; i < arr.length; i++) {
    if (Array.isArray(arr[i])) {
      flattened.push(...flattenArray(arr[i]));
    } else {
      flattened.push(arr[i]);
    }
  }

  return flattened;
}
```
```
**Expected Answer:**
```
function flatten(arr) { return arr.reduce((acc, val) => Array.isArray(val) ? acc.concat(flatten(val)) : acc.concat(val), []); }
```
**Evaluator Reasoning:** 5/10 keywords (50%)
**Failure case:** None — full credit

#### 9. [PLANNING • Difficulty 2] — 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `e94fdfbb-ff42-4a00-8093-83a47648c975` |
| Category | planning |
| Difficulty | 2 |
| Score | 10 / 10 |
| Scoring rule | `keyword-coverage>=0.5` |
| Model | `google/gemini-2.5-pro` |
| Config | `{"model":"google/gemini-2.5-pro","prompt_version":1,"max_tokens":2048,"mode":"perfect:round-1"}` |
| Latency | 16211 ms |
| Timestamp | 2026-06-14T18:53:25.908Z |
| Run ID | `2aaa4467-7f41-4c16-98b5-0ca2e97dcbec` |

**Prompt:**

> You need to organize a software project with 5 developers over 3 months. The project has frontend, backend, and database components. Create a high-level plan.

**Emma's Answer:**
```
**1. Task Decomposition & Resource Allocation**
*   **Components:** The project is decomposed into three main workstreams: Frontend, Backend, and Database.
*   **Team Allocation:**
    *   2 developers on Frontend (UI/UX implementation).
    *   2 developers on Backend (API and business logic).
    *   1 developer on Database (schema design, optimization) and DevOps.

**2. Dependency Mapping**
*   The primary dependency is the API contract between the frontend and backend.
*   The backend is dependent on the database schema.
*   Frontend development can proceed in parallel with backend development by using mock API servers once the contract is defined.

**3. Milestones & Timeline**

*   **Month 1: Planning & Foundation**
    *   **Tasks:** Define detailed requirements, design system architecture, create UI/UX wireframes, and establish the database schema and API contract. Set up development environments and CI/CD pipelines.
    *   **Milestone:** Architectural designs, schemas, and API contracts are finalized and signed off.

*   **Month 2: Core Development & Integration**
    *   **Tasks:** Parallel development of frontend components and backend services based on defined contracts. Implement core business logic and user authentication. Begin integration.
    *   **Milestone:** An integrated Alpha version with core features is demonstrable.

*   **Month 3: Testing, Refinement, & Deployment**
    *   **Tasks:** Conduct end-to-end testing, bug fixing, performance optimization, and security hardening. Prepare deployment scripts and documentation.
    *   **Milestone:** A stable, production-ready application is deployed.

**4. Risk Assessment**
*   **Risk:** API contract changes cause rework.
    *   **Mitigation:** Finalize and freeze the API contract at the end of Month 1.
*   **Risk:** A component delay blocks progress for other teams.
    *   **Mitigation:** Use mock servers and interfaces to enable parallel work.
*   **Risk:** Integration issues discovered late in 
```
**Expected Answer:**
```
Should include: task decomposition, dependency mapping, milestone definition, resource allocation, risk assessment
```
**Evaluator Reasoning:** 9/12 keywords (75%)
**Failure case:** None — full credit

#### 10. [PLANNING • Difficulty 3] — 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `142fdb34-3ae6-44dc-b0c1-1e611a00844f` |
| Category | planning |
| Difficulty | 3 |
| Score | 10 / 10 |
| Scoring rule | `keyword-coverage>=0.5` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048,"mode":"perfect:baseline"}` |
| Latency | 3191 ms |
| Timestamp | 2026-06-14T18:53:22.712Z |
| Run ID | `2aaa4467-7f41-4c16-98b5-0ca2e97dcbec` |

**Prompt:**

> Design a system to handle 10 million concurrent users for a chat application. What are the key architectural decisions?

**Emma's Answer:**
```
Key architectural decisions for a chat application with 10 million concurrent users include:

1.  **Distributed System Architecture:** Microservices or event-driven architecture for scalability and fault isolation.
2.  **Real-time Communication:** WebSockets for persistent, low-latency communication.
3.  **Scalable Data Stores:**
    *   **NoSQL Databases:** For message storage (e.g., Cassandra, MongoDB) due to schema flexibility and horizontal scalability.
    *   **Redis:** For caching, presence (online/offline status), and temporary message queues.
4.  **Message Queues/Brokers:** Kafka or RabbitMQ for reliable, asynchronous message delivery, decoupling services, and handling high throughput.
5.  **Load Balancing & Proxying:** Layer 4/7 load balancers (e.g., Nginx, HAProxy) and API Gateway for distributing requests and routing.
6.  **Service Discovery:** Kubernetes or Consul for managing and locating services.
7.  **Containerization & Orchestration:** Docker and Kubernetes for deployment, scaling, and management.
8.  **Cloud-Native Design:** Leveraging cloud services for elasticity, managed databases, and global distribution.
9.  **Presence System:** Dedicated service using Redis Pub/Sub for managing user online/offline status efficiently.
10. **Notification System:** Push notification services (e.g., FCM, APNs) and in-app notifications.
11. **Stateless Services:** Design most services to be stateless to facilitate easy scaling.
12. **Content Delivery Network (CDN):** For delivering static assets and media files.
```
**Expected Answer:**
```
Should cover: horizontal scaling, message queues, WebSocket management, database sharding, caching layers, CDN, load balancing
```
**Evaluator Reasoning:** 9/15 keywords (60%)
**Failure case:** None — full credit

#### 11. [MMLU • Difficulty 1] — 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `f77d890a-ba4d-4f59-829d-c2292ea0d8e6` |
| Category | mmlu |
| Difficulty | 1 |
| Score | 10 / 10 |
| Scoring rule | `substring-match` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048,"mode":"perfect:baseline"}` |
| Latency | 1182 ms |
| Timestamp | 2026-06-14T18:53:22.712Z |
| Run ID | `2aaa4467-7f41-4c16-98b5-0ca2e97dcbec` |

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
**Failure case:** None — full credit

#### 12. [MMLU • Difficulty 2] — 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `a85a261a-ffdc-4bb6-ac1b-33110185c6bd` |
| Category | mmlu |
| Difficulty | 2 |
| Score | 10 / 10 |
| Scoring rule | `keyword-coverage>=0.5` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048,"mode":"perfect:baseline"}` |
| Latency | 1221 ms |
| Timestamp | 2026-06-14T18:53:22.712Z |
| Run ID | `2aaa4467-7f41-4c16-98b5-0ca2e97dcbec` |

**Prompt:**

> In quantum mechanics, what does the Heisenberg uncertainty principle state?

**Emma's Answer:**
```
The Heisenberg Uncertainty Principle states that it is impossible to simultaneously know with perfect precision both the position and momentum of a particle.
```
**Expected Answer:**
```
You cannot simultaneously know the exact position and momentum of a particle with arbitrary precision
```
**Evaluator Reasoning:** 9/13 keywords (69%)
**Failure case:** None — full credit

#### 13. [MMLU • Difficulty 1] — 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `ca36ad52-ad54-4f84-9c46-f4bb663d719c` |
| Category | mmlu |
| Difficulty | 1 |
| Score | 10 / 10 |
| Scoring rule | `keyword-coverage>=0.5` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048,"mode":"perfect:baseline"}` |
| Latency | 1630 ms |
| Timestamp | 2026-06-14T18:53:22.712Z |
| Run ID | `2aaa4467-7f41-4c16-98b5-0ca2e97dcbec` |

**Prompt:**

> What is the difference between TCP and UDP?

**Emma's Answer:**
```
TCP (Transmission Control Protocol) is connection-oriented, providing reliable, ordered, and error-checked delivery of data. UDP (User Datagram Protocol) is connectionless, offering faster, but unreliable, unordered data transmission without error checking.
```
**Expected Answer:**
```
TCP is connection-oriented with guaranteed delivery and ordering; UDP is connectionless with no delivery guarantee but lower latency
```
**Evaluator Reasoning:** 8/14 keywords (57%)
**Failure case:** None — full credit

#### 14. [MMLU • Difficulty 2] — 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `d664b541-cffe-4c7d-bf1d-682764feadb2` |
| Category | mmlu |
| Difficulty | 2 |
| Score | 10 / 10 |
| Scoring rule | `keyword-coverage>=0.5` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048,"mode":"perfect:baseline"}` |
| Latency | 2275 ms |
| Timestamp | 2026-06-14T18:53:22.712Z |
| Run ID | `2aaa4467-7f41-4c16-98b5-0ca2e97dcbec` |

**Prompt:**

> Explain the CAP theorem in distributed systems.

**Emma's Answer:**
```
The CAP theorem states that a distributed data store can only simultaneously guarantee two out of three properties:

*   **Consistency:** All clients see the same data at the same time.
*   **Availability:** Every request receives a response, without guarantee that it contains the most recent version of the information.
*   **Partition tolerance:** The system continues to operate despite arbitrary message loss or failure of parts of the system.

In practice, network partitions are inevitable, so a choice must be made between consistency and availability.
```
**Expected Answer:**
```
A distributed system can only guarantee two of three: Consistency, Availability, and Partition tolerance
```
**Evaluator Reasoning:** 12/12 keywords (100%)
**Failure case:** None — full credit

#### 15. [MMLU • Difficulty 1] — 10/10

| Metric | Value |
| --- | --- |
| Prompt ID | `e228eb1c-c3e6-4741-ae1a-12af3775cb5b` |
| Category | mmlu |
| Difficulty | 1 |
| Score | 10 / 10 |
| Scoring rule | `keyword-coverage>=0.5` |
| Model | `google/gemini-2.5-flash` |
| Config | `{"model":"google/gemini-2.5-flash","prompt_version":1,"max_tokens":2048,"mode":"perfect:baseline"}` |
| Latency | 963 ms |
| Timest
