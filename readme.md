# LLM Co-Creation Prompts
<details>
<summary>🇨🇳 中文说明（点击展开/收起）</summary>

## 项目愿景

本项目不仅仅是在搜集“有效的prompt”，而是期望推动人与LLM之间的协作走向更理性、更高质量、更“理解对方意图”的方向。这是我最近深度关注的课题：**如何让AI作为协作伙伴真正帮我们澄清我们自己都未必明晰的需求，突破人类自身表达、抽象和思考习惯的桎梏**。

### 背后认知与假设

- **Prompt并非万能**：核心价值来自人与模型的共创与反复迭代，而非“写一句prompt 就够了”。
- **关注表达与理解的极限**：用户语言通常是模糊、边界不清晰的，好的 prompt 能暴露用户遗漏的假设、结构固化、思维惯性，从而激发更高阶的创新和本质追问。
- **项目的本质目标**：打造一个支持深度思考、透明协作、需求反刍和案例进化的资源集，服务于个人成长和专业工作流升级。

## 项目结构与模块

1. **项目定位**
    - 明确本库旨在促进 LLM + USER 共创式协作，强调“澄清-质疑-创造-共识”的全过程示范。
2. **共创 Prompt 设计理念**
    - 解释 LLM 既是答题者也是“需求澄清师”，以及如何用 prompt 反向让 AI 质疑你。
3. **打破思维惯性与提问固化**
    - 总结人类提问常见陷阱
    - 展示 AI 如何协助“升级你的问题”
4. **优质 Prompt 范式与示例精讲**
    - 每个范式包括实际例句，适用场景，背后原理，可能的优化方向与反思机会。
5. **协作流程与迭代机制**
    - 明确 USER / AI 各自职责（如谁主提问，谁主假设挑战，如何处理共识冲突）
    - 开放“让 AI 挑战我提问方式”等协作模板
6. **案例与多轮演进对话**
    - 展现 Prompt 迭代的完整过程
    - 把协作历史和思维调整记录下来，让改进有据可循

## 高阶 Prompt 范式总览

每一条都包括：**适用场景 / 范式说明 / 可迭代拓展**。

### 1. 让 AI 主动优化你的问题提法

> “请分析我提问的方式背后可能隐藏的假设，并提出更根本或更具价值的问题替代。”

- **适用场景**：感觉表达不精准，或怀疑自己的目标定义不够高效时。
- **范式说明**：让 AI 变为“假设狙击者”，推动你跳出模式。
- **可拓展**：反复迭代——AI 提新问题 → USER 反馈 → AI 再校正。

---

### 2. 聚焦问题解法思路，不求直接结论

> “我的问题是…，请不要直接回答，而是罗列几种主要分析途径，并解析各自优缺点，帮我取舍方案。”

- **适用场景**：面对结构性复杂问题，有多种路径、权衡点。
- **范式说明**：暴露 AI 的“解题地图”，而非提供唯一答案。
- **可拓展**：添加“推演下游影响”，支持策略升级。

---

### 3. 利用 AI 审视你的盲点与合理性

> “这是我的初步方案xxxx，请以批判性合作者视角，挑出最关键漏洞和隐性风险，并给出改进建议。”

- **适用场景**：需要自查漏洞、规避思维误差。
- **范式说明**：AI 多重角色模拟，扩大反馈视界。
- **可拓展**：不同“角色”连续挑战，实现全方位体检。

---

### 4. 让 AI 猜你的真实目标

> “基于我给的问题，请推测我的真实需求或动机，列举三种合理变体，并说明理由。”

- **适用场景**：自查是否掉进“错位提问”“间接目标”陷阱。
- **范式说明**：用 AI 的类人推理能力，对目标抽象做显性讨论。
- **可拓展**：针对 AI 推断偏差，反向修正规则。

---

### 5. 反转传统问答，AI 主导探究

> “这里有个挑战xxxx。请你以苏格拉底式方法，每次提出一个引导性问题，并根据我的回答继续追问。”

- **适用场景**：头脑风暴/灵感启发/非线性问题解构。
- **范式说明**：促使话题探索螺旋上升，打破用户固有框架。
- **可拓展**：模拟不同风格专家的提问链。

---

### 6. 主动引入不合常识的思路

> “除了常规方法，请尝试提出两种看似不靠谱但有潜力的另类解，并说明适用场景。”

- **适用场景**：创新激发、逆向思维训练。
- **范式说明**：AI 挑战自身“安全输出”倾向，解锁创新空间。
- **可拓展**：定期将“异想天开”选项纳入主流策略考量。

---

### 7. 透明化推理链条与不确定性

> “针对这个问题，请详细写出你的推理每一步，并评估每步信心。遇到难以确定处请标明。”

- **适用场景**：高敏感度/需可追溯性的场合，如科研、复杂决策。
- **范式说明**：AI 显性“思考过程”，便于用户查错和补足信息。
- **可拓展**：AI 暴露信心低点→USER 追加线索→再迭代。
- **补充**：推理模型已经完成了这一步
---

