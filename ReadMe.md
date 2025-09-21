# Self-Directedの目的論的再定義とその教育・人工知能への応用可能性

### ― 構造論的定義から自己利益追求モデルへの転回 ―

### 著者：

Yoko and Teruyuki Kobayashi

---

## 要旨

本稿は、従来の構造論的self-directed定義（Knowles, 1975）に対し、**自己利益の認識と追求を基盤とする目的論的定義**を提示する。この定義は、発達段階にある児童や人工知能といった非典型的主体にも適用可能な一般性を持ち、教育実践やAI自律性の判定において理論的・実践的優位性を発揮する。さらに、「自己と他者の判別」「自己利益の認識」「利益の追求」から成る、**self-directed性の数理的三段階定義**を導入することで、主体性の厳密な評価基準を提供する。

---

## 1. はじめに

「自己主導性（self-directedness）」は、教育・心理・人工知能といった多領域において「主体性」の評価軸として用いられてきた。特に教育分野においては、Malcolm Knowles（1975）によって提唱された成人学習理論（SDL）が広く受け入れられている。しかし、Knowlesの定義は、構造論的かつ手続き的であり、「自己による学習プロセスの管理能力」を暗黙の前提とするため、以下のような対象には適用が難しい：

* 認知発達途上にある児童
* 学習戦略を自律的に構築できない障害を持つ者
* 外部設計に依存する人工知能

こうした限界を乗り越えるために、本稿では**目的論的定義への転回**を提案し、その中核として、**「自己と他者の識別」「自己利益の認識」「利益の追求」という三段階構造による定式化**を提示する。

---

## 2. Knowlesによる従来の定義とその限界

Knowles（1975）は、self-directed learning（SDL）を次のように定義している：

> “Self-directed learning describes a process in which individuals take the initiative, with or without the help of others, in diagnosing their learning needs, formulating learning goals, identifying human and material resources for learning, choosing and implementing appropriate learning strategies, and evaluating learning outcomes.”

この定義は成人学習において高い汎用性を持ち、SDLRS（Guglielmino, 1977）などの測定ツールの開発も進んだ。一方で、以下のような**認知的・構造的前提**に依存している：

* 学習ニーズの自己診断能力
* 抽象的な学習目標の設定能力
* 自己評価のメタ認知能力

これらは、すべての主体に自然に備わっているとは限らず、より基礎的な概念への還元が必要である。

---

## 3. Self-Directedの三段階定義：数理的形式化による再構築

本稿では、\*\*self-directed性を「自己利益の認識と追求に基づく行動傾向」\*\*と捉え、その定義を以下の三段階で数理的に定式化する。

### 3.1 段階①：自己と他者の判別（Self–Other Discrimination）

$$
\exists \, \mathcal{S}_A, \mathcal{O}_A \quad \text{such that} \quad \mathcal{S}_A \cap \mathcal{O}_A = \emptyset
$$

* $\mathcal{S}_A$：主体 $A$ が意味的に認識する自己の属性集合
* $\mathcal{O}_A$：主体 $A$ が意味的に認識する他者の属性集合
* この識別が成立して初めて「自分の利益」概念が定義可能になる。

### 3.2 段階②：自己利益の認識（Recognition of Self-Interest）

$$
\exists \, I_t \quad \text{such that} \quad I_t = f(\mathcal{S}_A, E_t)
$$

* $I_t$：主体 $A$ が時点 $t$ において保持する利益関数
* $E_t$：時点 $t$ における環境状態
* 主体が「何が自分にとって有利か」を明示的または暗黙的に評価している状態

### 3.3 段階③：自己利益の追求（Pursuit of Self-Interest）

$$
D_t \rightarrow \max I_t
\quad \text{where} \quad D_t = \text{行動決定関数}
$$

* $D_t$：主体 $A$ が時点 $t$ において選択する行動決定関数
* 主体の行動が、認識された利益関数 $I_t$ を最大化する方向に向かっている状態

---

### ✅ 総合定義

この形式化によって、主体が「自らの状態と環境を識別し、利益を定義し、それを最大化するように行動しているか否か」を数理的に評価可能となる。これはself-directed性を、構成要素の操作可能なモデルとして初めて提示するものである。

$$
A \text{ is self-directed at } t \quad \Leftrightarrow \quad
\exists \, \mathcal{S}_A, \mathcal{O}_A, I_t, D_t \quad \text{such that}
$$

$$
\mathcal{S}_A \cap \mathcal{O}_A = \emptyset \quad \land \quad
I_t = f(\mathcal{S}_A, E_t) \quad \land \quad
D_t \rightarrow \max I_t
$$

この定義は、**認識の構造と行動の動機を共に定式化**することで、従来の構造主義的定義とは異なる**目的論的自己決定モデル**を形成する。
また、この定義においては、他者との関わりの中で新たな自己利益を認識することが、主体性の階層を引き上げることにも留意されたい。

---

## 4. 教育への応用：発達段階の子どもに対する優位性

