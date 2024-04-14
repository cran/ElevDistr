## version 1.0.8

---

### Description file improvement

- Corrected a reference and added DOI.
- Replaced the "WGS 84" abbreviation with "World Geodetic System 1984".

### Examples

- Replaced 'dontrun{}' with 'donttest{}', where necessary.
- Added 'donttest{}' if data is downloaded or the execution time is to long.
- Removed unnecessary comments like: "Additional examples that are not executed because they take too long to run".

### README

- Updated the installation guideline in the "README.md"."

### Minor corections

-Corrected some typos.

## version 1.0.7

---

### Minor improvements

- Added DOI to a reference in the vignettes file.
- Replaced CRANE package links with a canonical form.
- Corrected a typo.
- Shortened three examples.

## version 1.0.6

---

### Bug fixes

- I fixed three errors that only appeared under Linux systems: the examples testing, the tests, and the ‘ElevDistr.Rmd’ built failed. All three errors were caused by a GDAL error, changing the option from ‘terra::rast’ solved the problem. This option pastes “/vsicurl/” before the URL and properly enables the GDAL virtual file system.


```
#Example old function call
gst <- terra::rast(gstURL)

#Example new function call
gst <- terra::rast(gstURL, vsi = TRUE)
```

## version 1.0.5

---

### Prepare CRANE upload

- Removed old rgdal dependencies.


## version 0.0.0.9000

---

### NEWS.md setup

- Added NEWS.md creation with [newsmd](https://github.com/Dschaykib/newsmd).

