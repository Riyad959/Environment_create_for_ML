# Environment_create_for_ML

Environment creation guide for Machine Learning. Follow these steps to complete the setup

**Step 1:**
- Download and Install Anaconda from there [webside page.](https://www.anaconda.com/download/success)

**Step 2:**
- Open Anaconda applicatiooon and go to Environments option.

**Step 3:**
- Press create ```environment```
> [!TIP]
> You will find the option on the left hand side.

**Step 4:**
- Give a name to your environment and select ```python version 3.7.16```

**Step 5:**
- Run the environment and Open ```terminal```

**Step 6:**
- Run These command in the terminal to install ```tensorflow``` ```cuda toolkit``` ```NumPy``` & ```Keras```
######
        pip install tensorflow==2.6.0
######
        conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1.0
> [!IMPORTANT]
> Run this comand to verify if the gpu detected by the system.
######
        python -c "import tensorflow as tf; print(tf.config.list_physical_devices('GPU'))"
######
        pip install numpy==1.21.5
######
        pip install keras==2.6.0

Go to your IDE and test a code to verify it's working.

<p align="center">Happy Coding</p>

## Contact
GitHub [@riyad959](https://github.com/riyad959)


[![Mail Badge](https://img.shields.io/badge/riyadulislam959@gmail.com-c14438?style=for-the-badge&logo=Gmail&logoColor=white&link=riyadulislam959@gmail.com)](mailto:riyadulislam959@gmail.com)
<a href="https://discord.com/users/674847774046683157" target="_blank"><img src="https://img.shields.io/badge/riyad__959-7289DA?style=for-the-badge&logo=discord&logoColor=white" target="_blank"></a>
<a href="https://www.linkedin.com/in/riyadul-islam-11a18a28a" target="_blank"><img src="https://img.shields.io/badge/-Riyadul Islam-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
<a href="https://www.twitter.com/" target="_blank"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" target="_blank"></a>
<a href="https://www.youtube.com/@riyadsartbook" target="_blank"><img src="https://img.shields.io/badge/@riyadsartbook-FF0000?style=for-the-badge&logo=youtube&logoColor=white" target="_blank"></a>