# Sentence Similarity Using Cosine Similarity

This project calculates the similarity between sentences using the **Cosine Similarity** method.  
The process removes certain stop words, creates a shared vocabulary, converts each sentence into a frequency-based vector, and then computes similarity based on vector angle.

---

## How It Works

1. Stop words are filtered out.
2. A vocabulary is built from the remaining meaningful words in the sentences.
3. Each sentence is converted into a numerical vector based on word frequency.
4. Cosine similarity is used to measure similarity between the vectors.

---

## Example Input

Sentence 1: "Merhabalar benim adım ümit"
Sentence 2: "selam benim adım zeynep"


---

## Example Output

Similarity Score: 0.66

A score closer to **1** indicates high similarity, while a score closer to **0** indicates low similarity.

---

## Notes for Improvement

- Expand the stop word list for higher linguistic accuracy.
- Convert text to lowercase before processing.
- Add punctuation cleaning.
- Consider using TF-IDF for more meaningful weighting.
