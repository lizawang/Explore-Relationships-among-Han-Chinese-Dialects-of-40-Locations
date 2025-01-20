### Distances Matrix of distances of all language pairs which can be used in Gabmap.

### Note that the variant distance is computed by adding up its seperately computed segment distance and tone distance. This is important because if a variant distance is computed directly without seperately computing segment and tone distances first and adding them up later, the resulting variant distance is different. <br>

Aka, distance(segment+tone) != distance(segment) + distance(tone), when using Levenshtein edit distance and TFIDF.
