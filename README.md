# A versatile tool to rapidly process and analyze leaf photos

Leaf area is an important morphological metric than can be useful for comparing plants, phenotyping, understanding growth over time and for calculating things like ET, as examples. While measuring leaf area is a rather straightforward
process, it is also hands on and error prone using most techniques. To address this issue we have developed an image processing pipeline that allows users to take individual photos of the leaves for which an area is needed, then automatically extract leaf area from each image file. 

What once took days or weeks, now takes minutes or hours.

### Input
Directory with photo(s) of any leaf on reference paper

### Output
CSV data table containing ID info for each leaf and leaf area

## Recommended installation process

Clone the repository using `git`
   ```commandline
   git clone https://github.com/mattjenkins3/Automated-Leaf-Area-Detection.git
   ```
  Replace 'main' with any branch you'd like to clone.

## Using software
### 1. Create a virtual environment
  
  **Note**: first [Install virtualenv](https://virtualenv.pypa.io/en/latest/installation.html) if not already installed

Use the following commands to create a new virtual environment and then activate it:  


  ```commandline
  $ python3 -m venv myenv
  ```
This will create the virtual Python environment called `myenv`. Replace `myenv` with a different name if you prefer.

Activate the virtual environment called `myenv` using:
   
  ```commandline
  $ source myenv/bin/activate
  ```  
   
### 2. Install dependencies
     
  ```commandline
  (myenv) $ python -m pip install -r requirements.txt
  ```
### 3. Open a Jupyter notebook
   
  ```commandline
  (myenv) $ jupyter notebook
  ```
### 4. Start exploring the [Leaf Area Tool notebook](https://github.com/mattjenkins3/Automated-Leaf-Area-Detection/blob/main/leaf-area-tool.ipynb)
This tool allows users to process large batches of images quickly.

### 5. When you're done, don't forget to deactivate your virtual environment using
  ```commandline
  $ deactivate
  ```

## Requirements
- __Python 3.7__: There are many ways to install Python on your local machine, but we recommend downloading the official installer for your specific operating system, [directly from Python](https://www.python.org/downloads/).

## Citing this repository

To cite this repository:
```
@software{Leaf-Area-Tool,
  author = {Matthew Jenkins, Dylan Lenczewski-Jowers, Fabiola Chavez Lamas},
  title = {{Leaf Area Detect}: Automated Leaf Area Tool},
  url = {https://github.com/mattjenkins3/Automated-Leaf-Area-Detection.git},
  version = {0.1.0},
  year = {2022},
}
```
