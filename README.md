# How to run source
# 1. Install python: https://www.python.org/downloads/
<img width="1906" height="987" alt="image" src="https://github.com/user-attachments/assets/a68a2ef4-b25d-4040-bb66-3010dd225bd0" />

# 2. Open Terminal: ```Window -> Type Terminal -> Enter```
# 3. Clone repo: ```git clone https://github.com/tricaodev/crawl-data.git```
# 4. Go to working directory: ```cd crawl-data```
<img width="1097" height="255" alt="image" src="https://github.com/user-attachments/assets/d9a3f0bb-5f20-4ec8-beb4-e77f5bd6f5a0" />

# 5. Create virtual environment: ```python -m venv .venv```
# 6. Active virtual environment
* Window: ```./.venv/Scripts/activate```
* MacOS: ```source ./.venv/bin/activate```
<img width="1829" height="341" alt="image" src="https://github.com/user-attachments/assets/e9abb8cf-9973-4de4-8ca1-29585b1566a2" />

# 7. Install python package: ```pip install -r .\requirements.txt```
<img width="1830" height="332" alt="image" src="https://github.com/user-attachments/assets/69ea5c49-c431-48ae-89c4-07455f6a3bc7" />

# 8. Run crawler:
* ```python main.py --page travis_perkins --mode retail``` -> Crawl data from Travis Perkins without login to get retail price
<img width="1827" height="342" alt="image" src="https://github.com/user-attachments/assets/c48f82b7-3498-4571-830c-cef7a6ffc64e" />

* ```python main.py --page travis_perkins --mode trade``` -> Login before crawl data from Travis Perkins to get trade price
<img width="1831" height="342" alt="image" src="https://github.com/user-attachments/assets/167038d1-713f-46c9-9932-d368d5e294df" />
