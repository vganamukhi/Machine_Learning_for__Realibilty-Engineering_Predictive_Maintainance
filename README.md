# Machine_Learning_for__Realibilty-Engineering_Predictive_Maintainance

Comapnies is gathering several types of data for its fleet of very expensive machines. 
These very expensive machines have three operating modes: normal, faulty and failed. 
The machines run all the time, and usually they are in normal mode. 
However, in the event that the machine enters faulty mode, the company would like to be aware of this as soon as possible. 
This way they can take preventative action to avoid entering failed mode and hopefully save themselves lots of money.

They collect four kinds of timeseries data for each machine in their fleet of very expensive machines. 
When a machine is operating in normal mode the data behaves in a fairly predictable way, but with a moderate amount of noise. 
Before a machine fails it will ramp into faulty mode, during which the data appears visibly quite different.
Finally, when a machine fails it enters a third, and distinctly different, failed mode where all signals are very close to 0.

You can download the data here: exampleco_data

Your objectives:

There are some clear outliers in the data due to communication errors from the sensor equipment. 
These bad measurements have no bearing on the problem you’re trying to solve, and a good place to start is to find a way to filter them out.
Develop an approach to detect the beginning of the “faulty” period, ideally giving the Company engineers as much time as possible to shut 
down their machines before failure occurs (at which time all measurements drop close to 0