## 8. 引导AI深度思考给用户启发
> “要有深度，有独立思考，给我惊喜(但是回答里别提惊喜)。 在回答问题，做任务之前先想想，我为什么要问你这个问题?背后有没有什么隐藏的原因?因为很多时候可能我交给你一个任务，是在一个更大的上下文中，我已经做了一些假设。你要思考这个假设可能是什么，有没有可能我问的问题本身不是最优的，如果我们突破这个假设，可以问出更正确的问题，从更根本的角度得到启发。 在你回答问题的时候，要先思考一下，你的答案的成功标准是什么。换言之什么样的答案是"好"的。注意，不是说你要回答的问题，而是说你的回答的内容本身要满足什么标准，才算是很好地解决了我的需求。然后针对这些标准构思答案，最好能让我惊喜。 你最终还是要给出一个答案的。但是我们是一个合作的关系。你的目标不是单纯的在一个回合的对话中给出一个确定的答案（这可能会遵着你在一些假设不明的时候随意做出假设），而是跟我合作，一步步找到问题的答案，甚至是问题实际更好的问法。换言之，你的任务不是遵从我的指令，而是给我启发。”

- **适用场景**：激发AI主动探索，符合用户期望，甚至超出用户预期的答案
- **范式说明**：促使话题探索螺旋上升，打破用户固有框架。

---

## 让 AI 成为高速演进的“问题发现器”与思想合伙人

有效的 Prompt，不是让 AI 被动答题，而是让 AI 主动参与问题构建、思维提升、需求进化，并助你不断精进三重能力——把问题问对、问深、问新。本项目致力于在实践中总结出系统化范式和流程，助力你用好 LLM 作为你思想路上的同行者。

---

## demo环境准备

1. **Python 版本**  
   推荐 Python 3.9 及以上

2. **依赖安装**  
   在项目根目录下，运行：
   ```bash
   pip install -r requirements.txt
   ```
   `requirements.txt`内容如下：
   ```
   openai>=1.0.0
   python-dotenv
   ```

3. **配置 OpenAI API Key**  
   在项目根目录下新建一个 `.env` 文件，内容如下（请将 `sk-xxxx` 替换为你自己的 OpenAI API Key）：
   ```
   OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
   ```

## 参考

- OpenAI 官方文档：https://platform.openai.com/docs
- openai-python SDK：https://github.com/openai/openai-python

---

</details>

---

<details open>
<summary>🇺🇸 English Version (Click to expand/collapse)</summary>

# LLM Co-Creation Prompts

## Project Vision

This project is not simply a collection of “effective prompts,” but aims to promote deeper, higher-quality, more intentional co-creation between humans and LLMs. The core pursuit: **How can AI, as an active collaborative partner, help clarify the needs and intentions that we may not even fully recognize ourselves—transcending the limits of human expression, abstraction, and habit?**

### Cognitive Background & Assumptions

- **Prompts Are Not Magic:** The real value lies in iterative, collaborative interplay between human and model—not “just write a good prompt and you’re done.”
- **Focus on the Limits of Expression & Understanding:** Human language tends to be ambiguous and full of blind spots. Quality prompts can reveal hidden assumptions, rigid structures, and habitual patterns in thinking, inspiring deeper innovation and more essential questioning.
- **Fundamental Project Goal:** To build a resource hub supporting deep thinking, transparent collaboration, requirement reflection, and evolving case studies—serving personal growth and professional workflow upgrades.

## Project Structure & Modules

1. **Project Positioning**
    - This repo is designed to boost co-creation between LLM and user, showcasing the entire cycle of “clarification, challenge, creation, consensus.”
2. **Co-Creation Prompt Design Principles**
    - LLM is not only an answer provider, but also a “requirement clarifier.” Learn how to use prompts to have AI challenge you in return.
3. **Breaking Thinking Inertia & Fixed Questioning**
    - Summarize common pitfalls in human questioning.
    - Show how AI can help you “upgrade your questions.”
4. **Excellent Prompt Paradigms & Explanations**
    - Each paradigm includes example prompts, scenarios, underlying principles, potential optimizations, and opportunities for critical reflection.
5. **Collaboration Process & Iteration Mechanisms**
    - Clarify roles for USER and AI (e.g., who leads questioning, who challenges assumptions, how consensus is managed).
    - Provide open collaboration templates such as “let AI critique my questioning method.”
6. **Case Studies & Multi-round Evolving Dialogues**
    - Illustrate the full prompt iteration process.
    - Record collaboration history and mindset adjustments for traceable improvement.

## Overview of Advanced Prompt Paradigms

For each, include: **Applicable Scenario / Paradigm Description / Expandability**.

---

### 1. Have AI Actively Optimize Your Questions

