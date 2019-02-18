# Images Optimization Environment

## Compressors

### JPEG Encoders

 - [JPEG Archive](https://github.com/danielgtaylor/jpeg-archive) - (which uses [MozJPEG](https://github.com/mozilla/mozjpeg) under the hood)
    > Needs MozJPEG, I did installed with `brew install mozjpeg` for OSX version.
- [Guetzli](https://github.com/google/guetzli) - is a JPEG encoder that aims for excellent compression density at high visual quality.
  > I did installed with `brew install guetzli` for OSX version.
- [MozJPEG](https://github.com/mozilla/mozjpeg) - MozJPEG reduces file sizes of JPEG images while retaining quality and compatibility with the vast majority of the world's deployed decoders.
  > The command to execute MozJPEG is `cjpeg`

### PNG Encoders

- [pngquant](https://pngquant.org/) - pngquant is a command-line utility and a library for lossy compression of PNG images.
  > I did installed with `brew install pngquant` for OSX version.
- [OptiPNG](http://optipng.sourceforge.net/) - is a PNG optimizer that recompresses image files to a smaller size, without losing any information.
  > I did installed with `brew install optipng` for OSX version.

### WebP Encoders

- [WebP](https://developers.google.com/speed/webp/) - is a modern image format that provides superior lossless and lossy compression for images on the web.
  > I did installed with `brew install webp` for OSX version.

 ## DevDependencies

  - [Ladon](https://github.com/danielgtaylor/ladon) - A small, simple utility to process many files in parallel.