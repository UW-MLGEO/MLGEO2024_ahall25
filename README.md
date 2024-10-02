# Anna Hall's Repository for ESS569

This repository will house all of the code and data used for an introductory machine learning in geosciences class. The link to the repository can be found here: [Github](https://github.com/UW-MLGEO/MLGEO2024_ahall25)

### To install this repository:
1. Navigate to your directory of choice either directly in the JupyterHub interface or in your own terminal.
2. Paste the following script into the terminal and hit **enter**.
```bash
    git clone https://github.com/UW-MLGEO/MLGEO2024_ahall25.git
```
### 
When you clone the reopository, the command line output should look like the following screenshot. The repository will appear in the directory on the left hand side in the navigator sidebar.
  
<img src="CloneRepoScreenshot.png"/>

Now using the git commands is a bit tricky, follow the steps below for getting the environment.yml file from the JupyterHub interface to github.
1. Navigate to the directory that now houses the repo and move the environment.yml file to this directory.
2. Open a terminal shell in this directory and copy the following code
    ```bash
    git commit -m "Add environment.yml"
    ```
3. Now push the .yml file to github by copying the following code
   ```bash
    git push origin main
    ```
Should everything go okay, the terminal shell should look as follows:

<img src="GitAddScreenshot.png"/>

Note: The next screenshot shows what to do if things get hairy. If you update online in github, you need to do a **pull** on the main before you do a push.

<img src="GitCommandsScreenshot.png"/>

Note: You may need to generate a personal toaken, this can be done by navigating to the settings tab on github, then to developer settings (last option on the sidebar), and finally generate a token (you need to check the repo checkbox if you are generating one to be used within JupyterHub)

### To Run the Notebook
Go to the notebook in the cloned repository, you can now run the notebook, either by hitting **shift enter** or pressing run in the top navigation bar.
###

### My favorite Earth Science Topics are:
1. Satellites, specifically GNSS
2. Stratospheric Dynamics
3. the QBO (please see gif)
4. Lenticular Clouds
   
![Zonal Wind Anomaly](https://github.com/UW-MLGEO/MLGEO2024_ahall25/blob/main/qboGif.gif)

The MIT license offers a streamlined, highly permissive framework that encourages widespread use, modification, and sharing of your code, with the only stipulation being proper attribution—making it perfect for fostering innovation and broad community collaboration.

