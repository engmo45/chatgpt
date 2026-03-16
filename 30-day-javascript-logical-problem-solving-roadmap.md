# 30-Day JavaScript Logical Thinking & Problem-Solving Mastery Plan

This roadmap is designed to train how you **think**, not just what you code. It starts with core basics and steadily increases complexity.

## How to Use This Plan Daily

1. Spend 20–30 min on concept review.
2. Solve all daily challenges (without AI first).
3. Build the daily project with pseudocode first.
4. Refactor once for clarity.
5. Write a short reflection:
   - What pattern did I use?
   - Where did I get stuck?
   - How can I simplify my approach?

---

## Best Practices You Must Follow Every Day

- **Understand the problem first**: Input, output, constraints, edge cases.
- **Write pseudocode before coding**.
- **Use meaningful variable/function names**.
- **Keep functions small and single-purpose**.
- **Test edge cases** (empty input, duplicates, negative values, large numbers).
- **Dry run with sample data** before executing code.
- **Optimize only after correctness**.
- **Refactor after passing tests**.
- **Track time/space complexity** for each solution.
- **Use Git commits daily** with clear messages.

---

## Week 1 (Days 1–7): Foundations of Logical Thinking
Focus: variables, conditions, loops, functions, arrays, basic debugging.

### Day 1 — Inputs, Outputs, Conditions
**Challenges**
1. Check if a number is positive, negative, or zero.
2. Find the greater of two numbers.
3. Check if a number is even or odd.
4. Convert Celsius to Fahrenheit.

**Project: Mini Calculator (2 numbers + operation)**
**Pseudocode**
- Read `num1`, `num2`, `operator`.
- If operator is `+`, `-`, `*`, `/`, compute result.
- Handle division by zero.
- Print result or error message.

**Steps**
1. Define input variables.
2. Use `if/else` or `switch` to select operation.
3. Add validation for division by zero.
4. Return/display output.

---

### Day 2 — Loops & Repetition
**Challenges**
1. Print numbers 1 to 100.
2. Sum numbers from 1 to N.
3. Generate multiplication table for a given number.
4. Count digits in a number.

**Project: Number Pattern Generator**
**Pseudocode**
- Read number of rows.
- Loop row from 1 to rows.
- Inside each row, print stars equal to row count.
- Move to next line.

**Steps**
1. Build one loop for rows.
2. Add nested loop for symbols.
3. Store each row in string for cleaner output.
4. Print full pattern.

---

### Day 3 — Functions & Decomposition
**Challenges**
1. Write `isPrime(n)`.
2. Write `factorial(n)`.
3. Write `reverseNumber(n)`.
4. Write `sumOfDigits(n)`.

**Project: Math Utility Toolkit (menu-based)**
**Pseudocode**
- Show menu options.
- Read user choice and input number(s).
- Call matching function.
- Print result.

**Steps**
1. Create separate functions per operation.
2. Add central handler function.
3. Validate invalid menu choice.
4. Test each function independently.

---

### Day 4 — Arrays Basics
**Challenges**
1. Find min and max in array.
2. Calculate array average.
3. Count even/odd numbers in array.
4. Remove duplicates (basic approach).

**Project: Student Marks Analyzer**
**Pseudocode**
- Input array of marks.
- Compute total and average.
- Find highest and lowest marks.
- Count passes/fails using threshold.
- Print summary.

**Steps**
1. Loop once for aggregate values.
2. Update min/max inside loop.
3. Add pass/fail condition.
4. Return object with computed stats.

---

### Day 5 — Strings & Character Logic
**Challenges**
1. Check palindrome string.
2. Count vowels and consonants.
3. Reverse a string.
4. Find frequency of each character.

**Project: Text Inspector Tool**
**Pseudocode**
- Input text.
- Normalize text (lowercase, trim).
- Count words, characters, vowels.
- Build frequency map.
- Output report.

**Steps**
1. Split string for words.
2. Loop over characters for counts.
3. Use object/map for frequency.
4. Print clean formatted summary.

---

### Day 6 — Mixed Practice + Debugging
**Challenges**
1. FizzBuzz.
2. Two-sum (brute force).
3. Find second largest in array.
4. Check anagram (basic sorting approach).

**Project: Error Hunt Playground**
**Pseudocode**
- Prepare buggy functions.
- Run test inputs.
- Log expected vs actual outputs.
- Fix one bug at a time.
- Re-run tests.

**Steps**
1. Create 4 intentionally buggy snippets.
2. Add simple test cases.
3. Use console logs to inspect flow.
4. Refactor fixed code for readability.

