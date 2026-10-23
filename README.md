# Case Study 1: Danny's Diner

My analysis of the first case study in Danny Ma's 8 Week SQL Challenge.

> This is an independent learning project. The original case study and dataset are available on the [official case study page](https://8weeksqlchallenge.com/case-study-1/).

## Contents

- [Business task](#business-task)
- [Dataset and relationships](#dataset-and-relationships)
- [Questions and solutions](#questions-and-solutions)
- [Key findings](#key-findings)
- [What I learned](#what-i-learned)
- [Credits](#credits)

## Business task

In my own words, what does the business want to understand from its customer, sales, menu, and membership data?

## Dataset and relationships

Add an ER diagram showing how the `sales`, `menu`, and `members` tables connect.

| Table | What a row represents | Key columns |
|---|---|---|
| `sales` | A product purchased by a customer on a date | `customer_id`, `order_date`, `product_id` |
| `menu` | A menu item and its price | `product_id`, `product_name`, `price` |
| `members` | A customer's membership start date | `customer_id`, `join_date` |

## Questions and solutions

Use the [official case study page](https://8weeksqlchallenge.com/case-study-1/) for the questions and data. For each question, document your own approach and results.

### Question 1 — [Add a short question title]

**Approach:** Which tables, calculations, and assumptions did I use?

**SQL:** See the question's section in [`solutions.sql`](solutions.sql).

**Result:** Add a small result table or summarize the output.

**What it tells me:** Explain the business meaning of the result.

---

### Question 2 — [Add a short question title]

**Approach:** Describe the logic and assumptions.

**SQL:** See the question's section in [`solutions.sql`](solutions.sql).

**Result:** Add the output or a concise summary.

**What it tells me:** Explain what the result means.

---

Repeat this format for the remaining questions and any bonus questions you attempt.

## Key findings

1. **Finding:** Add a result and what it means.
2. **Finding:** Add a result and what it means.
3. **Finding:** Add a result and what it means.

## What I learned

- **SQL concepts practiced:** Add the concepts you used.
- **Most challenging part:** Describe what took the most effort.
- **Next time:** Note what you would improve.

## Credits

- Case study and dataset: [Danny Ma's 8 Week SQL Challenge](https://8weeksqlchallenge.com/case-study-1/)
- Challenge information: [Getting Started](https://8weeksqlchallenge.com/getting-started/)
- SQL dialect used: [e.g., PostgreSQL]

The case study content and dataset belong to their original publisher. This repository contains my own SQL, analysis, and learning notes.
