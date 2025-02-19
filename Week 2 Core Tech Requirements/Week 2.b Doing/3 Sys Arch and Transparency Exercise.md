## Architecture Review Exercise

**Level of Difficulty**: Medium

**Estimated Time**: 10 mins

**Instructions**
1. Review the Example System below.
2. For the simplified architecture above, identify:
    - Missing transparency components
    - Required data flows
    - Integration points for EU AI Act compliance
3. Draft up your response using a markdown file (i.e. Module3Exercise.md).
4. Once you've completed the above, submit your work to the [AI TA](https://chatgpt.com/g/g-67b5fb834f3c81919fabc4f3af4d7070-eu-ai-act-checker), that will review and provide you feedback.

*Note: Your submission with feedback and the conversation you have with the AI TA will be recorded as part of your completion.* 

-----
### Example System
Review this simplified architecture diagram and identify the: 
- Missing transparency components
- Required data flows
- Integration points for EU AI Act compliance

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

**Questions?** 
Ask the [AI TA](https://chatgpt.com/g/g-67b5fb834f3c81919fabc4f3af4d7070-eu-ai-act-checker). Make sure you specifify that you're working on the Systems Architecture and Transparency excercise before asking your questions.
