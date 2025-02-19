## Architecture Review Exercise
**Directions**
1. Review the Example System below.
2. For the simplified architecture above, identify:
  a. Missing transparency components
  b. Required data flows
  c. Integration points for EU AI Act compliance
3. Once you've completed the above, submit your code to the AI TA, that will review and provide you feedback.

   
### Example System
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


### Submission Directions
Submit your work for feedback here: https://chatgpt.com/g/g-67b5fb834f3c81919fabc4f3af4d7070-eu-ai-act-checker
Your submission with feedback and the conversation you have with the AI TA will be recorded as part of your completion. 

Remember: The EU AI Act specifies **what** transparency capabilities your architecture must support, but the **how** of implementation is flexible and should align with your organization's technical stack and practices.
