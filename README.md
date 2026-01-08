# Aes-Shard-2-Sha-4
Experimental Cryptographic Frameworks: AES-Shard-2 (Sharded Encryption) and Sha-4 ( Context Bound Hashing)
Overview & Attribution
This repository documents two experimental cryptographic frameworks:
AES-Shard-2 and SHA-4.
AES-Shard-2 is a sharded symmetric encryption architecture that removes the concept of a persistent encryption key.
Instead of storing or protecting a single key, encryption keys are assembled dynamically from multiple independent fragments (“shards”) and exist only briefly in memory before being destroyed.
SHA-4 is a context-bound adaptive hashing framework.
Unlike traditional hashes that are globally reusable, SHA-4 hashes are intentionally non-portable and are only valid within their intended execution context (such as a specific device, application, or time window).
These designs explore alternative security models that shift focus away from static keys and deterministic hashes toward ephemeral, context-aware cryptography.
Authorship & Contribution
The conceptual design and documentation of AES-Shard-2 and SHA-4 were developed collaboratively by:
Dean Mather
– Originated the core concepts and security model shifts
– Defined how sharded keys and context-bound hashes should behave
– Directed the overall architecture and intended use cases
– Led final documentation and publication
ChatGPT (OpenAI)
– Assisted with structured reasoning and design iteration
– Helped translate abstract ideas into clear technical explanations
– Supported documentation drafting and refinement
– Provided feedback on clarity, consistency, and framing
This collaboration combined human-led conceptual design with AI-assisted reasoning and documentation, resulting in the frameworks presented here.
Status & Disclaimer
These frameworks are conceptual and experimental.
They are not formal cryptographic standards, have not been audited, and are not intended to replace existing algorithms such as AES, SHA-2, or SHA-3.
Independent cryptographic review is recommended before any real-world use.
