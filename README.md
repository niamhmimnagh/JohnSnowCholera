## John Snow's 1854 Cholera Map

This repository contains a selection of georeferenced files that can be used to re-create and analyse John Snow's iconic map of the 1854 cholera outbreak in Soho, London. These files were developed to support research, visualisation, and educational purposes, offering insights into this historically significant epidemiological study.

### Background

John Snow's 1854 map is widely regarded as a foundational work in the field of public health and spatial epidemiology. By georeferencing the original map, these files make it possible to perform modern analyses and reproduce visualisations that connect geography to the outbreak's progression.

Details on the creation of these files, including the georeferencing process and the historical context, can be found in the accompanying blog post: https://simplifyingstats.wordpress.com/2024/12/28/geography-of-an-outbreak-georeferencing-snows-1854-map/

The original JPEG image used for the georeferencing process was sourced from the Wikipedia page on the 1854 Broad Street cholera outbreak (accessed 14 November 2024).

### Files Included

  * Snow_cholera_map: A georeferenced TIFF file created in QGIS, representing the base map of Soho in 1854.
  * cholera_cases: A file containing 317 georeferenced points for locations where one or more cholera-related deaths occurred. Each point includes:
    * Count: The number of deaths at the location.
    * Angle: The angle for graphical rotation to replicate the original map's bar visualisation.
  * pump_locations: A file with 13 georeferenced points indicating the locations of water pumps across Soho.

These files can be used for a range of purposes, including spatial analysis, epidemiological modeling, historical mapping, and visualisation of the 1854 cholera outbreak.


### Usage and Attribution

If you use this georeferenced data in your work, please provide appropriate credit. Proper attribution helps support the continued sharing of open data and acknowledges the effort behind its creation.


#### Citation Example:

Mimnagh, Niamh. "John Snow's 1854 Cholera Map: Georeferenced Data." GitHub repository, 2024. [https://github.com/niamhmimnagh/JohnSnowCholera]

Alternatively, in BibTeX format for academic use:

```
@misc{Mimnagh2024,
  author       = {Niamh Mimnagh},
  title        = {John Snow's 1854 Cholera Map: Georeferenced Data},
  year         = {2024},
  publisher    = {GitHub},
  url          = {https://github.com/niamhmimnagh/JohnSnowCholera}
}
```

### Contact

If you have any questions or would like to share how you've used this data, feel free to contact me via GitHub or leave a comment on the blog post linked above.

