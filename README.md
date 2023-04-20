<!-- TITLE AND SUBTITLE -->
<br />
<p align="center">
  <h1 align="center">Title</h1>
</p>
<p align="center">Subtitle </p>

<br />

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#run">Run</a></li>
    <li><a href="#project-organization">Project Organization</a></li>
  </ol>
</details>

<br />

<!-- ABOUT THE PROJECT -->

## About The Project

Project description.

<br />

<!-- INSTALLATION -->

## Installation

To get a local copy up and running follow these simple steps.

### Set up environment

```
conda env create -f environment.yml

conda activate environment_name
```

### Visual Studio Code

After running the code above in Terminal, you still have to select the environment in VSCode. Click `F1`, select `Python: Select Interpreter`, click `Enter` and select the one that has `environment_name` in brackets. If you don't see the environment in the list, reload VS Code.

<br />

<!-- RUN -->

## Run

Instructions on how to run the project to get the expected output.

<br />

<!-- PROJECT ORGANIZATION -->

## Project Organization

The project is composed of 2 main folders: the source code folder named `src` and the `data` folder containing raw, intermediate and final outputs.

<br />

This is the structured followed by this project

<pre><code>

├── README.md          <- The top-level README for developers using this project
├── data
│   ├── final          <- Final results and datasets
│   ├── intermediate   <- Intermediate datasets
│   └── raw            <- The original, immutable data dump
│
├── docs               <- Documents of interest for this project
│
├── src                <- Source code as Jupyter notebooks
│
├── environment.yml    <- YAML file to create conda environment to run the project
   
</code></pre>

<br />

<!-- BUILT WITH -->

## Built With

- [Python 3.11](https://www.python.org/)
- [Jupyter Notebook](https://jupyter.org/)
