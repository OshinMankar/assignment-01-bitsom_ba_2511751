### Vector DB Use Case

A simple keyword-based search would not be enough for this system. It only matches exact words, so if the wording in the contract is slightly different from what the lawyer types, important information might not show up.
For example, if someone searches for “termination clauses,” but the contract uses phrases like “end of agreement” or “contract cancellation,” a keyword search might miss those sections completely.

This is where a vector database becomes useful. Instead of just looking at words, it understands the meaning behind the text. It converts both the contract content and the user’s question into numerical representations (called embeddings) and then finds the most similar matches based on meaning.
In practice, the contract can be divided into smaller sections and stored as vectors. When a lawyer asks a question, the system quickly finds the most relevant parts and shows them.

Overall, this makes searching much more accurate and helpful, especially when dealing with large documents like 500-page contracts.
