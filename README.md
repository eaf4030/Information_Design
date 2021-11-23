# demand

What is demand?
Share of passenger using ridehailing who goes from A to B at the hour of the day h.

Data?
each rider after setting the destination observes the price and decides to request the ride or not (Step one)
after the platform found the driver, the pick up time is shown to rider and she can decide to cancel or keep the ride (step two)

Model:
I create a two step model. In the first step, it models the binary choice of requesting or not and in the second step the binary choice of canceling or not.
Since i only observe the second choice, the data is endogenous and a simple binary choice model is bias.
