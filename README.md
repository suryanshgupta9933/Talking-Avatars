# Talking Avatars

## Installation
1. Clone the repository.
    ```bash
    git clone https://github.com/suryanshgupta9933/talking-avatar.git
    ```
2. Create a virtual environment.
    ```bash
    conda create -n talking-avatar python=3.8
    ```
3. Activate the virtual environment.
    ```bash
    conda activate talking-avatar
    ```
4. Install PyTorch.
    ```bash
    pip install torch==1.12.1+cu113 torchvision==0.13.1+cu113 torchaudio==0.12.1 --extra-index-url https://download.pytorch.org/whl/cu113
    ```
5. Install ffmpeg.
    ```bash
    conda install ffmpeg
    ```
6. Install the requirements.
    ```bash
    pip install -r requirements.txt
    ```
7. Download the pretrained models.
    ```bash
    bash scripts/download_models.sh
    ```
