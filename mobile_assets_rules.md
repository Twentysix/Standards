# Follow these rules to have a happy mobile team.

We love the work you guys do, you make things look cool but the following would make our lives so much easier.

## 1 General rules
+ **1.1** Always deliver in png if we want jpg we can convert them.
+ **1.2** Trim as much transparency as possible.
+ **1.3** All files in a single directory with a descriptive name e.g. home\_button\_on@2x.png.
+ **1.4** We always want the same name for an individual asset e.g. don't put 'version_2' or 'final' in the filename if you make changes.
+ **1.5** Always view your work on a device to see how the end product will look.

## 2 Assets
+ **2.2** Assets should be designed **@2X** (designed at twice the size you want it to look).
+ **2.3** Asset dimensions should always be divisible by 2 (so that we can auto re-size them to **@1x**).
    + **2.3.1** We use a tool called to do this called ResourceHelper on OS X which is available on the apple@twentysix account and wouldn't be upset if you want to provide both sizes.
+ **2.4** Assets should be delivered with a filename in the format **@2x.png** so we don't have to rename them.
+ **2.5** Buttons should be a minimum of **40px * 40px** **(80px * 80px @2x)**
    + **2.5.1** You can get away with **30px** +  but **40px** will never cause problems.

## 3 Consistency
+ **3.1** If one button is **80 px * 80 px** the button next to it should also be the same and not **82 px * 82 px** with more transparency.
+ **3.2** The on version of a button should be the exact same dimensions as the off version so we dont have to move them about based on current state.
+ **3.3** We like numbers that are easy to remember e.g. divisible by 10.
+ **3.4** Be consistent with a naming convention.
    + **3.4.1** No spaces in filenames, replace with an underscore, filenames all lowercase.
    <code>button_name_on@2px.png. button_name_off@2px.png. button_name_disabled@2px.png.</code>
