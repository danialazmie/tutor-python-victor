# Setting up the environment

## Anaconda3

- Download and install Anaconda3 [here](https://www.anaconda.com/download/success)

### Setting up virtual environments

- For Windows, search and run `Anaconda Prompt (Anaconda3)` program from Windows Search
```shell
(base) C:\Users\user> 
```
- Create a virtual environment `conda create --name <env-name> python=3.11.9`
- Once it's set up, activate the new environment `conda activate <env-name>`
- Execute `conda install anaconda` to install a set of libraries that are commonly used for Data Science
- You can run `jupyter lab` to see if it's working correctly.

## Visual Studio Code (Optional)

- You can also use VSCode as your integrated development environment (IDE) which is more intuitive and production-ready. You can download it [here](https://code.visualstudio.com/)

## Notes

- A virtual environment is an isolated Python environment that allows you to create a separate instance of Python with its own set of installed packages and dependencies.
- Example:
  - Environment A has Python 3.6, pandas v1.5.3
  - Environment B has Python 3.11, pandas v2.2.2, Matplotlib v3.5.3
- This is important as sometimes you'll find yourself working on projects with different requirements. Say you work on a legacy system that requires Python 2 with older libraries, and at the same time you need to work on an ongoing project using Python 3 with new libraries.
- This allows you to switch environments faster and avoid conflicts when working on different projects.
