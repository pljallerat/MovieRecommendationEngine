MovieRecommendationEngine

#Setup

[..]

Step 4: sudo apt-get update && upgrade

Step 5: Install python 
sudo apt install python3 python3-pip ipython3
sudo apt install python3-pip
python3 --version

Step 6: Install Virtualenv 
sudo pip3 install virtualenv

Step 7: Create a new virtualenv 
virtualenv CS4337

Step 8: Activate this new virtualenv 
source CS4337/bin/activate

Step 9: Install Jupyter notebook 
pip install jupyter 

Step 10: Install Java JDK 8
sudo apt-get install openjdk-8-jre

Step 11: Install PySpark 
pip install pyspark

Step 12: Launch Jupyter notebook instance 
jupyter notebook --no-browser

Step 13: Set path variable for SPARK_HOME in the notebook 
%env SPARK_HOME = /home/sahir/cs4337/lib/python3.6/site-packages/pyspark

[If the above step doesn't work, try the following:]
export SPARK_HOME = /home/sahir/cs4337/lib/python3.6/site-packages/pyspark

Step 14: Install findspark to automate the process in future 
! pip install findspark