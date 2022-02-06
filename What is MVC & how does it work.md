>💡 Start your game dev journey by sharing with the world and start earning reward points. Outscal team will give a special surprise reward to those who successfully complete this #30DaysGameDevChallenge
>
>Log in to LinkedIn.
Create a post.
Share a short post that you are starting the second chapter of your game development journey with below hashtags.
Tag Outscal and your newly made connections in the post so the team will get notified every time. Use #30DaysGameDevChallenge and #outscal in the post. final step. Submit the LinkedIn post link via this form https://airtable.com/shrXGSkgf5NClpoIU
💡 In this chapter, you can create two submissions.
>
>submission = 50 points
submissions = 100 points
500 points = Outscal Branded T-shirt 👕
>
---

## What is MVC & how does it work

MVC design pattern introduces another abstraction layer that will help with the software planning, and also allow new programmers to navigate even in a bigger codebase. By splitting the thinking process into data, interface, and decisions, developers can reduce the number of source files that must be searched in order to add or fix functionality.

![](Images/1.png)

This design pattern separates code into three layers as the name suggests. 

- Model
    - job: stores game map, player and NPC data, game settings. Everything data.
    - is not aware of what Views or Controllers are looking at it.
    - can post and listen for events.
- View
    - job: draws on screen what the model represents.
    - is strongly aware of the model and its values.
    - can post and listen for events.
- Controller
    - job: taking keyboard and mouse input and posts matching events.
    - is strongly aware of the model and its values.
    - can post and listen for events.
- Events
    - job: coordinates messages between listeners.

![](Images/2.png)

This shows that even if the Controller does not know anything about the player's health, what level we are on, it still only catches key presses and sends out events to match.

Nor does the View care how the player is controlling our game. The View only cares about showing on screen the current model state. Since the View also listens to posted events, it will pick up mouse clicks and key presses that integrate into its widgets.

💡 🚀 **[Join Discord Server](https://discord.gg/J5zDscnzms) → Get your doubts solved by experts instantly**
