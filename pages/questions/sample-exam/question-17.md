# Technical Test Analyst Exam

## [TTA-3.2.3: Using Static Analysis for Improving Maintainability](../../3-static-and-dynamic-analysis/3.3-dynamic-analysis.md#331-overview)

### Question #17 (2 Points) - K3

You are the Technical Test Analyst working on a project developing a new Ambulance Dispatch System (ADS). This ADS assists operators in taking calls about incidents, identifying available ambulances, and mobilizing ambulances to handle the incidents.

You know that the ADS was designed using an object-oriented approach and implemented using a language with automated garbage collection. During system and acceptance testing the system has been perceived to be generally performing correctly, but also rather slowly, and it has also occasionally ‘crashed’; the subsequent (brief) investigations were inconclusive.

**Which of the following statements would BEST justify the use of dynamic analysis in this situation?**

    a. Dynamic analysis could be used to measure response times on user actions to identify efficiency bottlenecks
    b. Dynamic analysis could be used to generate control flow graphs of the system to allow targeted performance enhancement
    c. Dynamic analysis could identify memory access violations caused by a wild pointer that result in the occasional ‘crashes’
    d. Dynamic analysis could be used to determine if programmers introduced defects by not properly releasing allocated memory

**Select ONE option.**

---

<details>
<summary><strong>Show Answer</strong></summary>

#### Correct Answer: c

    a. Is not correct. Dynamic analysis is not typically used for measuring response times (it requires instrumentation and so makes response time measurement impractical). Response times on user actions also cannot identify bottlenecks in the system. Dynamic analysis instead provides lower-level performance metrics to be used for performance tuning
    b. Is not correct. Control flow graphs are generated by static analysis
    c. Is correct. Dynamic analysis can identify memory access violations caused by a wild pointer and these could be causing the ‘occasional’ crashes
    d. Is not correct. The scenario tells us that automated garbage collection was used, so it is unlikely programmers will need to release memory

</details>

---

[↑ Table of Contents](../../README.md#table-of-contents) | [← Previous Page](question-16.md) | [Next Page →](question-18.md)