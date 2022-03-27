# Ktech Site
Well functioning website build with django python's framework. it content blog and user interaction functionality.

<img src="./images/cover.png" width="1000" alt="photo cover" />

## Contents

1. Project Structure
2. Technologies and libraries
3. How to run
4. About Me

## 1. Project Structure

#### ktech_site
* ├── ....
* ├── ...

#### blog
* ├── ....
* ├── ....

#### media
* ├── images
    * ├── images asset
├── .gitignore
├── db.sqlite3
├── manage.py
├── README.md
├── requirements.txt

> **N.B :** db.sqlite3 file and media forder are automaticallygenerated once the server is run and was ignore in this repository for security.

## 2. Technologies and libraries

* django 4.0.3
* pillow
## 3. How to run

**N.B : python 3.8 is recommended**

### 3.1. CLONE PROJECT DIRECTORY

+ $ git clone https://github.com/RekidiangData-S/dj02_ktech_site.git
+ $ cd dj02_ktech_site

### 3.2. CREATE & ACTIVATE VIRTUAL ENVIRONMENT

#### 3.2.1. WITH PIP and VENV

##### (Windows) 
+ $ python -m venv dj02_venv 
+ $ dj02_venv\Scripts\activate (<= Activate virtual Environment)
+ $ deactivate (<= Deactivate virtual Environment)
+ $ pip install -r requirements.txt
+ Set  VIRTUAL ENVIRONMENT as KERNEL : 
  +  $ python -m ipykernel install --user --name dj02_venv --display-name "dj02_kernel"
+ $ jupyter notebook

##### (MasOS || LINUX)
+ $ python3 -m venv dj02_venv 
+ $ source dj02_venv/bin/activate (<= Activate virtual Environment)  
+ $ deactivate (<= Deactivate virtual Environment)
+ $ pip install -r requirements.txt
+ Set  VIRTUAL ENVIRONMENT as KERNEL : 
  +  $ python -m ipykernel install --user --name dj02_venv --display-name "dj02_kernel"
+ $ jupyter notebook


#### 3.2.2. WITH CONDA

+ Verify if you have conda installed ($conda --version) if not go to [anconda](https://www.anaconda.com/products/individual) or [miniconda](https://docs.conda.io/en/latest/miniconda.html) to download and install it

+ $ conda create -n dj02_venv python=3.8
+ $ conda activate dj02_venv (<= Activate virtual Environment)
+ $ conda deactivate  (<= Deactivate virtual Environment)
+ Set  VIRTUAL ENVIRONMENT as KERNEL : 
  +  $ python -m ipykernel install --user --name dj02_venv --display-name "dj02_kernel"
+ $ jupyter notebook
+ Go to Kernel -> Change kernel -> dj02_kernel
+ $ jupyter kernelspec list (<= list all ipykernel in your system)
+ $ jupyter kernelspec uninstall dj02_venv (<= Delete the ipykernel in your system)


#### Manage kernel
+ $ jupyter kernelspec list (<= list all ipykernel in your system)
+ $ jupyter kernelspec uninstall dj02_venv (<= Delete the ipykernel in your system)


## 4. About Me
___

### I'm Data Science Analyst, data and technology passionate person, Artificial Intelligence enthusiast, lifelong learner.

> My Website [Click Here](https://kiese.tech)

> Social Network

[![alt text][1.1]][1]
[![alt text][2.1]][2]
[![alt text][3.1]][3]
[![alt text][4.1]][4]

[1.1]: https://i.imgur.com/oFsAcMx.png (facebook icon with padding)
[2.1]: https://i.imgur.com/YCdR3o9.png (twitter icon with padding)
[3.1]: https://i.imgur.com/5BWvIrF.png (github icon with padding)
[4.1]: https://i.imgur.com/UA7Oh6z.png (medium icon with padding)

[1]: http://www.facebook.com/reagan.kiese.37
[2]: https://twitter.com/ReaganKiese
[3]: https://github.com/Rekidiang2
[4]: https://medium.com/@rkddatas


