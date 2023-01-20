# pico-paint
Create 8x8 pixel art for pico-8 without using a mouse!

### Explanation from lexaloffle page -> https://www.lexaloffle.com/bbs/?tid=51270

This is my first completed cartridge, made for people who don't like clicking or want to try something new.

It allows you to paint, copy, and paste 8x8 pixel art into pico-8 games without requiring a mouse.

### Key shortcuts:
- arrow keys to move
- `x` to paint
- `c` + `up` or `down` to change active palette
- `c` + `left` to turn background col into active palette
- `c` + `right` to change font col or change move delay (depending on mode)
- `enter` for the other settings

Copying and pasting is not as efficient as i'd like because of the built-in limitations of writing to and reading from clipboard. Make sure to `ctrl-c` after pressing copy in menu,  and `ctrl-v` before you press paste in menu. try: `[gfx]080811111888ccccc888cbbbc888bbbccccccc9ccfffff9fffffff9fffffffffffff[/gfx]` without extra characters or it won't load.

Thanks to https://www.lexaloffle.com/bbs/?uid=44112 for the string insert function https://www.lexaloffle.com/bbs/?pid=116400#p
