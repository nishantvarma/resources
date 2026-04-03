# Path to Theoretical Computer Science

goal: theory of computation, information theory, ai/ml — foundations of the field

---

## Stage 0 — Mathematical Prerequisites

| area | resource |
|------|----------|
| toc  | Discrete Mathematics and Its Applications — Rosen (or math path stage 3) |
| toc  | Logic — propositional + predicate |
| aiml | Linear Algebra Done Right — Axler / The Essence of Linear Algebra — Sanderson |
| aiml | Introduction to Probability — Blitzstein & Hwang |
| aiml | Calculus — Spivak (or math path) |

---

## Stage 1 — Foundations of Computing

1. **Code** — Charles Petzold
2. **The Elements of Computing Systems** — Nisan & Schocken + Nand to Tetris course
3. **Structure and Interpretation of Computer Programs** — Abelson & Sussman + MIT 6001
4. **Computer Science: An Interdisciplinary Approach** — Sedgewick & Wayne

---

## Stage 2 — Algorithms

1. **Introduction to Algorithms** — Cormen, Leiserson, Rivest & Stein + MIT 6006
2. **Algorithms and Data Structures** — Niklaus Wirth
3. **The Art of Computer Programming** — Donald Knuth (reference)

---

## Stage 3a — Theory of Computation

1. **The Annotated Turing** — Charles Petzold — guided reading of the original paper
2. **Introduction to the Theory of Computation** — Michael Sipser
3. MIT 18404J — Theory of Computation (Sipser's own course)
4. **Introduction to Theoretical Computer Science** — Boaz Barak — free, modern, complements Sipser
5. CMU 15-251 — Great Theoretical Ideas in Computer Science
6. **Mathematics and Computation** — Avi Wigderson — complexity theory
7. **Computation: Finite and Infinite Machines** — Marvin Minsky
8. **Post's Machine** — Vladimir Uspensky
8. **Gödel, Escher, Bach** — Douglas Hofstadter — incompleteness, self-reference, consciousness
9. **The Emperor's New Mind** — Roger Penrose — computation, physics and the mind; read alongside GEB
10. **The Nature of Computation** — Cristopher Moore & Stephan Mertens — comprehensive complexity
10. **On Computable Numbers** — Alan Turing (primary source, 1936)

talks:
- What Is Computation — Leslie Lamport
- Beyond Computation: The P vs NP Problem — Michael Sipser
- Hardware, Software and Heuristics — Richard Feynman
- Feynman and Computation — Tony Hey
- Alan Turing: A TCS Role Model — Avi Wigderson
- Algebra, Logic, Geometry at the Foundation of CS — C.A.R. Hoare
- Algorithms, Complexity and TAOCP — Donald Knuth
- Church's Coincidences — Philip Wadler
- Lambda Calculus — David Beazley
- Lambda Calculus Then and Now — Dana Scott
- Lambda Calculus vs Turing Machines — Advait Shinde
- What Is Computability? — Joel David Hamkins
- Turing, Gödel and Church at Princeton — Andrew Appel
- Programming the Turing Machine — Barbara Liskov
- We Really Don't Know How to Compute — Gerald Sussman

biographical:
- George Boole — Madhu Sudan
- Turing: The Man — ACM
- Turing, Pioneer of the Information Age — Jack Copeland
- Celebrating Emil Post — Stephen Wolfram
- Open Texture, Computability and Church's Thesis — Stewart Shapiro
- Who Is the Human Computer in Turing's Analysis? — Oron Shagrir

---

## Stage 3b — AI & Machine Learning

1. UCB CS188 — Introduction to Artificial Intelligence (Russell & Norvig textbook)
2. **Machine Learning** — Andrew Ng (course)
3. **Hands-On Machine Learning** — Aurélien Géron
4. **Neural Networks** — Grant Sanderson
5. Neural Networks and Backpropagation: Building Micrograd — Andrej Karpathy
6. **Deep Learning** — Andrew Ng (course) + **Deep Learning** — Goodfellow, Bengio & Courville
7. Language Modeling: Building Makemore — Andrej Karpathy
8. Building an LLM from Scratch — Andrej Karpathy
9. **The Annotated Transformer** — Alexander Rush
10. Deep Dive into LLMs — Andrej Karpathy
11. **Build a Large Language Model from Scratch** — Sebastian Raschka
12. **Probabilistic Graphical Models** — Koller & Friedman
13. **Artificial Intelligence: A Guide for Thinking Humans** — Melanie Mitchell

talks:
- How Neural Networks Learned to Talk — Art of the Problem
- Introduction to Large Language Models — Andrej Karpathy
- The Long Story of How Neural Nets Got Here — Terry Sejnowski
- What Is ChatGPT Doing? — Stephen Wolfram
- Programs with Common Sense — John McCarthy (1958, historical)
- The Master Algorithm — Pedro Domingos

---

## Stage 3c — Information Theory

information theory bridges toc (kolmogorov complexity) and aiml (cross-entropy, kl divergence)

1. **The Information** — James Gleick — accessible narrative; read this first
2. **A Mathematical Theory of Communication** — Claude Shannon (1948)
3. **A Symbolic Analysis of Relay and Switching Circuits** — Claude Shannon (master's thesis, 1937)
4. **An Introduction to Information Theory** — John Pierce
5. **Elements of Information Theory** — Cover & Thomas
6. **Information Theory, Inference, and Learning Algorithms** — David MacKay

talks:
- Introduction to Information Theory — Ryan Adams

---

## Map

    prerequisites (discrete math, logic, linear algebra, probability)
            |
    stage 1: foundations (petzold → nand2tetris → sicp)
            |
    stage 2: algorithms (clrs + mit 6006 → knuth)
            |
        +---+-------------------+
        |                       |
    stage 3a: toc            prereqs: la + prob
    (sipser → mit 18404j)       |
        |                       ↓
    stage 3c: it ──────────→ stage 3b: aiml
    (shannon → mackay)      (cs188 → ng → karpathy)
        |                       |
        +-----------+-----------+
                    |
              geb + wigderson

---

## Notes

- Do stage 3c alongside or between 3a and 3b — information theory bridges both.
- GEB is best read after Sipser — the incompleteness results land differently once you know the formal machinery.
- Shannon's 1948 paper is short and readable; the master's thesis shows the Boolean algebra connection.
- CS188 before neural networks — gives the full classical AI picture first.
