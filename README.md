# M031BSP_I2C_NSP2340A
 M031BSP_I2C_NSP2340A

update @ 2023/05/30

1. update play list index and scenario

	by terminal , press digit Q , W , E to play wave file (however , NSP will entry power down after play finish , and data will lost)
	
	by terminal , press digit 1~9 , 0 to play wave file (NSP will not go into power down)

		- when under play index 6~9 , 0 wave file , press S/s , will stop playing immediately
	
	by terminal , press A or a , to increase volume and D or d , to decrease volume

2. pre programming wave file index in NSP2340A EVB by Nuvoton NSP PlayList Editor with NSP 1-1 Writer

3. Below file copy from Nuvoton NSP PlayList Editor folder

	nsp_driver.c , use PC0 as BP01(DATA) , PC1 as BP00(CLK)
	
	nsp_driver.h  ,
	
	nsp_PlaySample.c , 
	
	nsp_PlaySample.h 

4. under NSP_project folder is zip file of NSP project , include project file with 9 wave file (index from 1 ~ 10) 

	open project file by Nuvoton NSP PlayList Editor , wave file re-sample as 16000 Hz 

	refer NSP PlayList Editor Tool User Guilde.pdf

5. below is NSP2340A NSP_programming

![image](https://github.com/released/M031BSP_I2C_NSP2340A/blob/main/NSP_PlayList_Editor_Tool_1.jpg)

![image](https://github.com/released/M031BSP_I2C_NSP2340A/blob/main/NSP_PlayList_Editor_Tool_2.jpg)

6. below is screen capture about when press digit 

![image](https://github.com/released/M031BSP_I2C_NSP2340A/blob/main/log.jpg)

