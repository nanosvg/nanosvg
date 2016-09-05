===
TODO
===
* Add documentation:
  - ports: [C#](https://github.com/thinksquirrel/nanosvg-csharp), [D](http://repo.or.cz/iv.d.git/blob_plain/HEAD:/nanovg/svg.d)
* Address outstanding issues at https://github.com/memononen/nanosvg/issues
* Address outstanding pull requests at https://github.com/memononen/nanosvg/pulls
* Add [support for styles ](https://github.com/memononen/nanosvg/pull/70)
* Add support for xlink'ed images (via [stb-image](https://github.com/nothings/stb/blob/master/stb_image.h) and [stb_image_resize](https://github.com/nothings/stb/blob/master/stb_image_resize.h)?)
* Add support for text ([stb_truetype](https://github.com/nothings/stb/blob/master/stb_truetype.h), [stb_easy_font](https://github.com/nothings/stb/blob/master/stb_easy_font.h) or simple [path based one](http://murga-linux.com/puppy/viewtopic.php?p=906923#906923))
* Add placeholders for other parts of the [SVG Tiny spec](https://www.w3.org/TR/SVGTiny12/)
* Additional rasterizer examples: X11, xcb, wayland, ... and [others](https://github.com/paulmecklenburg/svg2nc)
* Code cleanup and refactoring
* Benchmark, profile and optimize
  - compare to cairo+librsvg, libsvgtiny, svgandroid, Monkey-SVG, [MonkSVG](https://github.com/micahpearlman/MonkSVG), [SDL_svg](http://sourceforge.net/projects/sdlsvg/)(uses libsvg), [nvidia direct path rendering](https://developer.nvidia.com/nv-path-rendering)
