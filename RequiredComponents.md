These components are required for a good systems modeling library:
* System component (root-level node of a System scene), connects its values to Flows
* Flows (module for systems which controls the rate at which values increase/decrease) - ABSTRACT
* * InFlow - only increases a value in a system
  * OutFlow - only decreases a value in a system
  * BiFlow - flows both ways
* FlowPath (module which takes an array of points and a sprite and sends sprites along the path at a specified flow rate)
* Feedback (module which modifies the flow rate of a flow module(s) based on some other information)
* * PositiveFeedback
  * NegativeFeedback
  * StabilizingFeedback
* iStateMachine (module which runs state behavior from iState Modules)
* iStateModules (modules which define a behavior for the state machine, have a priority for whether their behvaior is executed)
* iStateSystem (System module which connects to an iStateMachine and has iStateModules, chooses which iState's behavior to run based on the iState's priority)
 
These components are required as examples:
* Single-stock, single-flow system
* * Water puddle evaporating, no rian (outflow)
  * Room cooling/warming to room temperature (biflow)
  * New lake with no outlet (inflow)
* Single-stock renewable system (biflow)
* * Fish population w/ spawn and harvest
* Single-stock nonrenewable system (outflow)
* * Oil field w/ harvest
* Single-stock renewable system w/ feedback
* * Fish population w/ spawn and harvest, where spawn depends on population and harvest depends on profit (??)
* Single-stock nonrenewable system w/ feedback
* Animated FlowPath example
* iStateSystem example