---

### Day 7 — Weekly Capstone
**Challenges**
1. Rotate array by K steps.
2. Find common elements of two arrays.
3. Find missing number from range.
4. Convert decimal to binary.

**Project: Command-Line Utility Suite (v1)**
(includes: calculator, text inspector, marks analyzer)

**Pseudocode**
- Show utility menu.
- Route user selection to a module.
- Collect required inputs.
- Execute module logic.
- Display output and return to menu.

**Steps**
1. Build menu controller.
2. Reuse previous days’ functions.
3. Separate code into modules/files.
4. Perform integration test with sample inputs.

---

## Week 2 (Days 8–14): Core Problem-Solving Patterns
Focus: searching, sorting, maps/sets, two pointers, recursion basics.

### Day 8 — Searching
**Challenges**
1. Linear search.
2. Binary search.
3. Find insertion position in sorted array.
4. First and last occurrence of target.

**Project: Search Visual Logger**
**Pseudocode**
- Input sorted array + target.
- Run linear and binary search.
- Log each step index checked.
- Compare steps/time conceptually.

**Steps**
1. Implement both search methods.
2. Add step-counter variable.
3. Output found index + step count.
4. Write short comparison note.

### Day 9 — Sorting Logic
**Challenges**
1. Bubble sort.
2. Selection sort.
3. Insertion sort.
4. Sort objects by property.

**Project: Custom Sort Playground**
**Pseudocode**
- Input array of objects.
- Select key (`age`, `score`, etc.).
- Sort ascending/descending.
- Print before and after.

**Steps**
1. Implement comparator function.
2. Build choice for order direction.
3. Validate missing key case.
4. Run multiple datasets.

### Day 10 — Hash Map / Frequency Pattern
**Challenges**
1. First non-repeating character.
2. Most frequent element.
3. Group words by length.
4. Check if two arrays have same squared values.

**Project: Frequency Analyzer Dashboard (console)**
**Pseudocode**
- Input list of values.
- Create frequency map.
- Identify top frequency and unique values.
- Print structured report.

**Steps**
1. Use object or `Map` for counts.
2. Traverse to find max frequency.
3. Separate repeated vs unique.
4. Format output clearly.

### Day 11 — Two Pointers
**Challenges**
1. Pair sum in sorted array.
2. Remove duplicates in sorted array.
3. Valid palindrome ignoring non-alphanumeric.
4. Container with most water (conceptual start).

**Project: Pair Finder Toolkit**
**Pseudocode**
- Input sorted array + target.
- Use left and right pointers.
- Move pointers based on sum.
- Return matching pair(s).

**Steps**
1. Initialize `left=0`, `right=n-1`.
2. Compare sum to target.
3. Move proper pointer each iteration.
4. Stop when pointers cross.

### Day 12 — Sliding Window Basics
**Challenges**
1. Max sum subarray of size K.
2. Average of every subarray size K.
3. Longest substring without repeating chars (start).
4. Minimum size subarray sum.

**Project: Window Metrics Engine**
**Pseudocode**
- Input array/string and window size.
- Build initial window.
- Slide window one step each loop.
- Update best metric each move.

**Steps**
1. Compute first window result.
2. Add incoming, remove outgoing value.
3. Track max/min/length metric.
4. Return final best value.

### Day 13 — Recursion Basics
**Challenges**
1. Recursive factorial.
2. Fibonacci with recursion + memoization.
3. Recursive sum of array.
4. Countdown recursion.

**Project: Recursion Explorer**
**Pseudocode**
- Define recursive function with base case.
- Log each call level.
- Return combined result from subcalls.
- Compare with iterative version.

**Steps**
1. Write clear base case first.
2. Implement recursive relation.
3. Add indentation logging for depth.
4. Measure call count.

### Day 14 — Weekly Capstone
**Challenges**
1. Valid parentheses.
2. Longest common prefix.
3. Merge two sorted arrays.
4. Product of array except self (basic).

**Project: Pattern-Based Problem Solver (v2)**
**Pseudocode**
- Select problem category.
- Map category to pattern function.
- Execute with sample + custom input.
- Print complexity notes.

**Steps**
1. Build function registry by pattern.
2. Add challenge runner.
3. Attach complexity annotation.
4. Refactor into reusable modules.

---

## Week 3 (Days 15–21): Intermediate Logic & Real Projects
Focus: objects, stack/queue, deeper array/string problems, clean architecture.

### Day 15 — Objects & Data Modeling
**Challenges**
1. Merge two objects deeply (basic).
2. Find duplicate values in object array.
3. Convert array to object by key.
4. Validate required fields.

