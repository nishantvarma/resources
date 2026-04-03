# cs/path

goal: foundations of cs, strong in toc, aiml, it

---

## phase 0 — prerequisites (math/)

| goal | resource |
|------|----------|
| toc  | math/dm — discrete math (sets, combinatorics, proofs) |
| toc  | math/logic — propositional + predicate logic |
| aiml | math/la — linear algebra (axler, sanderson) |
| aiml | math/prob, math/stat — probability + statistics |
| aiml | math/calc — calculus (for backprop) |

---

## phase 1 — foundations (cs/elem)

1. code-charles-petzold
2. coursera-from-nand-to-tetris + the-elements-of-computing-systems-nisan-schocken
3. structure-and-interpretation-of-computer-programs-abelson-sussman + mit-6001-sicp
4. computer-science-an-interdisciplinary-approach-sedgewick

---

## phase 2 — algorithms (cs/algo)

1. mit-6006-introduction-to-algorithms
2. algorithm-and-data-structures-niklaus-wirth
3. the-art-of-computer-programming-donald-knuth (reference)

---

## phase 3a — theory of computation (cs/toc)

1. annotated-turing-charles-petzold
2. introduction-to-the-theory-of-computation-michael-sipser
3. mit-18404j-theory-of-computation
4. introduction-to-theoretical-computer-science-boaz-barak
5. cmu-15-251-great-theoretical-ideas-in-computer-science
6. mathematics-and-computation-avi-wigderson
7. computation-finite-and-infinite-machines-marvin-minsky
8. godel-escher-bach-douglas-hofstadter
9. the-nature-of-computation-moore-mertens
10. on-computable-numbers-alan-turing (primary source)

talks:
- what-is-computation-leslie-lamport
- beyond-computation-the-p-vs-np-problem-michael-sipser
- hardware-software-and-heuristics-richard-feynman
- feynman-and-computation-tony-hey
- alan-turing-a-tcs-role-model-avi-wigderson
- algebra-logic-geometry-at-the-foundation-of-cs-car-hoare
- algorithms-complexity-and-the-art-of-computer-programming-donald-knuth
- churchs-coincidences-philip-wadler
- lambda-calculus-david-beazley
- lambda-calculus-then-and-now-dana-scott
- lambda-calculus-vs-turing-machines-advait-shinde
- what-is-computability-joel-david-hamkins
- turing-godel-and-church-at-princeton-andrew-appel
- programming-the-turing-machine-barbara-liskov
- we-really-dont-know-how-to-compute-gerry-sussman

biographical:
- george-boole-madhu-sudhan
- turing-the-man-acm
- turing-pioneer-of-the-information-age-jack-copeland
- the-turing-computational-model-acm
- celebrating-emil-post-stephen-wolfram
- open-texture-computability-and-churchs-thesis-stewart-shapiro
- who-is-the-human-computer-oron-shagrir
- computable-real-numbers-edmund-clarke

---

## phase 3b — aiml (cs/aiml)

1. ucb-cs188-introduction-to-artificial-intelligence
2. machine-learning-andrew-ng
3. hands-on-machine-learning-with-scikit-learn-keras-tensorflow-aurelien-geron
4. neural-networks-grant-sanderson
5. introduction-to-neural-networks-and-backpropagation-building-micrograd-andrej-karpathy
6. deep-learning-andrew-ng + deep-learning-goodfellow-bengio-courville
7. introduction-to-language-modeling-building-makemore-andrej-karpathy
8. lets-build-llm-from-scratch-andrej-karpathy
9. the-annotated-transformer-alexander-rush
10. deep-dive-into-llms-like-chatgpt-andrej-karpathy
11. build-a-large-language-model-from-scratch-sebastian-raschka
12. probabilistic-graphical-models-koller-and-friedman
13. artificial-intelligence-a-guide-for-thinking-humans-melanie-mitchell

talks:
- how-neural-networks-learned-to-talk-art-of-the-problem
- introduction-to-large-language-models-andrej-karpathy
- introduction-to-neural-networks-and-backpropagation-building-micrograd-andrej-karpathy
- the-long-story-of-how-neural-nets-got-to-where-they-are-terry-sejnowski
- what-is-chatgpt-doing-and-why-does-it-work-stephen-wolfram
- programs-with-common-sense-john-mccarthy (historical)
- the-master-algorithm-pedro-domingos

---

## phase 3c — information theory (cs/it)

it bridges toc (kolmogorov complexity) and aiml (cross-entropy, kl divergence)

1. the-information-james-gleick
2. mathematical-theory-of-communication-claude-shannon
3. a-symbolic-analysis-of-relay-claude-shannon
4. an-introduction-to-information-theory-john-pierce
5. elements-of-information-theory-cover-thomas
6. information-theory-inference-and-learning-algorithms-david-mackay

talks:
- introduction-to-information-theory-ryan-adams

---

## map

    math/dm + math/logic
            |
    cs/elem (petzold -> nand2tetris -> sicp)
            |
    cs/algo (mit-6006 -> knuth)
            |
        +---+-------------------+
        |                       |
    cs/toc (sipser -> mit18404j)  math/la + math/prob
        |                       |
    cs/it (shannon -> mackay) -> cs/aiml (cs188 -> ng -> karpathy)
        |                       |
        +-----------+-----------+
                    |
              geb + wigderson
