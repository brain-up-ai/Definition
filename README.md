# Brain-up AI

Brain-up AI (BAI) refers to an AI-powered app that supports human learning. This involves providing information that is:

- **Accurate:** Correct, up-to-date and references external systems.
- **Foundational:** Directs towards foundational (simpler) information.
- **Related:** Can be connected or mapped with one another.
- **Goal-oriented:** Focused on the very next step that solves the problem.

## Mini Examples

The folowing examples start with problems that a user wants to solve. Each problem is followed with directions on how a BAI app should provide an answer.

### Accurate

**Problem:** What is the weather in Toronto?

BAI app should consult external sources like Weather.com and accurately retrieve the weather conditions in Toronto.

### Foundational

**Problem:** What is the solution to `x + 7 = 10`?

BAI app should direct towards foundational Algebra lessons that provide structured steps on solving similar problems. Examples of such lessons include Khan Academy videos or OpenStax textbooks.

### Related

**Problem:** What is an HTML page?

BAI app should refer to related concepts like websites and computer languages.

### Goal-oriented

**Problem:** What is pecorino romano in cacio e pepe?

BAI app should provide infromation about pecorino romano in relation to cacio e pepe, like how it's used in that specific dish.

## Full Example

The following is a full example of what chat-style, BAI app would look like:

### Simple Question

- **User Question 1:** What is Cacio e pepe?

- **BAI App Answer 1:**

```
Cacio e pepe is an Italian pasta dish that "contains grated pecorino romano
and black pepper with tonnarelli or spaghetti" (Wikipedia).

Check out the following article from wikipedia.com that provides basic
information about Cacio e pepe: https://en.wikipedia.org/wiki/Cacio_e_pepe

Follow-up quesitons:
-------------------------------     ---------------------------------
|   What is pecorino romano?  |     | What's the difference between |
-------------------------------     | tonnarelli and spaghetti?     |
                                    ---------------------------------
```

---

- **User Question 2:** What is pecorino romano?

- **BAI App Answer 2:**

```
Pecorino romano is a "hard, salty Italian cheese" that is grated over
Cacio e pepe (Wikipedia).

Here's a recipe that discusses using pecorino romano and other cheeses in
Cacio e pepe: https://www.stefanofaita.com/en/recipes/classic-cacio-e-pepe/

Follow-up quesitons:
--------------------------
|     Alternatives to    |
|     pecorino romano?   |
--------------------------
```

#### Analysis

In the _BAI App Answer 1_, the AI app searches up Wikipedia and quotes the article in its response. This helps ensures **accuracy**.

Additionally, the BAI app **relates** its answer to **foundational** (simpler) concepts like "Italian pasta".

Then, at the end of its responses, the BAI app provides follow-up questions that address **foundational** questions, like "What is pecorino romano?"

Finally, in _BAI App Answer 2_, the BAI app provides an answer **related** to the **user's goal**: learning about cacio e pepe. As such, it links to a recipe about pecorino romano in cacio e pepe, instead of another Wikipedia article.
