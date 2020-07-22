# steinsgate-analysis
An analysis of the game assets used by the Steins Gate Visual Novel series.
## Backgrounds
The naming convention for backgrounds is shared across the entire VN series: `BG[0-1]+[AEN][0-1]*.PNG`. This means you can copy all the background images from all the games into a single directory.
- The first number, which ranges from 01 to 112, represents the scene - meaning a set location, from a set perspective.
- The letter represents the time of day. A = Afternoon, E = Evening, N = Night.
- The second number, if it exists, represents a variation of that scene - like images around Akihabara with and without people.
### Observations
- I mentioned that the backgrounds are shared. For example, Scene 01 represents the doorway to the Future Gadget Lab. Variations on that background from Steins Gate, Steins Gate: Linear Bounded Phenogram and Steins Gate Zero all use Scene 01. You'll see this quite nicely if you just copy them all into the same directory.
- Images around the same area tend to be grouped together. For example, Scenes 01-04 represent the interior of the Future Gadget Lab. But, this isn't a hard rule - Scene 05 and Scene 79 both show the exterior of the lab.
- The time of day attribute is required, even when it shouldn't matter - like an indoor place without any windows. This is mildly interesting because the game doesn't always tell you the time, so now you can figure it out.
