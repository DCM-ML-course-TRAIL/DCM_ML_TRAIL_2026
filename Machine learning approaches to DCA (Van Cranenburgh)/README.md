## *Machine learning approaches for discrete choice analysis*
**Lecturer:** Dr. Sander van Cranenburgh

### Day 3 – Machine learning approaches for discrete choice analysis (Part 1) (Van Cranenburgh)
- Introduction to machine learning for choice modellers
- Artificial neural networks & Training
- [Lab session 3A](./Machine%20learning%20approaches%20to%20DCA%20(Van%20Cranenburgh)/Lab_sessions/Lab_session_03A) (Python notebook - neural networks for choice analysis)

### Day 4 – Machine learning approaches for discrete choice analysis (Part 2) (Van Cranenburgh)
- Utility-based machine learning models (a.k.a. hybrid models)
- The L-MNL model
- [Lab session 3B](./Lab_sessions/Lab_session_03B) (Python notebook - hybrid choice models)
<br><br>


# Instructions to set up your workspace for days 3 & 4
In this section, we will guide you through the configuration of your Python environment for days 3 and 4 of the course. You have to set up your environment once. This environment will work for all lab sessions.

### Setting up Python environment using Anaconda

Anaconda is a popular platform for managing Python environments. It is **strongly** recommended to create a **fresh** environment that uses Python version **3.12.11**. Other versions of Python, such as **3.10, 3.9 or  older**, are known to give some problems. Also, reusing an environment from another course is a recipe for installation troubles.

Step-by-Step Instructions:


#### A. Download the lab session files

1. **Go** to the top of this repository: [github.com/github.com/DCM-ML-course-TRAIL/DCM_ML_TRAIL_2026](https://github.com/DCM-ML-course-TRAIL/DCM_ML_TRAIL_2026)

2. **Download the materials**
   - Click the green Code button (top right of the file list)
   - In the dropdown, select Download ZIP
   ![img1](./Assets/A-2.png)

3. **Locate the ZIP file**
   - By default, the file will be saved in Downloads
   - The file is named: `DCM_ML_TRAIL_2026-main.zip`

4. **Copy to your course folder**
   - Open File Explorer in Windows (or Finder in Mac).
   - Move the ZIP file to a convenient location, e.g. Desktop or Documents.

5. **Unpack (extract) the ZIP**
   - Right-click the ZIP file → choose **Extract All...**
   - Inside the extracted folder you should see the subfolders **\Lab_sessions\lab_session_01**
      
#### B. Download the requirements.txt file into your Downloads folder 

1. **Go** to: [github.com/DCM-ML-course-TRAIL/DCM_ML_TRAIL_2026](https://github.com/DCM-ML-course-TRAIL/DCM_ML_TRAIL_2026)
   
2. In the file list, click on **requirements.txt**

   ![img2](./Assets/B-2.png)

3. On the top-right of the file view, click the **Download raw file** icon ()

   ![img3](./Assets/B-3.png)

4. The file will be saved to your **Downloads** folder 

5. Check in your **Downloads** folder to confirm the file is there.


#### C. Create an **empty** Python 3.12.11 environment

0. **Install Anaconda**: 
   - Go to the [Anaconda download page](https://docs.anaconda.com/anaconda/install/).
   - Choose the appropriate version and click Download.
   - Run the installer and follow the  instructions.

1. Open **Anaconda Navigator**, then Go to the **Environments**

2. Click **Create:** (bottom left) Do not reuse an old env!!
  
3. Enter a name for yoour environment (e.g., DCM_TRAIL_2026)

4. Tick **Python** and **select** version 3.12.11 from the dropdown

5. Click **Create** and wait (be patient)

   ![img4](./Assets/C-5.png)

**IF Python 3.12.11 is Not listed**

1. Open the command line terminal (cmd)

2. Type the following command and press Enter: 
   ```conda create -n py312 python=3.12.11```

   ![img5](./Assets/C2-2.png)

3. After installing, close and restart Anaconda Navigator

#### D. Install the required Python packages

1. In Anaconda Navigator, LEFT-click the green (image of button) button next to the environment name

2. Choose **Open Terminal**

3. In the terminal, go to your downloads folder by typing:
   ``cd Downloads``

   ![img6](./Assets/D-3.png) 

4. Install the required packages by typing:
   ``pip install –r requirements.txt``

5. Wait until the installation is finished (be patient)

6. Close the terminal


#### E. Install and launch Jupyter Notebook

1. Go to **Home** (top left)

2. In the dropdown at the top, select the created environment (e.g. DCM_TRAIL_2026)

   ![img7](./Assets/E-2.png) 

3. Scroll through the list or use the search bar to find Jupyter Notebook

4. Click **Install** (be patient)

5. When the installation is complete, the button will change from **Install** → **Launch**.

6. Click **Launch** to start Jupyter by double-clicking the launch button


#### F. Start your lab session

1. After launching **Jupyter Notebook**, a new browser tab will open automatically.

2. In the Jupyter file browser, **navigate to the course folder** where you unpacked the materials (e.g. Documents\Courses\DCM_TRAIL_2026\DCM_ML_TRAIL_2026-main\Lab_sessions).

3. Locate the lab notebook you want to work on (file ending in .ipynb).

4. **Double-click** the file to open it in a new tab.

5. You can now start running the notebook cells.

   ![img8](./Assets/F-4.png) 