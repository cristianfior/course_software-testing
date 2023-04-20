# MODULE2: Initial strategies
### Based on Scenarios
A hybrid between script and exploratory tests. Leaving of a preexisting scenario, think and trace another ways.
- Add steps
- Remove steps
- Update steps
- Repeate steps
- Replace steps
- Execute the same but different

### Based on Feedback
Help to focus on critical/problematic points. Doesn't bring new scenarios but show where to find them.
- Density of reported errors
- Expert prioritization
- Scenario criticality
- Coverage

### Based on Techniques
- Equivalence class: Try to map a infinite group of possibilities into a finite subgroup, making it possible to test.
    - Concomitance of intervals.
- Limit value: tests the intersection of a feature value limits; lower limit and lower limit -1, upper limit and upper limit +1.
- Transition of states: should have finite states, to every state there will be some actions. It looks to the flow of the application.
- Decision tables: helps when want to combine few rules/scenarios in one, so its possible compare conditions to results
| SCENARIOS     | n   |
| ------------- | --- |
| Scenario Name | T/F |
| ------------- | --- |
| RESULTS       |     |
| ------------- | --- |
| Expected      | Y/N |

- Orthogonal array/Pairwise: when decision table is too big
