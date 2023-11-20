# Gender-Deploy

**Follow the steps to run the Website:**
1. Install virtual environment in the command pormpt >> pip install virtualenv
2. Make a virtual environment in the directory       >> python -m venv .venv      (Here the environment name is .venv)
3. Activate the environment                          >> .venv\Scripts\activate
4. Download and install the necessary files          >> pip install -r requirements.txt
5. Run the webNew.py file                            >> python webNew.py
6. Open the link provided by the code (localhost)
7. Now upload video or image of front face of a person And the website will detect the Gender of that image or video

**Follow the steps to run the API:** 
1. Install virtual environment in the command pormpt >> pip install virtualenv
2. Make a virtual environment in the directory       >> python -m venv .venv      (Here the environment name is .venv)
3. Activate the environment                          >> .venv\Scripts\activate
4. Download and install the necessary files          >> pip install -r requirements.txt
5. Run the gender.py file                            >> python gender.py
6. Go to postman and make a **post** request to the **url** provided by the code
7. Go to > body , Then > Form-data
8. Enter key -> file and select files(images or videos) as value
9. Now after sending the request the API will start working in the background and after few minutes(for videos) or seconds(for Images) the detcted result will be shown.
