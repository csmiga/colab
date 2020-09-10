## Codev (Cloud Development Environment)
[//]: # (<img src="https://colab.research.google.com/img/colab_favicon.ico" height="60" width="60">)

Codev is a Jupyter Notebook, cloud development environment that includes CPU/GPU recognition, customized GIT, Google Drive connectivity, a "~/Projects" directory, Python virtual environments, Python Libraries, SSH terminal access via ngrok or Serveo, customized Vim, and more. The codev repository offers more than is expressed here, so if needed, fork this repository and customize to your requirements.

*Free Development Environment + Free Software = Opportunity*

### Contents

  * [Installation][installation]
  * [Creating a Jupyter Notebook][creating_a_jupyter_notebook]
  * [Usage][usage]
  * [Notes][notes]

### Installation

  * To install the Jupyter Notebooks application to Google Drive, log into your Google Drive account.
  * From the settings icon (gear) at the top right corner of the browser, select "Settings" from the pull down menu.
  * From the "Settings" window, select "Manage Apps" on the left, and choose "Connect more apps" at the top of the same screen.
  * At the "Connect apps to Drive" window, enter "Colab" in the "Search Apps" field.
  * Select "Google Colaboratory" application and install to Google Drive.
  * To verify installation is successful, go to Google Drive, and verify a "Colab Notebooks" directory exist.
 
### Creating a Jupyter Notebook

  * From the Google Drive, Colab Notebooks directory, create a Jupyter Notebook file by right mouse clicking over a blank area.
  * Select the Google Colaboratory application, and a new Jupyter Notebook file will open in the browser. Rename the file from "Untitled0.ipynb" to "codev-01.ipynb"
  * Copy ["codev-01.ipynb"](https://github.com/csmiga/codev/blob/master/codev-01.ipynb) code to the new Jupyter Notebook and save.
  * To save the file, go to the pull down menu and select "File" --> "Save"
  * Close the notebook by exiting the browser tab.

### Usage

  * From the Google Drive, Colab Notebooks directory, right mouse click on the "codev-01.ipynb" file. A pop-up window will appear.
  * From the pop-up window, select "Open with" --> "Google Colaboratory". A new tab will appear in the browser.
  * To start the CDE, run "codev-01.ipynb" by clicking on the open bracket "[ ]" or "(>)" at the top left corner of the first cell of this file.
  * Monitor the CDE build environment. A URL and prompt will apear for authorzation to your Google Drive account. 
  * The build proces takes a few minutes.
  * When the CDE build is complete, launch any of the following cells in the "codev-01.ipynb" notebook to gain SSH teminal access to your CDE.

### Notes

  * If PyTorch, Kaggle, ONNX, or some other Python Library is not loaded in this environment, review ~/Projects/requirements.txt after the virtual machine is built. The libraries may be commented out.
  * Python 3 is the default interpreter for Colab Jupyter Notebook.
  * Create an NGROK account at https://ngrok.com/ and obtain an authorization token to update the "ngrokAuthToken" variable in the "codev-01.ipynb" file. See "DEFINE USER ENVIRONMENT" in "codev-01.ipynb" for additional information.
  * All requirements are included except SSH authorized_keys, config, and id_rsa key files. See "SET UP SSH KEY AND CONFIGURATION FILES FOR USER" in "codev-01.ipynb" for additional information.
  * Local development from a Linux workstation is available via sshfs" and "google-drive-ocamlfuse". More information is available using a search engine such as Bing, DuckDuckGo, or Google.
  * GPU hardware acceleration is available in the Jupyter Notebook pull down menu. Go to "Edit" --> "Notebook settings".
  * In the "Notebook settings" window, select "GPU" at the "Hardware accelerator" pull down menu, and run<br/>
    "codev-01.ipynb" from a Jupyter Notebook from Google Drive.
  * CPU hardware acceleration is set by default.

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

  [installation]: <https://github.com/csmiga/codev/blob/master/README.md#installation>
  [creating_a_jupyter_notebook]: <https://github.com/csmiga/codev/blob/master/README.md#creating-a-jupyter-notebook>
  [usage]: <https://github.com/csmiga/codev/blob/master/README.md#usage>
  [notes]: <https://github.com/csmiga/codev/blob/master/README.md#notes>
