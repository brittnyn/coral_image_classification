# Coral Image Classification
A CNN-based image classification model to accurately identify and monitor the health of coral reefs.

![coral reef](image.png)

## Problem
Coral reefs are vital to marine life: 
* Protects coastlines from weather damage
* Shelters at least 25% marine species
* Provide human resources for a plethora of industries.

Coral reefs are one of the most vulnerable ecosystems on Earth:
* Half of the world's coral reefs have died
* Coral bleaching occurs due to rising ocean temperatures and other environmental factors

## Challenges
* Manual identification of bleached and healthy corals is time-consuming 
* Requires specialized knowledge and continuous monitoring 

## Solution
CNN-based image classification model 
* Automates labor-intensive process with accurate classification
* Uses large dataset of labeled coral images for learning and training
* Produces a more efficient, consistent, and scalable approach

### Application:
* Large-scale, real-time coral reef monitoring 
* Underwater camera systems or aerial imagery


### Purpose:
* To assist marine researchers, biologists, and data scientists in identifying healthy and bleached corals based on distinct visual patterns. 
* To better understand the health of coral reefs, monitoring changes within ecosystems and contributing to the conservation & restoration strategies.
* To raise public awareness about the importance of coral reef ecosystems and the hardships they face.

<!-- Addition Visuals: TTYGIF or ASCIINEMA -->
# Installation
### Additional Notes
<!-- Programming language version, operating system, or dependencies that have to be installed manually -->
* At most Python `3.13` for compatibility with TensorFlow
* Using a virtual environment isolates program from global packages
* Run cells from top to bottom using a GPU accelerator
  
This is a VGG-19 classifier using TensorFlow
1. Clone the respository:
   ```bash
   git clone https://github.com/brittnyn/coral_image_classification
   cd your-repo
   ```

2. Create and activate a virtual environment (highly recommended):
    ```bash
    python -m venv .venv
    source .venv/bin/activate # Mac/Linux
    ```

    ```bash
    python -m venv .venv
    .venv\Scripts\activate # Windows 
    ```

3. Install the required packages
    ```bash
    pip install numpy pandas matplotlib opencv-python seaborn tensorflow tensorboard python-dotenv scikit-learn
    ```
4. Install kagglehub for access to kaggle dataset
    ```bash
    pip install kagglehub
    ```
5. Switch to Jupyter Kernel in VS Code (if needed)  
    a. Pip install `ipykernel` for Jupyter Notebook extension in VS Code  
    b. Open `.ipynb` notebook file inside VS Code  
    c. Select Kernel at the top-right corner of the editer  
    d. Select Python Environments $\rightarrow$ Choose environment labelled `.venv`  
    e. Or, select *Create python environment* $\rightarrow$ *Enter interpreter path* $\rightarrow$ *Manually browse for the path*


## Roadmap
<!-- Possible ideas for the future: -->
* Use a more modern model
* Expand curated dataset
* Use real-world examples from videos 
* Expand to visualized GUI
* Integrate with other marine technologies

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

