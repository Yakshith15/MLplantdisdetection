DL project to detect various plant diseases by images

To run project follow commands:
git clone https://github.com/Yakshith15/PlamtDisDetection.git
cd app
pip install -r requirements.txt
streamlit run main.py

To dockerise the application run the following commands
docker build -t [imageName]:v.01
docker images # To check image created
docker run -p 80:80 [imageName]
