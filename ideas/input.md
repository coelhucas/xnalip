My goal is to handle input in a way that I can register multiple triggers (ex.: W key, DPAD-UP, Left Stick UP & Arrow-UP) in a same named/typed action that can be reused later.

Pseudo - not thinking about C# "practices" and stuff yet, need to read about it later
```cs
var MoveUp = Input.Register(Key.ArrowUp, Gamepad.DPAD_UP, Key.W, Mouse.LMB);

if (MoveUp.isPressed) {
    // do something
}

/*
 Additional usages I might add at some point
 Might be useful if I want to avoid conflicting at some point, but I could as well just let players press anything to switch between
 Controller/KB-Mouse
*/
MoveUp.disableGamepad();
MoveUp.disableKeyboard();
MoveUp.enableGamepad();
MoveUp.enableKeyboard();


```