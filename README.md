# IMAGE RETRIEVAL WITH CLIP AND ChromaDB
## Description
This project illustrates the primary goal of image retrieval, which is to develop a system that can return relevant images from a predefined dataset based on an input query image. This involves finding and ranking images that are similar or related to the query image, enabling efficient and accurate retrieval from large-scale image datasets.

This project includes:

- Building a basic image retrieval program.
- Developing an advanced image retrieval program using the [CLIP](https://github.com/mlfoundations/open_clip) model and [ChromaDB](https://docs.trychroma.com/) vector database.
- (Optional) Collecting and processing data for the purpose of building a personalized image retrieval program from [flickr](https://www.flickr.com/).


## Installation

#### Running the Notebook on your computer

1. *Clone the repository:*
    ```sh
    git clone https://github.com/tranphuongtruc/IMAGE_RETRIEVAL_WITH_CLIP_AND_ChromaDB.git
    cd IMAGE_RETRIEVAL_WITH_CLIP_AND_ChromaDB
    ```

2. *(Optional)Create a virtual environment:*
   
    On Windows:
 
    ```sh
    python -m venv venv
    .\venv\Scripts\activate
    ```

    On macOS and Linux:

    ```sh
    python3 -m venv venv
    source venv/bin/activate
    ```

#### Running the Notebook on Google Colab

1. *Open Google Colab*

    Go to [Google Colab](https://colab.google/)

2. Upload Your Notebook

    Click on ***File*** -> ***Upload notebook***
    Choose the .ipynb file from your local machine.

3. *(optional) Mount Google Drive*

    If your notebook requires access to files stored in your Google Drive, you can mount it using the following code:

    ```sh
    from google.colab import drive
    drive.mount('/content/drive')
    ```