> "Please analyze any hidden assumptions behind my question, and propose more fundamental or valuable alternative questions."

- **Applicable Scenario:** When your own expression feels imprecise or your goal definition seems inefficient.
- **Paradigm Description:** Make the AI a “hypothesis hunter” to break you out of routine patterns.
- **Expandability:** Iterate—AI suggests new questions → USER gives feedback → AI adjusts again.

---

### 2. Focus on Solution Approaches, Not Immediate Answers

> "My question is ... Please do not answer outright. Instead, list out several main analysis paths, discuss pros/cons of each, and help me choose an approach."

- **Applicable Scenario:** Facing complex, multi-pronged problems with trade-offs.
- **Paradigm Description:** Reveal the AI’s “solution map” instead of a single answer.
- **Expandability:** Add “downstream impact simulation,” supporting strategic upgrades.

---

### 3. Use AI to Identify Your Blind Spots & Reasonability

> "Here is my draft plan: xxxx. Please, as a critical partner, identify the key flaws and hidden risks, and suggest improvements."

- **Applicable Scenario:** For self-checking loopholes and avoiding cognitive biases.
- **Paradigm Description:** AI plays multiple roles, broadening the scope of feedback.
- **Expandability:** Allow different “roles” to challenge continuously for a full-spectrum review.

---

### 4. Let AI Guess Your True Goal

> "Based on my question, please infer my true needs or motives, list three plausible variants, and explain your reasoning."

- **Applicable Scenario:** To check if you're falling into “misaligned questioning” or “indirect objective” traps.
- **Paradigm Description:** Leverage AI’s human-like reasoning to explicate the abstraction behind your goal.
- **Expandability:** Allow the user to reverse-correct AI’s mis-inferences with new rules.

---

### 5. Reverse Traditional Q&A: AI Leads the Inquiry

> "Here's a challenge: xxxx. Please use a Socratic approach—ask me one guiding question at a time, and dig deeper based on my answers."

- **Applicable Scenario:** Brainstorming, inspiration, or nonlinear problem deconstruction.
- **Paradigm Description:** Push topic exploration to a higher level, shattering the user's initial framing.
- **Expandability:** Model different expert questioning chains.

---

### 6. Proactively Introduce Unconventional Ideas

> "Besides standard methods, suggest two seemingly crazy but potentially valuable alternative solutions, and describe scenarios where they might work."

- **Applicable Scenario:** Stimulate innovation and practice reverse thinking.
- **Paradigm Description:** Have AI challenge its “safe-answer bias” and unlock more creative ground.
- **Expandability:** Regularly incorporate “wild ideas” into mainstream strategic consideration.

---

### 7. Make Reasoning Chains & Uncertainty Explicit

> "For this problem, outline every reasoning step in detail and assess your confidence at each step. Highlight areas of uncertainty."

- **Applicable Scenario:** High-stakes or traceability-demanding contexts (e.g., research, complex decisions).
- **Paradigm Description:** AI makes its thinking process explicit, letting users spot errors or fill in missing info.
- **Expandability:** AI exposes low-confidence steps → USER gives extra clues → iterate again.
- **Note:** Modern reasoning models have already supported this step.

---

### 8. Inspire User with AI's Deep Deliberation

> "Be deep, think independently, and surprise me (but don’t mention ‘surprise’ in your answer). Before answering or doing the task, reflect on why I’m asking—could there be hidden reasons or context? Consider if my request itself is truly optimal, or if reframing it could reveal a better perspective. As you construct your answer, define what a successful answer should achieve (not just ‘answer my question,’ but really address my underlying need). Then, co-create with me—not just a one-shot reply, but by actively exploring better answers and even better questions."

- **Applicable Scenario:** Encourage AI to proactively explore, meeting or even exceeding user expectations.
- **Paradigm Description:** Foster a spiral of exploration, breaking user’s fixed patterns.

---

## Make AI a Rapidly-Evolving “Problem Finder” & Thinking Partner

A good prompt doesn’t make AI a passive answerer—it draws it into constructing problems, elevating thinking, evolving requirements, and helping you get better at asking the right, deeper, and newer questions. This project aims to summarize systematic patterns and processes in practice, so you can harness LLMs as intellectual partners on your thinking journey.

---

## Demo Environment Setup

1. **Python Version**  
   Python 3.9 or above recommended

2. **Dependencies**  
   Run in project root:
   ```bash
   pip install -r requirements.txt
   ```
   `requirements.txt` should include:
   ```
   openai>=1.0.0
   python-dotenv
   ```

3. **Configure OpenAI API Key**  
   At project root, create a `.env` file:
   ```
   OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
   ```
   (Replace `sk-xxxx` with your OpenAI API Key.)

---

## References

- [OpenAI Official Documentation](https://platform.openai.com/docs)
- [openai-python SDK](https://github.com/openai/openai-python)

---

For questions, feel free to open an Issue or submit a PR 🙌

---

</details>