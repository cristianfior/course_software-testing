# MODULE1: INTRODUCTION
### Auto x Manual
- If talking about quantity: auto will be way better
- If talking about quality: manual will be slightly better
When talking about automated tests, the correct pyramid is: unit > services > e2e
Unit tests are the cheapest and fastest way to test a system and its prevents amounts of future failures. Therefore, when aiming to automate tests in a company or a system, the main focus should be on unit tests (despite many companies are making a bunch of e2e tests which bleed a lot of errors, that could be avoided if using unit tests).

### Script x Exploratory
- Script tests are like you're on a trip, and have a guide telling you where to go, when and what to do.
- Exploratory are like you're on a trip, but you're on your own, no one will tell you what to do, you have to seek and find.
| SCRIPTS                                     | EXPLORATORY                                                          |
| ------------------------------------------- | -------------------------------------------------------------------- |
| Executed following an script                | Executed with the defined purpose                                    |
| Defined steps                               | Only an initial direction                                            |
| Planning is made at scripts creation        | Planning is made during tests execution                              |
| "Take your time"                            | Time is predeterminated                                              |
| Prevent bugs                                | Found bugs                                                           |
| Can be automated                            | Can't be automated                                                   |
| Expected results are "Success" or "Failure" | Expected results are "Success" or "Failure", Doubts and observations |
| Existing features                           | New features                                                         |

### Test mass management
Environment(Entry + Action) = Result

### Planning
- Plan in advance
    - What, how, why?
    - As a/an... I want... So that...
- Create sessions with predetermined time
- Avoid distractions

1. Explore the feature/component/module
2. With some strategy/resource/condition
3. To discover certain information