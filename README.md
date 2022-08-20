# EagleAirlines

The Eagle Airlines .xlsx sheet is an all-in-one report solution for the fictional company Eagle Airlines, which is trying to determine if they should buy another bushplane.  

Eagle Airlines considered the following variables before purchasing another plane: 
* Hours Flown (annual), as a total of ticketed and chartered flights.
* Charter Price per Hour
* Ticket Price per Hour for scheduled flights
* Seat Occupancy rate for scheduled flights
* Proportion of Cahrtered flights
* Operating Costs per Hour
* Annual Insurance
* Proportion of the buying cost financed
* Interest Rate
* Purchase Price 

Eagle Airlines provided me with base, expected values for these variables, as well as a lower and upper blound based on their previous flight experience. 

Explanation of each tab:
1. Title: Landing page with links to other tabs and last updated date.
2. Income Statement: This is an easily adjustable mock-income statement that Eagle Airlines can use after I'm long gone to estimate their profits.  By adjusting the blue cells, the conditionally formatted output in B27 compares against the opportunity cost of just investing the money rather than buying a plane.
3. Income Model: The income model works with the "full scenario table" to run a What-If Analysis: Data Table for every possible combination of input variables, up to a reasonable step-size.  Within "full scenario table," there are 59,049 considered possible outcomes.  Cells H4:I59052 look like they have no formula in them, but are actually inputting scenario numbers on the left into C3 and recording the output of C28.  We use this to determine the chance of profiting off the plane, assuming all input variables have a uniform chance to land anywhere along their expected ranges.
4. Best&Worst Case: This simply highlights the best, expected, and worst case scenarios for the purchase of a new plane.  Eagle Airlines can expect a return between -$54,950 and $86,763.
5. Sensitivity Analysis: The sensitivity analysis tab has what I consider the single most useful data in the entire report: The tornado chart.  The tornado chart lists the input variables in order of most impact to least impact.  If Eagle Airlines focuses on one thing and one thing alone, it needs to be occupancy percentage.  All other variables pale in comparison to occupancy.  
6. Break Even Analysis: This tab shows, per variable, how successful Eagle Airlines needs to be in order to come out ahead in purchasing the plane. 
