# bidirectional-buffer with non-inverting CMOS input
This project has files needed to design and implement GPIO

# steps to install NI Multism on windows:
1) Download NI Multisim 14.1 from https://softfamous.com/ni-multisim/download/
2) Click on `Download from ni.com -> GET STUDENT DOWNLOAD  ` 
<br/>
  <img align ="left" src="https://user-images.githubusercontent.com/66675990/84494289-d9744800-acc6-11ea-91a3-938bc8146741.JPG" width= "300" > 
 <img  src="https://user-images.githubusercontent.com/66675990/84496533-b9df1e80-acca-11ea-9606-0a4dd1d316c9.JPG" width="300" >
   <br/>  
        
3) Unzip the compressed folder and save in preferred folder.   <br/>     
4) Open `setup.exe` file and install.

**Note: NI Multisim can be downloaded only on windows OS. For MAC OS or LINUX users, Windows OS have to be installed using virtual machine or can use online MULTISIM LIVE https://www.multisim.com/

Unzip the compressed folder and save in preferred folder.
Open setup.exe file and install.
**Note: NI Multisim can be downloaded only on windows OS. For MAC OS or LINUX users, Windows OS have to be installed using virtual machine or can use online MULTISIM LIVE https://www.multisim.com/


# Getting started with simulation:
1) Go to place->component->all families->nmos to get the component NMOS
2) similarly import PMOS, inverter(NOT gate), digital clock to give inputs to both buffers connected in a bidirectional fashion
3) import digital constant which can be used as an enable pin connecting it directly to the source terminal of the PMOS
4) place 5 voltage probes (place->probe->voltage) as shown in the GPIO.ms14 file
5) CMOS inverter is constructed using a PMOS and an NMOS
6) Two CMOS inverters are connected to get a buffer which is non-inverting
7) Make a simulation of the GPIO circuit as shown and run it to get the output graphs
8) The graphs show us the characteristics of the GPIO pin which is used to select the input or output mode

# BRIEF DESCRIPTION OF GPIO (General Purpose Input/Output)
1) The GPIO pin is controlled by the user to get a desired mode of the whole chip
2) The input/output mode can be selected by giving the enable pin to logic high or low
3) The output and input buffers are formed by combining two CMOS inverters 
4) Both the buffers are connected in a bidirectional fashion which allows the data to flow either of the direction

# Contact information:
1) Nalla Gowthami, Electronics and instrumentation engineering, NIT Rourkela, gowthaminalla1821@gmail.com
2) Kunal Gosh Director, Vsd Corp Pvt.Ltd, kunalpgosh@gmail.com
3) Phillip Guhring, Software architect at Libresilicon Association pg@futureware.at
4) Dr.Gaurav Trivedi Co-principal investigator, EICT academy, and associative proffessor, EEE depatement, IIT Guwahati, trivedi@iitg.ac.in
