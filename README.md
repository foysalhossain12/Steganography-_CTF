--- Developing continue ---------

# 🔥 Steganography


![Header](https://user-images.githubusercontent.com/55437834/115628460-7ad61c80-a322-11eb-8095-a2bf03171db8.jpg)


Steganography is  process that is use for hiding  information inside of Image, audio , video or any digital object.That means  when you hide your informaton inside image or audio or video   , then send it to your destination  it's called steganograpghy   .

See detials Via Video :
                        https://youtu.be/Kxwzy2bJCqk
 
### Tools :
    
    steghide
    stegoveritas
    zsteg
    binwalk
    exiftool
    strings command
    stegsolver
    diit-1.5.jar
    formost
    sonic visualizer
    magic eye solver
    
    
### Steghide :
              steghide mainly use for extract or embeded file into .jpg file . But one can extract information from 
              audio / wav /mp3 file .
          
### Command :
             steghide extract -sf image.jpg
         
#### Note : Steghide don't extract .png format hide data 


### Stegoveritas :
                  stegoveritas ----comming soon
              
### Zsteg :
zsteg use for extract data from .pnd format image .It is so useful tools in CTF contest .
       
### Command :
         
zsteg image.png
         
### Diit-1.5.jar :
diit-1.5.jar is so important tools for CTF contest . When all process fail to solve steganograhy challenge it come .
It use algorithm for extract data from image file
     
#### Command :
              java -jar diit-1.5.jar
              
### Stegsolver :
             stegsolver is another important tools for ctf . It change color combination and expose data from image .
             
#### Command :
 java -jar  stegsolver
             
Then , Choose target image and change color combination . If color changes system don't expose data you must click on  analyse button then choose option one by one . 

#### Note : You can combine two magic image for getting information uing stegsolver


### Magic eye solver:
                 magic eye solver is onle tools which is similar tools like stegsolver .It is mainly use for magic image .
                 



#### How to solve Challenge of Steganography ?

Ok  , no problem . Follow the given below process >>

### 👀 Process for solving Steganography image  Challenges :

Step 1: check file type using  file command
:ey
Step2:use exiftool command 

Step3:use strings command

Step4:use steghide command if you have password for extract  otherwise use binwalk (But luckly you can try steghide without password)

Step5:zsteg tools 

Step6:open stegsolve.jar file using java –jar stegsolve.jar ( then  , try to use it according to its uses )

Step7:use magic eye solver 

Step8:use diit-1.5.jar and try to extract information 

### 😍 Process for solving Steganography wav  Challenges :

Step 1 :open  file and listen it .

Step 2 :If target audio file is morse code try to extract information using online morse code decode tools .If not , follow step 3

Step 3 :open sonic visualizer and try to extract information from it .

Step 4 : If above all step are failed . Try to extract data using  steghide as it has ability to extract audio file 


