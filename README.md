# Hovercraft
Mini linefollowing hovercraft for the Lockheed Martin Engineering Post

As a final project associated with my participation in the Lockheed Martin Aerospace 
Engineering Explorer Post my team and I were challenged to create an autonomous line 
following hovercraft able to support a .5 lb payload. I was largely in charge of the
coding of the device which presented a great challenge due to the high stakes and 
difficulties associated with hovered movement.

Major challenges:
Preventing drifting associated with preserved angular momentum
Selecting a sufficient power to hover while preserving control
Calibrating line sensing for hovering height changes

After extensive testing and advice from Lockheed engineers, I chose to persue a more
simplistic solution consisting of if else loops as apposed to my origional idea of 
PID line following.
