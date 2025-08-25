---
type: Handout
status: new
source: "[[docs/03 - Resources/GitHub/Luis85/Obsidian-Plugin-Development-Starter-Kit/Pull Request - 19|Pull Request - 19]]"
---

# 🧭 Handout: Working with Issues & Pull Requests

*Project Publishing Process (GitHub + Obsidian)*


## 📘 Tutorial (Learning by Doing)

**Goal:** Create the first "Proof of Concept" PR and deliver a README.

1. **Document the Problem Space**

   * Create a new GitHub repo
   * Create Issues for the main domains or problems you want to explore.
   * Each Issue = one problem. Add any research or discovery notes.

2. **Create the Proof of Concept PR**

   * Create a new branch: `proof-of-concept`.
   * Open a Pull Request titled "Proof of Concept".
   * Use the PR template to describe: problem, insight, opportunity, solution idea.
   * Link the Issues you just created.

3. **Add the First Deliverable (README)**

   * Write the initial README in Obsidian or your IDE.
   * Explain what the project is about, why it exists, and its goals.
   * Commit your README to the branch, referencing the Issue or PR ID in the commit message.

4. **Refine & Collaborate**

   * Keep the PR in draft.
   * During refinement sessions, add Deliverables (User Stories, Design Docs, Journeys) as Markdown files.
   * Push updates regularly and discuss changes in the PR thread.

5. **Review & Merge**

   * Once the team agrees, request review.
   * Incorporate feedback until the PR is approved.
   * Merge the Proof of Concept PR → the repo now has a README and a traceable process.

---

## 🛠️ How-To Guide (Practical Recipes)

* **Create a new Issue:**

  * Use for problems, questions, or domains to explore.
  * Add discovery work (notes, insights).

* **Start a new PR:**

  * Always link it to one or more Issues.
  * Use the PR template to scope the solution.
  * Push deliverables and commits referencing the Issue/PR ID.

* **Add Deliverables:**

  * Write Markdown docs (README, Use Cases, Journeys).
  * Include design artifacts if relevant.
  * Treat them as part of the solution, not separate work.

* **Refine Together:**

  * Use the PR thread for discussion.
  * Break down large PRs into smaller ones if needed.

* **Review & Merge:**

  * Request feedback early.
  * PR is the unit of work → only merge when the increment is ready.

---

## 🧩 Explanation (Concepts & Mental Model)

* **Issues = Problem Space (Discovery)**

  * Capture problems, ideas, domains.
  * Document research and insights.

* **PRs = Solution Space (Delivery)**

  * Propose, refine, and deliver solutions.
  * PRs hold user stories, deliverables, designs, and implementation.

* **Repo = Implemented Solution**

  * The repository shows the current state of the product.
  * Deliverables (code + docs) live side by side.

💡 **Think of PRs as release packages.**
They start broad (draft scope), get refined (requirements + design), and end merged (product increment).

---

## 📑 Reference (Quick Look)

**Basic Flow**

1. Idea → GitHub Issue
2. Issue → Draft PR
3. Draft PR → Deliverables (README, User Stories, Docs, Code)
4. PR → Review & Merge → Product Increment

**First Deliverable in every project:** `README.md`

**Commit Messages:** Always reference Issue/PR IDs (e.g., `#12 Add initial repo structure`).

**Branch Naming:** Use context + issue ref (e.g., `feature/#12-readme`).
