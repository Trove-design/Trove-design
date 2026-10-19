# Hi there, I'm Akbar Gheirat 👋

I am an AI enthusiast, tech explorer, and lateral thinker. I am deeply passionate about analyzing complex software architectures, debugging deep-seated infrastructure bottlenecks, and making open-source ecosystems more robust.

---

## 🚀 Focus & Tech Stack

*   **Core Areas:** AI Agent Systems (LLM Frameworks), System Analysis, Performance Debugging & Cache Optimization
*   **Languages & Tools:** TypeScript, Node.js, Bash, Git, DeepSeek API & LLM Infrastructures

---

## 🏆 Open-Source Contributions & Core Audits

While my personal projects are currently hosted in private repositories, I actively demonstrate my engineering and analytical skills through core contributions to major tech frameworks:

### 🔹 DeepSeek Harness (Core Architecture Hub)
I conducted a detailed architectural analysis regarding dynamic tool registration. I successfully identified a critical session-isolation vulnerability that caused massive context-cache degradation (Prefix-Cache Invalidation) across DeepSeek models.

*   **The Issue:** Dynamic plugins incorrectly mounted tools under the process-root global scope instead of the local agent scope. This led to widespread cache-misses and significant token inflation in parallel sessions sharing the same API key.
*   **My Contribution:** Audited the root cause, provided a working TypeScript patch to enforce proper scoping isolation via `agent.ctx`, and submitted the corresponding regression specs to secure the fix.
*   👉 **[View the Architecture Discussion & Patch (Issue #963)](https://github.com)**
*   👉 **[Follow-up Core Audit: Prompt Leaks & System-Prompt Listeners (Issue #10348)](https://github.com)**

---

## 💼 Career Goal
I am currently looking for an entry-level opportunity within an innovative tech team where I can leverage my strong analytical mindset, structured debugging approach, and passion for AI infrastructure.

📫 **Let's connect:** [My LinkedIn Profile](https://linkedin.com)
