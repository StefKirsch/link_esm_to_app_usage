# Digital DNA: Link ESM participant data to their phone usage

## Setup

### I. Download the files and open in RStduio

> This assumes that you are using R and RStudio. For other IDEs, the workflow might be diffenrent

1. **Download a reasonably recent version of RStudio and R** if you haven't already.

2. **Navigate to the location of your choice** and **clone** this repository with 

```
git clone https://github.com/StefKirsch/link_esm_to_app_usage.git
```

3. Open the `.Rproj` file in the folder with **RStudio**

### II, Set Up the Environment with `renv`

This project uses `renv` for package management. Follow these steps to set up and restore the environment:

1. **Install `renv`** (if not already installed):
   ```r
   install.packages("renv")
   ```

2. **Restore the project environment** by running the following command in the R console from the project directory:
   ```r
   renv::restore()
   ```

   This will install all the packages required for the project as specified in the `renv.lock` file.
