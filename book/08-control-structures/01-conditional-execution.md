# Conditional Execution

One type of control structure involves `selection`, choosing what piece of code to execute based on a condition's true/false value. We can also describe this as `conditional execution`.

## A Mental Model

Let's imagine a real-world scenario. It's 10:45am on Tuesday and our class just wrapped up. You want to grab coffee before your next class.

Since we meet in DeBartolo, your closest option will be Duncan Student Center's Hagerty Cafe. But, lots of other people just got out of class and might also be on the hunt for coffee. Enter a condition you need to test for: `Can I get coffee from Hagerty Cafe before my next class?`

There are other contributing factors, but let's stick with a simplified underlying question.

If the answer is `yes`, you go to Hagerty and get coffee. If the answer is `no`, you're out of luck (or will need to try something else).

Let's say there's a long line at Hagerty- you won't be able to get coffee in time for your next class. The `no` answer to the initial condition might lead you to test a new condition: `Can I get coffee from O'Shaughnessy's Charron Family Commons before my next class?`

If Hagerty works, you'll never have to think about Charron. If Hagerty doesn't work, but Charron does, you're good to go! If Hagerty doesn't work AND Charron doesn't work, you might give up on coffee (or test similar conditions for other campus coffee locations).

The scenario we just walked through is an example of conditional execution. 

## Visual Representation

Let's represent this visually.

INITIAL SCENARIO FIGURE

Remember in our initial scenario, you aren't introducing additional conditions.

SECOND SCENARIO FIGURE 

In the second scenario, you're introducing an additional condition (based on the result of the first condition test).


