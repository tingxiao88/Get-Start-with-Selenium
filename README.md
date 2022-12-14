# Get-Start-with-Selenium
Welcome to the tutorial for selenium-python. \
In this tutorial, you will learn how to
 - Setup your python environment
 - Setup selenium
 - webscraping with selenium
 - Mimic a human user with selenium

<a name="Set_up_your_python_environment"></a>
# Page Navigation
 - [Setup your python environment](#Set_up_your_python_environment)
 - [Setup selenium](#Setup_Selenium)

# Set up your python environment
###  - [step 1 - follow this website to install anaconda](https://www.anaconda.com/distribution/)
###  - [step 2 - install PyCharm](https://www.jetbrains.com/pycharm/download/#section=windows)
###  - step 3 - create a anaconda environment
   - [Anaconda Cheatsheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)
   - Open Anaconda Prompt
```bash
conda create --name selenium python==3.9
```
![create_new_anaconda_env](./readme_assets/anaconda_create_env.png)

### step 4 - Check the list of environment
```bash
conda env list
```
![conda_env_list](./readme_assets/conda_env_list.png)

### step 5 - Activate the environment
```bash
conda activate selenium
```
![conda_activate_selenium](./readme_assets/conda_activate_selenium.png)

### step 6 - Install python packages
```bash
# run command line by line
pip install selenium
pip install numpy
pip install pandas
pip install beautifulsoup4
pip install lxml
pip install requests
pip install jupyter
```

### step 7 add conda environment to PyCharm
   - Open PyCharm -> Settings

![pycharm_settings](./readme_assets/pycharm_setting.png)
   
   - Open Project -> Project Interpreter

![pycharm_settings](./readme_assets/pycharm_setting_2.png)

   - Open the dropdown menu and select "Add" and choose selenium environment

![pycharm_settings](./readme_assets/pycharm_setting_3.png)

   - make sure the environment is selected in the project interpreter and click apply

![pycharm_settings](./readme_assets/pycharm_setting_4.png)

<a name="Setup_Selenium"></a>
# Page Navigation
 - [Setup your python environment](#Set_up_your_python_environment)
 - [Setup selenium](#Setup_Selenium)
# Setup Selenium

### step 1 - check chrome version
   - Open chrome -> click the three dots on the top right corner -> Help -> About Google Chrome

![chrome_version](./readme_assets/chrome_version.png)

### step 2 - download the webdriver with the same version as your chrome
   - [Click here to download the ChromeDriver](https://chromedriver.chromium.org/downloads)

![webdrive_download](./readme_assets/webdrive_download.png)

### step 3 - unzip and move the webdriver to your "C" drive

![c_drive](./readme_assets/c_drive.png)

Now you are ready to start your first selenium script