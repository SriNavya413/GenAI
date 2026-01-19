### Embeddings
An embedding is a numerical representation of text that captures its meaning by placing it as a point in a high-dimensional space.
### Why Embeddings Are Needed
1️⃣ Traditional Search (Lexical Search)
##### Example: Ctrl + F
Matches exact keywords
Works by comparing letters
Counts and highlights word occurrences
📌 This is called lexical search.
❌ Limitations
Works only if the exact word exists
Cannot understand meaning or similarity
#### Example:
Search for “cat” ❌ will NOT return “feline”
Computer matches letters, not concepts

### 2. Library Example (Human vs Machine Search)
Imagine a library
A student asks for books related to a topic
Librarian searches the catalog
If the exact keyword exists → book is found
If not → no result
### Humans understand:
Cat and Feline are related
Machines using lexical search:
Do NOT understand this relationship

### Supermarket Example
#### How a Supermarket Is Organized
Items are not arranged alphabetically.
#### They are arranged by category:
Fruits together
Soaps together
Pet food together

### Supermarket as Coordinates
Imagine every item has a location number.

### Item	       Location
Apple	            (1,5)
Banana	          (1,6)
Shampoo	          (10,2)
Dog Food	        (12,4)

### What This Means
Apple and Banana are close
Shampoo and Dog Food are far
 Close location = similar category

 ### Mapping Supermarket to Embeddings (Clear View)
### Real World	                                               Embeddings
Supermarket item	                                           Word / sentence
Shelf location	                                               Embedding
Distance between items	                                     Meaning similarity
Same aisle	                                                   Similar concept

 
