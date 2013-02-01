# Follow these rules to have a happy mobile team.

We love the work you guys do, you make things look cool but the following would make our lives so much easier.

## General rules
+ Always deliver in png if we want jpg we can convert them.
+ Trim as much transparency as possible.
+ All files in a single directory with a descriptive name e.g. home\_button\_on@2x.png.
+ We always want the same name for an individual asset e.g. dont put version_2 or final in the filename if you make changes.
+ Always view your work on a device to see how the end product will look.

## Assets
+ Assets should be designed **@2X** (designed at twice the size you want it to look).
+ Asset dimensions should always be divisible by 2 (so that we can auto re-size them to **@1x**).
    + We use a tool called to do this called ResourceHelper on OS X which is available on the apple@twentysix account and wouldn't be upset if you want to provide both sizes.
+ Assets should be delivered with a filename in the format **@2x.png** so we don't have to rename them.
+ Buttons should be a minimum of **40px * 40px** **(80px * 80px @2x)**
    + You can get away with **30px + ** but **40px** will never cause problems.

## Consistency
+ If one button is **80 px * 80 px** the button next to it should also be the same and not **82 px * 82 px** with more transparency.
+ The on version of a button should be the exact same dimensions as the off version so we dont have to move them about based on current state.
+ We like numbers that are easy to remember e.g. divisible by 10.
+ Be consistent with a naming convention.
    + No spaces in filenames, replace with an underscore.
    + <notextile>button_name_on / button_name_off / button_name_disabled</notextile>
    + filenames all lowercase.
