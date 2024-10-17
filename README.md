# Abstract
# A large population at Carnegie Mellon University consists of international students or domestic students who live far away, and must enroll in the university health insurance, the Highmark Health BCBS PPO Blue Plan. Being in an unfamiliar environment, these students struggle with finding doctors close to them that are also within their health insurance network. This project aims to provide the user, students who are enrolled in the Carnegie Mellon University health insurance, with a comprehensive list of in-network primary care physicians within a short walking or driving distance of their home. Utilizing technologies such as HTML, API, and CSV scraping, we compiled a list of PPO Blue providers within the zip codes closest to Carnegie Mellon University. The program will process the user’s inputted address and generate a list of primary care providers sorted by proximity, ensuring that students can easily access the healthcare they need. Additionally, users can also input the physical area of their ailment to get a recommendation on what relevant speciality doctors they may need to visit next. 

# User Instructions
# Download the file ‘PD2024.csv’. 
# Please make sure you are connected to the internet because the program will be accessing various web-based data sources. 
# Also, ensure that the Python library, geopy, is installed in the environment you’ll be running the code in. 
# Once you run the code, you will start by describing your issue. Issues should be described with one word for best results. The recommended input is the specific body part affected.
# Then, enter your Pittsburgh address in two parts.
# Street Address: Enter your complete street address with no abbreviations. 
# Zip-code: Enter your specific zip-code using the standard 5 number format. The program will raise an error if an incorrect zip-code is entered. 
