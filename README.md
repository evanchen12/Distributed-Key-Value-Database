# Distributed-Key-Value-Database
# Approach --- 

# Challenges --- 
- There was a problem with the MID not matching in the initial get. The problem was seemly caused by using if to handle the different state the nodes can be in instead of elif.
- Key error when iteratting through uncommitted array,
- Changing between 2 leaders very oftenly,
# Design and features --- 
- 
# Testing --- 
For testing we use the test file in the configs folder. For looking at more intricate problems we had to use json.dumps since print had no effects
