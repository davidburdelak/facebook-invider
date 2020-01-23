# FACEBOOK INVIDER

## How these scripts work?

The code retrieves the list of buttons visible in the window, and then simulates a click for each of them. I emphasize that the script will be executed for all visible buttons, it means that the last few steps we need to repeat and scroll the window with invitations down to load new buttons, but it's still a big help.

## How to use?

1. Open window with inviding
2. Make a keyboard shortcut and go to "Console"
- Chrome: [Ctrl]+[Shift]+[I]
- Firefox: [Ctrl]+[Shift]+[K]
3. Enter the code below
4. Scroll down to load more buttons

#### Events

```
javascript:var inputs = document.getElementsByClassName('_1pu2');
for(var i=0;i<inputs.length;i++)
{ inputs[i].click(); }
```

#### Pages

```
javascript:var inputs = document.getElementsByClassName('_1pu2');
for(var i=0;i<inputs.length;i++)
{ inputs[i].click(); }
```
