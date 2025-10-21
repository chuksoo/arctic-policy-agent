# Arctic Policy Agent
An Agentic AI system for a local government department specifically focusing on the initial screening and policy clarification for public assistance programs like SNAP, Medicaid, and TANF, using the official department manuals at https://manuals.dfcs.alaska.gov/ as the primary knowledge source.

The AI system, the **AK Benefits Navigator**, should perform the following actions:

1. **Interpret Natural Language Queries:** Understand complex questions about program eligibility (e.g., income limits, residency, asset rules).

2. **Retrieve Policy:** Use Retrieval-Augmented Generation (RAG) to find the exact, cited section of the DFCS policy manual that answers the query.

3. **Check Dynamic Rules (Act):** Call an external, auditable API tool to fetch up-to-date, non-static data, such as the current Federal Poverty Level (FPL) or maximum allowable income limits.

4. **Provide Grounded Answers:** Deliver a personalized, highly accurate answer to the citizen, always including the specific citation (e.g., DPA Manual, § 10.120) to ensure trust and compliance.
