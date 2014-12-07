# ASCII Cube
> A simple ASCII-rendered rotating cube

This demo generates a simple rotationg 3d-cube that is rendered with ASCII
characters inside a `<pre>` tag.

## Example
You can find an example at a local tilde.club server:

http://palvelin.club/~jehna/

Here's an example output of the script:
<img src="http://i.imgur.com/Z2bHrVi.png" alt="example image">

## Additional info

Here are a few details:
- This scipt is 100% independent, does not require any graphic libraries to run
- Lines are drawn with an improved [Bresenham's line algorithm][bresenham]
- The "canvas" scales with the browser's widow, always centering the cube on refresh
- The script is mobile-friendly and runs well with iPhone
- There's an additional function for creating the attribution link at the end

## License
The work is licensed under MIT license

[bresenham]: http://en.wikipedia.org/wiki/Bresenham's_line_algorithm