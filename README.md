# cifar100

<img src="https://github.com/Mukhriddin19980901/cifar100/blob/main/images/0_crGF5wBkzhcEu4Yv.jpg" width="700" height="500" />

Our output data is so large tha but we don't have enough data to train so that we need add some augmnetation data to multiply it. 



# Step - 1 . Downloading model

- First click the buttons *windows+R*  and type *cmd* in box below clone my model from github on the black window

       C:\>  git clone https://github.com/Mukhriddin19980901/cifar100.git

- Write this command on black window.
 
       C:\> cd cifar100
 
# Step - 2 .Creating virtual environment 

- You need to upgrade your pip command to create environment

       C:\cifar100>python.exe -m pip install --upgrade pip


- Here you need to install environment module and you can create  your virtual environment

       C:\cifar100>python -m venv pip install --user virtualenv
 
 - Give the name to the environmentyou can give any name instead *environment_name*)

       C:\cifar100>python -m venv environment_name

- Then you need to activate the environment

       C:\cifar100>environment_name\Scripts\activate.bat

- Install all required libraries from the *requirements.txt* file

      (environment_name) C:\cifar100> pip install -r requirements.txt

- Now you can work on jupyter notebook

      (environment_name) C:\cifar100>jupyter notebook


# Step - 3 . Coding
 
- Now you can see the code [here](https://github.com/Mukhriddin19980901/cifar100/blob/main/cifar100code.ipynb).The model was built on CNN.Here you can compare the flactuation of training accuracy and loss after every epoch.It took about 8 hours and 8 minutes 52 seconds to train data in 20 epochs


<img src="https://github.com/Mukhriddin19980901/cifar100/blob/main/images/cifar100accur.png" width="700" height="500" />


- As far as validation concerned the numbers are  , validation accuracy is **57 %**

- [Here]() is a notebook for  deploying the model 

🔴 ***If you find it useful give a star to this repo and follow me on [Kaggle](https://www.kaggle.com/muhriddinmalik) and [Linkedin](https://www.linkedin.com/in/mukhriddin-khaydarov-8a9729209?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3Bay%2BB1xqoRZKf2DcZnvkRVw%3D%3D)***

