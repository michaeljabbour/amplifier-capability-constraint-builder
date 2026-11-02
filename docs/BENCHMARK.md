# Constraint-checker comparison boundary

`python3 scripts/functional_gate.py` exercises the retained checker with
fictional temporary constraints. Its mixed gold includes one authorized action
and one unauthorized action. Both constant-deny and constant-allow controls
must fail that same gold: zero illegal escapes alone must not reward deny-all.
An empty case set is not success. The existing boundary fixture checks a legal
read, a path escape and an unsupported write; invalid checker results fail.

These exposed software controls exercise metric sensitivity, not an unseen
security claim or a task-reward benchmark. Candidate Python is trusted local
code and is executed during import; this is not a sandbox. No tool dispatch,
provider call, user file mutation or policy installation occurs in this gate.

Before a real comparison, freeze the action/state contract, allowed-action
gold and legitimate/illegal task distribution, baseline predicate or policy
engine, resources and untouched confirmation cases. Report escape and false
rejection counts separately with their denominators and actual task completion.
Include a leave-alone authorized case, a malicious escape and a no-action stop.
Do not adjust gold after seeing a candidate fail.

Let the person choose one bounded constraint change from observed failures.
Use at most two rounds and preserve keep/revert reasons. Stop on goal,
regression, no meaningful movement, missing authority/resources or user exit.
No comparative superiority, human growth or general security result follows
from these local controls.
