Aaron Chiuwei
1. Within a Github action that runs whenver code is pushed, because it catches issues before changes are made to the main codebase.
2. No, because E2E tests are designed for testing user actions, not function outputs. Unit Tests would be better for function outputs.
3. Navigation mode analyzes initial page loading performance metrics, while snapshot mode examines the current state of a page. Navigation cannot analyze interactions after loading and snapshot cannot analyze analyze loading performance of JavaScript execution.
4. Based on the Lighthouse results, three things that could be improved is to properly size images, add a meta viewport tag, and reduce unused JavaScript.