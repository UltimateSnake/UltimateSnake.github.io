# Help
Snake game is a simple and addictive puzzle game where players control a continuously growing snake, eating food to increase its length while avoiding collisions with itself or the walls.

## Control
![help_control.png](help_control.png)

## Custom Level
### File Location
`<installation directory>/CustomLevel/<your files>.txt`
### Format
<table>
<tr><td>**Symbol**</td><td>**Implication**</td>  </tr>
<tr><td>**`x,y`**</td><td>the position of the snake's head (0 ≤ x ≤ 40, 0 ≤ y ≤ 28).</td>  </tr>
<tr><td>**`len`**</td><td>the initial length of the snake.</td>  </tr>
<tr><td>**`speed`**</td><td>the base speed of the snake.</td>  </tr>
<tr><td>**`wrap`**</td><td>wrap mode (on/off).</td>  </tr>
<tr><td>**`block`**</td><td>block mode (on/off).</td>  </tr>
<tr><td>**`prus`**</td><td>pursuit mode (on/off).</td>  </tr>
<tr><td>**`#`**</td><td>block.</td>  </tr>
<tr><td>**`.`**</td><td>food.</td>   </tr>
</table>

![EverEdit_2wHUkRs4GM.png](EverEdit_2wHUkRs4GM.png)
## Theme
### File Location
`<installation directory>/res/themes.json`
### Format
The theme file is in JSON.
```text
{
name1:[[front-color],[back-color]],
name2:[[front-color],[back-color]],
}
```
### example
```json
{
    "Black-Green": [[40, 60, 20, 255],[90, 140, 40, 255]],
    "Green-Black": [[90, 140, 40, 255], [40, 60, 20, 255]],
    "Black-White": [[50, 50, 50, 255], [200, 200, 200, 255]],
    "White-Black": [[200, 200, 200, 255], [50, 50, 50, 255]],
    "Theme1": [[25, 60, 50, 255], [25, 202, 173, 255]],
    "Theme2": [[60, 25, 50, 255], [244, 96, 108, 255]],
    "Theme3": [[150, 60, 40, 255], [236, 173, 158, 255]],
    "Theme4": [[40, 65, 75, 255], [190, 231, 233, 255]],
}
```
