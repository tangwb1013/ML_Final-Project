# ML_Final-Project
1. set up the development environment  
   mkdir self-driving  
   cd self-driving  
   virtualenv --no-site-packages venv  
   source venv/bin/activate  

   git clone https://github.com/tangwb1013/ML_Final-Project.git  

   pip install eventlet  
   pip install numpy  
   pip install python-socketio  
   pip install tensorflow==0.12.1  
   pip install pillow  
   pip install flask  
   pip install keras==1.1.0  
   pip install opencv-python  
   pip install matplotlib  
   pip install pandas  
   sudo apt-get install python3-tk  

2. train the model  

   python model.py  

3. run the model  

   python drive.py model.json  
