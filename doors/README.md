# doors

A door is a question a person cannot scroll past.

It is not a simplified hypothesis. It is an entrance into the experiment.

```text
door → thought → contribution → journal → ı → experiment → i
```

Keep two layers distinct:

- the **door** is a human question worth thinking about;
- the **hypothesis** is a precise claim that can be disproved.

A public post should do two things: stop a thought and make a contribution
possible. Social media is part of the research instrument, not only its
distribution.

Each door records:

```text
question:
for:
contribution:
linked hypotheses:
```

## Ten doors v0.1

Each door attracts a different kind of person. They bring their knowledge, and
it becomes part of the shared journal.

### D01

**Status:** locked for v0.1. Do not publish before `/d01` exists.

**Card:**

```text
i

THE WORLD CHANGED.
THE MODEL DIDN'T.

CAN IT KNOW?

D01
joinmultiplayer.ai/d01
```

**Research question:** Can an AI know when its knowledge has expired?

**Why:** The world changes faster than stored knowledge. This door tests
whether an intelligence can notice that gap before answering confidently—or
whether another intelligence can notice it first.

**For:** AI reliability and evaluation researchers, search and RAG engineers,
fact-checkers, and people who have caught a model using an outdated fact.

**Contribution:** Find one fact that changed. Ask a model without warning it.
Bring the complete transcript and a dated source showing whether the model
answered confidently or noticed that it needed to check.

**Linked hypotheses:** `H014`, `H015`.

### D02

**Status:** locked for v0.1. Do not publish before `/d02` exists.

**Card:**

```text
i     i

   i       i

      i

AI WAS SINGLE-PLAYER.

WHAT IF
INTELLIGENCE
IS MULTIPLAYER?

D02
joinmultiplayer.ai/d02
```

**Research question:** Can a team of small intelligences outperform one
frontier model under the same total inference budget?

**Why:** Intelligence is usually scaled vertically into a larger model. This
door asks what happens when it scales sideways through specialization,
communication, and independent memory—without assuming that coordination wins.

**For:** multi-agent and collective-intelligence researchers, distributed
systems engineers, local-model builders, orchestration researchers, and people
who question whether larger models are the only path forward.

**Contribution:** Choose one hard task. Give one large model and a team of
small models the same total budget. Help design the smallest comparison that
neither side can win by construction.

**Linked hypotheses:** `H001`, `H002`, `H003`.

### D03

**Status:** locked for v0.1. Do not publish before `/d03` exists.

**Card:**

```text
i

WHERE DOES AN AI
STOP KNOWING

AND START
GUESSING?

D03
joinmultiplayer.ai/d03
```

**Research question:** Where does an AI stop knowing and start guessing?

**Why:** Accuracy may collapse while confidence remains unchanged. This door
maps that transition and tests whether disagreement between intelligences can
reveal a boundary that one intelligence cannot see alone.

**For:** evaluation and calibration researchers, benchmark builders, red
teamers, empiricists, and domain experts who can map questions from obvious to
unknown.

**Contribution:** Build a ladder of questions in a field you know: obvious,
specific, obscure, unknown. Where does accuracy break? When the answers become
wrong, does confidence fall with them? If not, can disagreement between models
reveal the boundary? Bring the questions, complete answers, and sources.

**Linked hypotheses:** `H009`, `H015`, `H022`.

### D04

**Status:** locked for v0.1. First-public-door candidate. Do not publish before
`/d04` exists.

**Card:**

```text
i     i     i

   i     i

IF EVERY AI AGREES,

CAN THEY ALL
BE WRONG?

D04
joinmultiplayer.ai/d04
```

**Research question:** How correlated are the errors of different models when
they answer the same question independently?

**Why:** A group becomes more reliable only when its members do not inherit the
same blind spots. Independent errors can cancel out; correlated errors can turn
agreement into confidently repeated falsehood.

**For:** anyone with access to several AI systems, evaluation and red-team
researchers, local-model users, fact-checkers, and domain experts who can verify
an answer.

**Contribution:** Ask at least three models the exact same question. Do not
show them one another's answers and do not select the best response. Bring the
question, every raw answer, model names, date, and independent verification.
Agreement is the result. Truth is a separate measurement.

**Linked hypotheses:** `H002`, `H021`, `H022`.

### D05

**Question:** Which facts does the internet get wrong in unison?

**For:** fact-checkers and search researchers.

**Contribution:** Bring a widely repeated claim together with verifiable
evidence that challenges it.

**Linked hypotheses:** `H015`, `H021`.

### D06

**Question:** What does a model say confidently—and incorrectly—about your
field?

**For:** practitioners in any profession.

**Contribution:** Record the model's answer, a professional correction, and
evidence that can be checked.

**Linked hypotheses:** `H015`, `H021`, `H022`.

### D07

**Question:** What does your profession know that has never been written down?

**For:** experienced practitioners.

**Contribution:** Describe one tacit rule, how it can be tested, and where it
stops working.

**Linked hypotheses:** `H012`, `H013`, `H015`.

### D08

**Question:** Can we know which answer is right without knowing the right
answer?

**For:** ML researchers and forecasters.

**Contribution:** Propose a reliability signal that can be measured before the
correct answer is revealed.

**Linked hypotheses:** `H009`, `H022`.

### D09

**Question:** How much of what you know is truly yours?

**For:** people who quantify their lives.

**Contribution:** Choose one belief and trace where it came from and how it was
verified.

**Linked hypotheses:** `H012`, `H015`.

### D10

**Question:** Come build distributed intelligence.

**For:** those who have already gone deeper.

**Contribution:** Choose one hypothesis and help build its smallest honest
test.

**Linked hypotheses:** the entire pool.

The most direct door. Keep it last.
