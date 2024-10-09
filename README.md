# AI-Powered UI Design Assistant

This project aims to build an AI-powered tool that converts natural language descriptions into UI code (HTML). The goal is to streamline the UI design process by allowing developers to quickly generate code from simple commands.

## How to Contribute
1. Clone the repository.
2. Set up a virtual environment. (optional)
3. Install the required dependencies using `pip install -r requirements.txt`.
4. Create a new branch for your work.
5. Submit a pull request for review.

## Project Structure
- `model/`: Contains model-related code (training, inference, etc.)
- `data/`: Contains datasets for training and fine-tuning.
- `frontend/`: UI code for the web interface. (Optional)
- `scripts/`: Utility scripts for setup and data preprocessing.

## Setup Instructions
- Python version: 3.9+
- Install dependencies: `pip install -r requirements.txt`
- When adding new dependencies, do not forget to update the `requirements.txt` file using `pip freeze > requirements.txt`
- Set up Google Colab
  - Go to Google Colab and sign in with your Google account.
  - You can create a new notebook by selecting File > New notebook or by opening an existing one.
  - To leverage the GPU for faster model training and testing, click on Runtime > Change runtime type, in the dropdown for "Hardware accelerator," select GPU and click save.
  - Link your GitHub repository with Google Colab.

## Handling Datasets
- Large datasets: upload to Google Colab or Google drive. 
- Small datatsets: upload to the `data/` folder in the repo. 

## License
This project is licensed under MIT License.

