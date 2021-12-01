## Dynamic Vehicle Redistribution and Online Price Incentives in Shared Mobility Systems
* TITS 2014
* Julius Pfrommer
### abstract
* idea: intelligent routing decisions for staff-based vehicle redistribution and real-time price incentives for customers
* framework: 
    - For customers, using model-based predictive control principles based on the current and predicted state of the system
    - For redistribution staff, using model-based heuristic periodically recomputed routing directions in parallel.
- contributions
    - A tailored routing algorithm that plans how trucks will be used to redistribute bicycles among stations. Redistribution is performed in the dynamic setting, i.e., while the system is in operation. The heuristic chooses the actions of multiple trucks, with the aim of enabling as many extra journeys as possible to take place.
    - A dynamic incentives scheme where customers are encouraged to change their target station in exchange for a payment. Changes to journey length may be inconvenient, and we assume customers accept or reject such incentives based on the value of their time and the payment offered.
- goals
    - maximize the number of additional journeys enabled via redistribution, taking into account available resources and cost tradeoffs. 
* evaluation: 
    * applied to London's Barclays Cycle Hire scheme
- conclusions
    - it is possible to trade off reward payouts to customers against the cost of hiring staff to redistribute bicycles
### Mehtod
#### Derived Monte Carlo model of the London PBS using historical data

#### heuristice for determin the routes of redistribution trucks

#### model-based controller for computing the price incentives offered to customers

#### Monte Carlo simulation framework

### Evaluation