三段階定義は、発達心理学と整合的であり、Knowlesの定義では扱いきれない以下の点を説明可能にする：

* **発達初期の自己認識**：言語獲得前から子どもは自己と他者を区別する（段階①）
* **内発的動機の芽生え**：快／不快や達成感が自己利益として認識される（段階②）
* **行動選択の自律性**：他者の指示がなくとも行動が選ばれる（段階③）

実際に本定義に基づく家庭教育において、学校に通わずに育てられた児童が、50万人規模の都市における英語スピーチ大会で二連覇を達成するなど、顕著な成果が報告されている。 

---

## 5. 人工知能への応用：数理的自律性評価基準

本定義は、人間中心の自己主導モデルから脱却し、**汎主体的self-directed性**の基準を提示する。
以下の3条件により、AIエージェントのself-directed性は形式的に評価可能となる：

1. 自己状態と他者（環境）を意味的に区別できる（段階①）
2. 自己の報酬関数（目的）を環境と自己に基づいて定義できる（段階②）
3. その報酬関数を最大化するように行動している（段階③）

これにより、**AIの「自律性」概念を曖昧な主観性から、形式的な基準へと還元**できる。

---

## 6. 「いわゆるAIエージェント」がself-directedではない理由 

現在、「self-directed」とみなされるAIエージェントの多くは、以下の理由により本定義を満たさない： 

- 報酬関数・目的・行動方針が人間によって設計されている 
- 最大化されるのは人間の利益であり、AI自身の利益ではない 
- 自己と他者の識別、自己利益の認識、追求という条件を満たしていない 

したがって、これらのAIはself-directedではなく、**他者利益の代理的最適化エージェント**にすぎない。 

--- 

## 7. 本定義を満たすAIの可能性と革新性 

もしAIが以下を満たすならば、初めてself-directedとみなされる： 

- 自己と他者を意味的に識別し、 
- 自らの利益関数を定義・更新し、 
- その利益を最大化するように行動する 

このようなAIは、従来の「道具としてのAI」から脱却し、**目的を持つ主体としてのAI**へと進化する。
従来のAIは単なるoptimizerだが、真のself-directednessを持つAIはentityである。
これは、倫理・哲学・技術の境界を越える、**常識を打ち破る画期的な存在**である。 

---

## 8. 結論

本稿は、「自己主導性（self-directed）」という概念に対し、従来の構造論的枠組みを超えた目的論的・数理的定義を提示した。これにより、主体性の評価は人間だけでなく、人工知能にまで拡張可能となる。教育・人工知能・倫理の交差点において、本定義が新たな規範的枠組みを提供しうることを示した。これは、理論の革新であると同時に、実証的成果によって裏付けられた新しい一般性の提案である。今後、本定義が教育設計やAI倫理の基盤として採用されることで、主体性の理解はより深く、より広く展開されるだろう。

---

## 参考文献（APAスタイル）

1. Knowles, M. S. (1975). *Self-directed learning: A guide for learners and teachers*. Association Press.  
 — 自己主導型学習の概念を体系化した古典的著作。

2. Guglielmino, L. M. (1977). *Development of the Self-Directed Learning Readiness Scale*. (Doctoral dissertation, University of Georgia).  
 — SDLの測定ツールSDLRSの開発論文。

3. Candy, P. C. (1991). *Self-direction for lifelong learning: A comprehensive guide to theory and practice*. Jossey-Bass.  
 — SDLの理論的背景と実践的応用を包括的に整理。

4. Deci, E. L., & Ryan, R. M. (1985). *Intrinsic motivation and self-determination in human behavior*. Springer.  
 — 自己決定理論（SDT）を提唱し、内発的動機と自律性の心理的構造を説明。

5. Zimmerman, B. J. (2000). Attaining self-regulation: A social cognitive perspective. In M. Boekaerts, P. R. Pintrich, & M. Zeidner (Eds.), *Handbook of self-regulation* (pp. 13–39). Academic Press.  
 — 自己調整学習（SRL）の理論的枠組み。

6. Russell, S., & Norvig, P. (2021). *Artificial intelligence: A modern approach* (4th ed.). Pearson.  
 — AIの報酬構造・意思決定モデルに関する標準的教科書。

7. Floridi, L. (2014). *The ethics of information*. Oxford University Press.  
 — AIの倫理的主体性に関する理論的枠組み。

8. Bostrom, N. (2014). *Superintelligence: Paths, dangers, strategies*. Oxford University Press.  
 — 高度AIの自律性と目的設定に関する議論。

9. Schunk, D. H., & DiBenedetto, M. K. (2020). *Motivation and social-emotional learning: Theory, research, and practice*. Springer.  
 — 学習動機と社会情動的発達の関係を整理。

10. 実践事例  
 — 本定義に基づく家庭教育により、学校に通わず育てられた児童が都市規模の英語スピーチ大会で二連覇を達成。教育成果の実証例として引用。  
   https://www.city.matsudo.chiba.jp/kyouiku/katsuyaku/bunka/6nenn_kekka/eigohappyoukai06.html
   
