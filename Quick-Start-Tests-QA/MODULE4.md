# Module 04: Analysis, modeling, implementation
### Analysis
1. Understanding about test alternatives
    - Not enough time for everything, so we...
    - Prioritize
2. Choose what test techniques use
    - How to resolve scenarios
    - Scenario, result of environment and situations
    - Techniques, see how many tests there are in the scenario and what's these tests are

### Modeling
- Designing or writing tests
    1. Modeling types
        - Logic
            - Fast, cheap, good for old teams
            - Bad for dispersed teams, running data is missing
        - Concrete
            - Specific of physical
            - Steps
            - Good for new teams or dispersed teams
            - Knowledge is manteined on the company
            - Slow, expensive
        - Data Driven
            - Data tables and tags
        - Keyword Driven
            - Keywords and Data tables
    2. Listing the tests, still without the steps

### Implementation
1. Test detailing
    - Write steps
        - Manual
        - Automated
2. Creation of test dough
    - Data set that includes the expected results
3. Environment preparations
    - Hardware
    - Software
    - Access
    - People

### Scenarios
1. Environment
    1. Development
        - Free to break it
        - Candidate releases
    2. Test
        - Complete tests
    3. Production
        - Use of customers and users
    4. Types
        - Physical
        - Virtualized, VMs and containers (Docker)
    5. Problems
        - DLL Hell
        - "Works on my pc"
2. Situations
    - Tests
    - Volume of Users and transactions
        - Day x Night
        - Week-days x Week-end
        - Seasonalities
        - Special dates, black friday, xmas, valentines and etc

### Test suit
- Tests cluster
- Execution sequence
- Pre-conditions
- Pre-requesites
- Risks
- Development sequence
    - Easier first
    - Highest risk first