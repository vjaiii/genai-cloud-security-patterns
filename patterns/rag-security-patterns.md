# RAG Security Patterns

Retrieval Augmented Generation (RAG) systems connect LLMs to internal data sources.

This introduces several security concerns.

## Risks

Unauthorized document retrieval

Prompt injection altering retrieval behavior

Sensitive data leakage

Excessive document access

## Security patterns

Least privilege access to document stores

User identity passed to retrieval layer

Document-level access controls

Sanitized prompts before retrieval

Logging all retrieval operations

## Additional recommendations

Separate AI service accounts

Network isolation for vector databases

Encryption for embeddings storage

Security review of indexing pipelines
