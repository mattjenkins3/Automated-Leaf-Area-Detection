# A versatile tool to rapidly process and analyze leaf photos

## This branch is dedicated to development of the bubble sheet feature
This feature allows users to fill out a bubble sheet before taking photos, allowing for enhanced automated image annotation.

For example, a four row, five option, bubble sheet can be included and users can describe the position of the harvested leaf using four parameters (e.g. height, orientation, or genotype), with five categorical options for each parameter.

Leaf area is an important morphological metric than can be useful for comparing plants, phenotyping, understanding growth over time and for calculating things like ET. While measuring leaf area is a rather straightforward
process, it is also hands on, time-consuming and error prone using modern techniques. To address this issue we have developed an image processing pipeline that allows researchers to take photos of all leaves for which an area is needed, then automatically calculate an accurate leaf area for all leaves. What once took days or weeks of manual labor, now takes minutes or hours.

__Input:__ Directory with photo(s) of any leaf on reference paper, with bubble annotation

__Output:__ Data table containing ID info for each leaf and leaf area

## Citing this repository

To cite this repository:
```
@software{Leaf-Area-Detect,
  author = {Matthew Jenkins, Dylan Lenczewski-Jowers, Fabiola Chavez Lamas},
  title = {{Leaf Area Detect}: Automated Leaf Area Tool},
  url = {https://github.com/mattjenkins3/Automated-Leaf-Area-Detection.git},
  version = {0.1.0},
  year = {2023},
}
```
