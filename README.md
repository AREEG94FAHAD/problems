# problems
You have installed a new tracking system in your local shop. The system tracks every time a customer enters or exits the shop. Now you'd like to test if the system works correctly.

At the beginning and at the end of the day there are no customers in the shop. The system logs all the in and out movements of customers in a two-dimensional array of strings events, where events[i][0] is the unique id of the customer entering or exiting the shop, and events[i][1] is either "in" or "out", depending on the direction of movement of that customer.

Your task is to write a function solution(events), which returns true if the system may have worked correctly, and false otherwise.

Example

For

events = [
  ["John_0", "in"],
  ["Mary_0", "in"],
  ["John_0", "out"],
  ["Mary_0", "out"]
]
the output should be solution(events) = true.

For

events = [
  ["John_0", "in"],
  ["John_0", "in"],
  ["John_0", "out"],
  ["John_0", "out"]
]
the output should be solution(events) = false.

The same person cannot enter the shop twice without exiting.
