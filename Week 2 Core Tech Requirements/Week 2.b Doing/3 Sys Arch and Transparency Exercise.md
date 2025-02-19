## Architecture Review Exercise

### Example System Assessment

Review this simplified architecture diagram and identify missing transparency components:

```
┌─────────────────┐      ┌─────────────────┐      ┌─────────────────┐
│                 │      │                 │      │                 │
│  Client App     │──────│  API Gateway    │──────│  Model Server   │
│                 │      │                 │      │                 │
└─────────────────┘      └─────────────────┘      └─────────────────┘
                                                         │
                                                         │
                                                  ┌──────▼──────┐
                                                  │             │
                                                  │  Database   │
                                                  │             │
                                                  └─────────────┘
```

### Implementation Exercise

For the simplified architecture above, identify:
1. Missing transparency components
2. Required data flows
3. Integration points for EU AI Act compliance


- Compliance testing frameworks
- Architecture validation tools
- Documentation generators
- Gap analysis templates

### Submission Directions
Submit your work for feedback here: https://chatgpt.com/g/g-67b5fb834f3c81919fabc4f3af4d7070-eu-ai-act-checker
Your submission with feedback and the conversation you have with the AI TA will be recorded as part of your completion. 

Remember: The EU AI Act specifies **what** transparency capabilities your architecture must support, but the **how** of implementation is flexible and should align with your organization's technical stack and practices.
