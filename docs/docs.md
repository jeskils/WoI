## Documents  

_This section is archived and represents early experiments leading to the **Word of Information (WoI)** concept — connecting linguistic structure, information theory, and biological signal interpretation._

The documents below represent the scientific and conceptual foundation of my work.  
My master’s thesis explores the use of **Mutual Information (MI)** in brain signal prediction, while the **concept document** extends this idea into **language modeling and information representation**, forming the basis for the *Word of Information (WoI)* framework.  

Together, they bridge biological computation and artificial intelligence — showing how measurable information can unify both worlds.

📄 [Master’s Thesis — “Evaluating the ability of Mutual Information to detect epileptic seizures in EEG data” (PDF)](docs/60HP.pdf) — archived  
📄 [Concept Document — “Mutual Information as Information in Language” (PDF)](docs/concept.md) — archived  

---

## Question  

**Is it possible to build a model that can predict the color, variety and estimate the quality of a wine just from the words in a review?**

---

### Answer  

Of course, one can search for specific word combinations in a review and compare them to a known collection of words (corpus) to make predictions.  
My method is to match the words in the review with a set of important words (found using a technique called **Mutual Information**) and then represent each word as a column in a binary matrix.  

This means each review gets a vector or *fingerprint* of zeros and ones, depending on whether certain words appear in the text.  
For example, *“tannins”* might represent a red wine characteristic, while *“peach”* could indicate a white wine.  
With enough labeled reviews, this matrix can reveal patterns and similarities between different reviews.

---

### White, Red & Rosé  

The color, flavor and quality of a wine is characterized by the use of certain words in a review.  
By extracting the words that describe a typical Red or White wine it is possible to predict the color.  

| **Red Wine Descriptors** | **White Wine Descriptors** |
|---------------------------|-----------------------------|
| Dark fruit: blackberry, blackcurrant, plum, cherry | Citrus: lemon, lime, grapefruit, orange |
| Spicy: pepper, clove, cinnamon, tobacco | Tropical: pineapple, mango, papaya, passion fruit |
| Earthy: leather, forest floor, mushroom | Floral: jasmine, honeysuckle, elderflower |
| Tannic: grippy, astringent, structured | Mineral: chalky, flinty, wet stone |
| Rich: full-bodied, bold, concentrated | Crisp: fresh, zesty, sharp, lively acidity |
| Herbal: thyme, rosemary, eucalyptus | Creamy: buttery, smooth, silky |
| Smoky: oak, toasted, vanilla | Green fruit: apple, pear, green grape |

---

### Example Review  

> *Deep, dense and pure from the opening bell, this Toro is a winner. Aromas of dark ripe black fruits are cool and moderately oaked. This feels massive on the palate but sensationally balanced. Flavors of blackberry, coffee, mocha and toasty oak finish spicy, smooth and heady. Drink this exemplary Toro through 2023.*

---

### Archived Results  

*(This section reflects earlier API experiments that demonstrated prediction logic before deployment support was removed.)*

**Matched Words:**  
`tannins, oak, blackberry, mocha, spice`

**Predicted Output (archived):**  
`Red Wine — Variety: Toro — Estimated Quality: 9.2 / 10`

---