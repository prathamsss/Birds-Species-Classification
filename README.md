# Birds-Species-Classification
        Birds Species Classification using Keras pretrained model. (200 different species).

        Dataset link: http://www.vision.caltech.edu/visipedia/CUB-200-2011.html

        Before processing for training:
             1. Split the data into traning and validation as given in the split.txt file (0-validation and 1- texting). 
                Simply write a code for it. Finally dataset should be arranged in following way.
                
                
                 Arranged a data in following structure of directories:
                  Dataset--
                  1.--Train----
                  
                  --Class 1	  --img1
                              --img2... so on

                  --Class 2   --img1
                    .         --img2...so on
                    .
                    .
                  --Class 200  --img1
                               --img2....so on


                  2.--Validation---
                  
                  --Class 1	  --img1
                              --img2....so on 

                  --Class 2  --img1
                    .         --img2
                    .
                  --Class 200  --img1
                               --img2...so on
                               
           Now copy the path of training and validation and paste it accordingly in code.                    

    2. Or if you want also you can split by 70% Training, 30 % testing, by using keras Imagedatagenrator class. 
    
    
    Thank You!
    
   
    
