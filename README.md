# Flow Field implementation based on Eikonal Equation for Unity
### Socials
[Twitter](https://twitter.com/BJKgamedev) | [Youtube](https://www.youtube.com/channel/UCyfwnxacJqN3vBFI6vVj_8g)
### Showcase video
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/CfXa_U5K0lw/0.jpg)](https://www.youtube.com/watch?v=CfXa_U5K0lw)
### Description
Flow Field implementation based on Eikonal Equation.
- The directions are more accurate than on a regular Flow Field so the paths calculated are smooth instead of being "squarish".
- Calculates three values for each cell:
  - Flow direction
  - Current direction goal - position of the cell that the flow is directed towards.
  - Distance to destination - distance to the destination cell.
- Handles obstacles and the position closest to the destination cell without going through the obstacles.

### Performance
Time complexity: `O(width * height)`.

![Performance](https://i.imgur.com/0Bm6f3Y.png)