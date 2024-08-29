
# Face Swapping With Deep Fakes Methods

<div align="center">

</div>

## Installation
  
1. Clone this repository
  ```bash
  git clone https://github.com/saba99/Face_Swap.git
  cd Face_Swap

  ```
2. Install dependent packages
  ```bash
  pip install -r requirements.txt
  ```
  
3. Download weights
  ```bash
  sh download_models.sh
  ```

 ## Face Swap On Image

  ** Colab <a href="https://colab.research.google.com/drive/1pLyLbnBma9PiWioMxmyPBn-TWhkI6mqt"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="google colab logo"></a>
  
  You may set the target face, and then source will be swapped on this person, or you may skip this parameter, and then source will be swapped on any person in the image.
  ```bash
  python inference.py --target_path {PATH_TO_IMAGE} --image_to_image True
  ```
