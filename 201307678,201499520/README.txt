Module Name: POS Tagging using Resource Rich languages
Name:Nirmal Surange(201499520) & Suman Dowlagar(201307678)


1- Requirements:
----------------
 Operating System               :       LINUX (tested on >= Ubuntu 10.04)

 Compiler/Interpreter/Librarie(s):      Java / Python

2- Directory Structure:
-----------------------

201307577
├── README
├── Report
├── Results
│   └── marathi_100sentences_Tagged.txt
│   
│   
└── code
    ├── bin
    │   ├── compile.sh
    │   ├── installib.sh
    │   └── run.sh
    ├── lib
    ├── Intermediate_Data
    └── src
	├──pre_TagRemove.py
	├──PMI_Dict.py
	├──Trig_Sim_Dict.py
	├──NbrCount.py
	├──Alignment_files_java(directory)
	├──RIs_QIs.py
	└──Tagg.py

9 directories, 2 input files, 12 program files (6 python files, 6 java files)               


3- How to run
---------------
   ---> bin - (bin folder contains 3 shell scripts (.sh files).)

        ---> sh installib.sh 
			If you are using any external libraries or libraries which are not included in the standard JAVA or Python libraries, this script installs the required 				libraries, for no such libraries, this file should be left blank (the libraries should be included in the 'lib' folder)

        ---> sh compile.sh 
			This file should contain the commands to compile your program. For Java, this script should contain 'javac program_name.java' for creating the class files, cc/			gcc for C. For Python, this script should be left blank.

        ---> sh POSTagging.sh input_file	(for pos tagging (using hindi and marathi parallel data))

			This should contain the commands to run your programs
				#####The output of the program should be displayed on the terminal#####
   ---> src - 
	
	This folder contains all programs to be run, this also contains the training model as well as the input files used for training
   
   ---> lib 
	
	this folder should is left blank.

