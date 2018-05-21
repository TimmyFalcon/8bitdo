# 8bitdo
An utility for 8bitdo sf30 pro on citra or others emulator.

This little program is made on c# with the SlimDx lib.

It will help you to bind click mouse on Controller (all button except joystick, Dinput mode for now).

The program will create a folder inside your "Documents" called "MouseGamepad".
Inside this one, you can create gameprofile for each game you want.

This is the list of buttons recognized :
  a, b, x, y, l, r, l2, r2, up, down, left, right
Then just put X,Y position and when you click on the assigned button it will click at the position.

This is an example of file:
left=1080,665
right=1080,670
up=900,900


Know Bugs or issue :
  -Do not recognize Xinput.
  -Can not manage more than one controller.
  -The program will pick the first controller that it find, so unplugged your controller that you don't need.
