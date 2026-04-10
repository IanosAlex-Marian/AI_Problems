# DialectRO

This project is part of the [MLCompete](https://platform.olimpiada-ai.ro/en) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

## Documentation

The project addresses multiple subtasks related to Romanian dialect analysis:
1. **Word Counting:** Counting specific word occurrences across the dataset.
2. **Punctuation Analysis:** Calculating the mean difference in punctuation frequency between dialects.
3. **Diacritics Detection:** Counting diacritic characters in the text.
4. **Dialect Classification:** Identifying dialects ("graiul moldovenesc", "graiul bănățean", and "româna standard") using a `LinearSVC` model with `TfidfVectorizer` (character n-grams 2-6).
