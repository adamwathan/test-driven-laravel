# Test Driven Laravel

## Structure

- Intro: Lies you might believe about testing
    + If I can't test my code in isolation, it's poorly designed

## Questions

- What's the very first test I should write for a new app?
- What's the right way to test Eloquent models?
    + Using a test database
        * SQLite in memory w/Migrations trait
        * Real MySQL instance w/DatabaseTransactions trait
    + Designing good factories
- When should I use a mock?
    + Commands vs Queries
    + Mocks vs Spies
- How do I test code that uses an external service?
- How do I test that things are wired up correctly?
    + eg. events are bound to right listeners

## Advice

- Don't worry too much about isolation
    + Tests might be slower, but slow tests are better than no tests
    + Integration tests are important, and they are probably the best place to start anyways
- 
