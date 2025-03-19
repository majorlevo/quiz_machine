<!-- ABOUT THE PROJECT -->
## About The Project
This repository is for the 'Generative AI' class for Óbuda University

The goal of this project is to create a generative AI, which creates a quiz from a given source. The source can be a txt file, or a pdf file. 


### Installation


1. Get a free API Key at [https://openrouter.ai/](https://openrouter.ai/)
2. Clone the repo
   ```sh
   git clone https://github.com/majorlevo/quiz_machine.git
   ```
3. Install requirements
   ```sh
   pip install -r requirements.txt
   ```
4. Enter your API in `env_params.py`
   ```js
   openrouter_api_key = '<YOUR_API_KEY_GOES_HERE>'
   ```
5. Change git remote url to avoid accidental pushes to base project
   ```sh
   git remote set-url origin github_username/repo_name
   git remote -v # confirm the changes
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

To use this project run the 'third_edit.ipynb' notebook. If you want to set the difficulty and number of the questions, set the parameters False, else leave them True.




## Group members:
    -Alexandra Mentes
    -Botond Bencsics
    -Levente Major

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [autoquizzer](https://github.com/anakin87/autoquizzer?tab=readme-ov-file)

