## GSOC22 Final Report

This is the final report for GSOC 2022

`Project Name:` Improved ImageIO: adding JPEG2000, GIF, and EXIF support

`Organisation:` The Julia Language

`Project Size`: Large

### Project Summary:

JuliaImages takes support from JuliaIO to provide encode and decode methods of various image formats. The focus of this project is to add IO support for GIF and JPEG2000 formats. This project also aims to provide improved metadata EXIF support for the Julia community.

This project had 3 phases:
- ExifViewer.jl
- GIFImageIO.jl
- JPEG2000.jl

----

## Sub-Projects

The project consisted of 3 sub projects namely: EXIFViewer.jl, GIFImages.jl, JPEG2000.jl

### EXIFViewer.jl

Provides interface to use LibExif C library in Julia. Allows reading metadata from Images.

Project Link: https://github.com/ashwani-rathee/ExifViewer.jl

Pull Requests:
- https://github.com/ashwani-rathee/ExifViewer.jl/pull/1
- https://github.com/ashwani-rathee/ExifViewer.jl/pull/3
- https://github.com/ashwani-rathee/ExifViewer.jl/pull/6

### GIFImages.jl

Provides interface to use LibGIF C library in Julia.

Project Link: https://github.com/ashwani-rathee/GIFImages.jl

Pull Requests:
- https://github.com/ashwani-rathee/GIFImages.jl/pull/1
- https://github.com/ashwani-rathee/GIFImages.jl/pull/4
- https://github.com/ashwani-rathee/GIFImages.jl/pull/6

Color Quantisation methods were included

### JPEG2000.jl

Provides interface to use OpenJpeg C library in Julia.

Project Link: https://github.com/ashwani-rathee/JPEG2000.jl

Pull Requests: 
- https://github.com/ashwani-rathee/JPEG2000.jl/pull/1
- https://github.com/ashwani-rathee/JPEG2000.jl/pull/3
- https://github.com/ashwani-rathee/JPEG2000.jl/pull/4

Minor Projects:

### LibGifExtra
Provides extra functions written in C to improve perfomance and access of LibGif Library

Project Link: https://github.com/ashwani-rathee/libgifextra

Pull Requests:
- https://github.com/JuliaPackaging/Yggdrasil/pull/4882

### LibOpenJpegExtra

Provides extra functions written in C to improve perfomance and access of OpenJpeg Library

Project Link: https://github.com/ashwani-rathee/libopenjpegextra

Pull Requests:
- https://github.com/JuliaPackaging/Yggdrasil/pull/5173
- https://github.com/JuliaPackaging/Yggdrasil/pull/5643