**Project: Inventory Manager**
**Pseudocode**
- Store products as object array.
- Add/update/remove product.
- Search by name/category.
- Compute stock valuation.

**Steps**
1. Define product schema.
2. Write CRUD functions.
3. Add validation for bad data.
4. Generate summary report.

### Day 16 — Stack & Queue Thinking
**Challenges**
1. Implement stack with array.
2. Implement queue with array.
3. Balanced brackets using stack.
4. Reverse string using stack.

**Project: Browser History Simulator**
**Pseudocode**
- Use two stacks: back, forward.
- On new visit: push current to back, clear forward.
- On back: move current to forward, pop from back.
- On forward: reverse operation.

**Steps**
1. Define current page state.
2. Build `visit`, `back`, `forward` methods.
3. Handle empty stack edge cases.
4. Print navigation state after actions.

### Day 17 — Advanced String Problems
**Challenges**
1. Longest substring without repeating chars.
2. Longest palindrome substring (center expansion).
3. String compression.
4. Check rotation of strings.

**Project: String Intelligence Toolkit**
**Pseudocode**
- Input string + selected operation.
- Apply corresponding string algorithm.
- Return result and index/length metadata.

**Steps**
1. Implement each algorithm separately.
2. Build dispatcher function.
3. Validate empty string input.
4. Add benchmark for longer strings.

### Day 18 — Intermediate Arrays
**Challenges**
1. Kadane’s algorithm.
2. Merge intervals.
3. Spiral matrix traversal.
4. Three-sum (intro).

**Project: Array Analytics Engine**
**Pseudocode**
- Input array + operation.
- Run selected algorithm.
- Return both result and explanation trace.

**Steps**
1. Implement operations with clear helpers.
2. Keep immutable operations when possible.
3. Add trace logs for debugging.
4. Compare brute-force vs optimized for one task.

### Day 19 — Error Handling & Defensive Coding
**Challenges**
1. Validate numeric input parser.
2. Build safe divide function.
3. Guard against null/undefined in object access.
4. Retry helper for unstable async call (mock).

**Project: Robust Input Processor**
**Pseudocode**
- Read mixed raw input.
- Validate each field type/range.
- Collect errors and valid entries.
- Output clean data + error list.

**Steps**
1. Create validator functions.
2. Chain validation per field.
3. Return structured error objects.
4. Add tests for invalid cases.

### Day 20 — Testing Mindset
**Challenges**
1. Write tests for palindrome function.
2. Write tests for two-sum.
3. Add edge tests for empty arrays.
4. Test invalid inputs.

**Project: Mini Test Harness (without framework)**
**Pseudocode**
- Define test cases list.
- For each case, run function and compare expected.
- Track pass/fail counts.
- Print summary.

**Steps**
1. Implement `assertEqual` helper.
2. Add grouped test suites.
3. Print detailed mismatch logs.
4. Use harness on previous projects.

### Day 21 — Weekly Capstone
**Challenges**
1. Top K frequent elements.
2. Subarray sum equals K.
3. Decode basic encoded string.
4. Daily temperatures (stack).

**Project: DSA Challenge Runner CLI (v3)**
**Pseudocode**
- Load challenge bank.
- Let user pick challenge.
- Execute solver + tests.
- Show result, complexity, and hints.

**Steps**
1. Structure challenges as config objects.
2. Attach solver/test functions.
3. Build score tracking.
4. Save progress to JSON file.

---

## Week 4 (Days 22–30): Advanced Problem Solving & Portfolio Projects
Focus: end-to-end thinking, optimization, async logic, architecture, interview-level habits.

### Day 22 — Complexity & Optimization
**Challenges**
1. Improve O(n²) duplicate check to O(n).
2. Compare recursive vs iterative Fibonacci.
3. Analyze complexity of 5 past solutions.
4. Optimize string frequency count.

**Project: Complexity Analyzer Notes Generator**
**Pseudocode**
- Input function descriptions.
- For each, note loops/recursion/map usage.
- Estimate time and space complexity.
- Output structured markdown report.

**Steps**
1. Define complexity rubric.
2. Parse metadata from solution objects.
3. Generate table output.
4. Review and correct estimations.

### Day 23 — Async Logic (Promises / async-await)
**Challenges**
1. Chain promises.
2. Parallel requests with `Promise.all`.
3. Handle rejection safely.
4. Build delay utility.

**Project: Async Task Orchestrator**
**Pseudocode**
- Define async tasks list.
- Run tasks sequentially and in parallel modes.
- Capture success/failure per task.
- Print final report.

