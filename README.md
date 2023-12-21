# Face-Mask-Detector

# Step 1:
In the development of the Face Mask Detector project, the initial steps involve the utilization of the os module to facilitate seamless interaction with the operating system. This includes tasks such as file and directory creation, management, input/output operations, and process handling. Subsequently, the project leverages essential machine learning libraries, specifically tensorflow and keras, to enable the implementation of a robust face mask detection model.

# Step 2:
Given that the project aims to discern the presence or absence of masks on faces, a meticulously curated dataset comprising categorized images depicting individuals with and without masks is employed. Due to the limitations in Jupyter Notebook's capacity to directly import entire folders, a strategic approach involves compressing the dataset into a zip file, which is then uploaded to the notebook environment. To facilitate the extraction of the compressed file, the project incorporates the zipfile and shutil libraries.

# Step 3:
Continuing with the implementation, the opencv module is integrated for proficient image recognition. The subsequent phase involves the division of the dataset into training and testing sets, achieved through the utilization of the sklearn module. To enhance the model's predictive capabilities, the project integrates the VGG architecture.

# Step 4:
Following the preparatory steps, the model undergoes training, resulting in a remarkable achievement of 96% accuracy. This high level of accuracy attests to the efficacy of the implemented machine learning model in effectively discerning between masked and unmasked faces. The Face Mask Detector project thus stands as a testament to the seamless integration of advanced technologies and methodologies to address a pertinent real-world challenge.
