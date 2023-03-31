# HiPAS GridLAB-D Project Template

This is the HiPAS GridLAB-D project template for general purpose simulations. To start your own project do the following:

1. Create your project repository in a your GitHub account using this repository as a project template.
2. Modify the `setup.sh` file to include any installation and setup requirements for your project, including downloading data files.
3. Modify the `run.sh` file to run the `gridlabd` simulation as needed.
4. Go to the `Actions` tab to view the status of the run.
5. When the run is complete, click on the download the run, and download the `output` artifact. The results will be contained in the downloaded `output` folder.

# Pro-tips

## Changing the `gridlabd` version

You can select an alternate version of `gridlabd` by editing [.github/workflows/main.yml](.github/workflows/main.yml#L12) file and changing the `container` settings from the default `slacgismo/gridlabd:latest` to a different one available in DockerHub.  The latest development version is available using the image `slacgismo/gridlabd:develop`.  See [DockerHub images](https://hub.docker.com/repository/docker/slacgismo/gridlabd/general) for a list of all available version images you can use with GitHub. 
