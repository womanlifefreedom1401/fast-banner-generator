# fast-banner-generator [(راهنمای فارسی)](https://github.com/womanlifefreedom1401/fast-banner-generator/blob/main/%D8%B1%D8%A7%D9%87%D9%86%D9%85%D8%A7%DB%8C-%D9%81%D8%A7%D8%B1%D8%B3%DB%8C-%D9%86%D8%B3%D8%AE%D9%87%DB%B1-%D9%81%D8%B4%D8%B1%D8%AF%D9%87.pdf)
<p align="center">
  <img src="https://github.com/womanlifefreedom1401/fast-banner-generator/blob/main/sample/f8.png" width="400">
</p>

## Goal
To make banners for the protests ASAP.

## How to?
Run the notebook on Google Colab.

There are a limited number of parameters, by changing them, you can customize your banner:
1. `centerize` (boolean) : text to be aligned center or right
2. `baseFontSize` (float) : font size ; will be automatically changed if text is too long.
3. `isBbox` (boolean) : want a bounding-box around the text?
4. `textColor` (str or tuple) : color of the text
5. `boxColor` (str or tuple) : fill-color of the bounding-box
6. `offsetX` (int) : distance between first text line and right-side (if not centerized)
7. `offsetY` (int) : distance between first text line and top-side
8. `dY` (int) : vertical distance between other text lines

## Known issues
After upgrading Pillow (`! pip install Pillow --upgrade`) the runtime must be manually restarted.
