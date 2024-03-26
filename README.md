In this problem you, can simulate a simplified airport security system at a busy airport. Passengers arrive according to a Poisson distribution with λ1 = 5 per minute (i.e., mean interarrival rate 1 = 0.2 minutes) to the ID/boarding-pass check queue, where there are several servers who each have exponential service time with mean rate 0.75 minutes. [Hint: model them as one block that has more than one resource.]

After that, the passengers are assigned to the shortest of the several personal-check queues, where they go through the personal scanner (time is uniformly distributed between 0.5 minutes and 1 minute).
Use the Arena software (PC users) or Python with SimPy (PC or Mac users) to build a simulation of the
system, and then vary the number of ID/boarding-pass checkers and personal-check queues to determine
how many are needed to keep average wait times below 15 minutes. [If you’re using SimPy, or if you
have access to a non-student version of Arena, you can use λ1 = 50 to simulate a busier airport.]
