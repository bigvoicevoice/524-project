# 524-project
### Introduction
UW-Madison's campus press needs to distribute university newspapers (e.g. the Daily Cardinal) to major locations on campus. The circulation office can be built at university libraries for printing and delivering. Due to a limited budget, the press decides to find an economical way to do so.

Specifically, we need to decide locations of circulation offices and where to deliver for each of the office. We also need to devise appropriate delivery routes to minimize the total cost.

To make the scenario more realistic, we will consider different modes of transportation. In our example, bikes and cars are available for delivery, of which the cost and capacity are different. We allow for multiple delivery routes of a single facility.

### Overview of the approach
We formulate the problem as a two-stage optimization model. In the first stage, we consider the facility location problem to select libraries and assign them buildings to deliver to. Once we choose the library locations, we group the buildings into clusters according to the assignment, and solve the vehicle routing subproblem within each group.
