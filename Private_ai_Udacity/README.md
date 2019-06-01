# Secure and Private AI Scholarship Challenge - Udacity

Secure and Private AI Scholarship Challenge by Udacity and Facebook. This free course will introduce you to three cutting-edge technologies for privacy-preserving AI: Federated Learning, Differential Privacy, and Encrypted Computation. You will learn how to use the newest privacy-preserving technologies, such as OpenMined's PySyft. PySyft extends Deep Learning tools—such as PyTorch—with the cryptographic and distributed technologies necessary to safely and securely train AI models on distributed private data.

# Sections

## Deep Learning with Pytorch

Solutions are given in [Udacity_Pytorch_Scholarship.](../Udacity_Pytorch_Scholarship)

## Introducing Differential Privacy

### Getting Started

- Download [Anaconda](https://www.anaconda.com/distribution/)

- Run the following commands in bash/cmd:

    ```bash
    conda create -n pysyft python=3
    conda activate pysyft
    conda install jupyter notebook
    pip install syft
    pip install numpy
    ```

- If you have any errors relating to zstd - run the following (if everything above installed fine then skip this step):

    ```bash
    pip install --upgrade --force-reinstall zstd
    ```

and then retry installing syft (pip install syft).

- With this environment activated and in the repo directory, launch Jupyter Notebook:

    ```bash
    jupyter notebook
    ```