**Steps**
1. Mock async tasks with timeouts.
2. Implement sequential runner.
3. Implement parallel runner.
4. Add retry option for failed tasks.

### Day 24 — State & Workflow Thinking
**Challenges**
1. Build finite-state machine for traffic light.
2. Track order status transitions.
3. Validate allowed transitions.
4. Prevent invalid state mutation.

**Project: Task Workflow Manager**
**Pseudocode**
- Define states and transitions.
- Input action.
- Verify transition allowed.
- Update state and log history.

**Steps**
1. Create transition map.
2. Implement transition guard.
3. Persist action history.
4. Display current state dashboard.

### Day 25 — File/Data Processing
**Challenges**
1. Parse JSON safely.
2. Aggregate totals from transaction list.
3. Filter records by date/category.
4. Detect malformed entries.

**Project: Expense Insights Processor**
**Pseudocode**
- Load transactions.
- Validate entries.
- Group by category.
- Compute totals and monthly trends.
- Output summary report.

**Steps**
1. Build parser/validator pipeline.
2. Group using map/object.
3. Calculate aggregates.
4. Export report to JSON/Markdown.

### Day 26 — Architecture & Reusability
**Challenges**
1. Refactor duplicated logic into helpers.
2. Convert long function into modules.
3. Add config-driven behavior.
4. Introduce dependency injection basics.

**Project: Utility Library Refactor**
**Pseudocode**
- Audit previous codebase.
- Extract reusable utilities.
- Group by domain (array, string, math).
- Add docs and tests.

**Steps**
1. Identify duplicate blocks.
2. Create module folders/files.
3. Update imports and references.
4. Add examples in README.

### Day 27 — Interview-Style Timed Drills
**Challenges**
1. 45-minute medium array problem.
2. 45-minute string/map problem.
3. 30-minute stack/queue problem.
4. 30-minute debugging challenge.

**Project: Mock Interview Simulator**
**Pseudocode**
- Prepare timed prompt list.
- Start timer per prompt.
- Capture solution + notes.
- Score by correctness, clarity, complexity.

**Steps**
1. Build prompt database.
2. Add timer utility.
3. Add scoring rubric.
4. Generate end-session feedback.

### Day 28 — Capstone Planning Day
**Challenges**
1. Write requirements for final project.
2. Break project into milestones.
3. Define data structures needed.
4. Identify risk/edge cases.

**Project: Final Capstone Design Doc**
**Pseudocode**
- Choose final project idea.
- Define user stories.
- Map features to functions/modules.
- Plan testing strategy.

**Steps**
1. Draft scope (MVP + stretch goals).
2. Sketch folder architecture.
3. Write implementation timeline.
4. Create acceptance criteria checklist.

### Day 29 — Final Capstone Build
**Challenges**
1. Implement core feature A.
2. Implement core feature B.
3. Add error handling.
4. Add unit tests for key functions.

**Project: Final Capstone (implementation)**
Examples: Algorithm practice CLI, smart habit tracker, or workflow manager.

**Pseudocode**
- Initialize project structure.
- Build core modules.
- Connect modules through controller.
- Run tests and fix defects.

**Steps**
1. Implement MVP first.
2. Add logging and input validation.
3. Add tests for critical paths.
4. Refactor for readability.

### Day 30 — Final Polish + Portfolio Readiness
**Challenges**
1. Optimize one slow algorithm.
2. Improve naming/readability of old code.
3. Add docs for all core functions.
4. Record lessons learned.

**Project: Capstone Polish & Showcase**
**Pseudocode**
- Audit code quality.
- Add README with setup and usage.
- Add complexity notes and examples.
- Package final submission.

**Steps**
1. Run all tests and fixes.
2. Improve documentation and comments.
3. Add sample input/output.
4. Publish repository and summary.

---

## Weekly Review Template (Use every 7 days)

- **What improved in my thinking?**
- **Which pattern is still hard?**
- **What bug type repeats most?**
- **Which solution can I simplify?**
- **What will I focus on next week?**

---

## Extra Best-Practice Checklist for Every Project

- [ ] Problem statement written in your own words
- [ ] Pseudocode completed before coding
- [ ] Inputs validated
- [ ] Edge cases listed and tested
- [ ] Complexity analyzed
- [ ] Refactored for readability
- [ ] Tests added for critical logic
- [ ] README updated with usage

If you follow this plan strictly for 30 days, you’ll build strong programming logic, pattern recognition, debugging confidence, and project execution discipline in JavaScript.
