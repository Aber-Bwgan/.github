# Urgent

- Load shape file of destinations
- Navigation to destination (might work but test)
- Manage destinations (random and charging station when battery low).  This needs to send goals to the navigation, monitor the navigation and send a new goal when the previous one is done, or cancel the current one and send the charging station as a goal if SoC goes low.
- The display of the low battery status needs to be done by the ESP if we want this to be resetable when the Pi shuts down (see "Less urgent").
- Launch file for navigation. Also look at order of starting and restart if failure 
- Reintroduce map clearing as a recovery strategy in the behaviour tree
- Build new robot
- Order oak pro cameras (can we move money from time to hardware?)

# Less urgent

- Shutdown pi while charging
- Look for birds? And use that as a goal.
