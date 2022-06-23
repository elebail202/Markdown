# WORKSHOP

## MR IMAGING OF ARTICULAR CARTILAGE *(quantitative analysis)*

Different structure/composition of the tissue. The content is different, water content decrease in the deep of the cartilage.

### Osteoarthritis *(Victor)*

**Knee osteoarthritis** the most common cause of disability in older adults. In Europe, 35-40 millions suffer from osteoarthritis.

-> Progressive degeneration of extracellular matrix. Cartilage not able to ensure this sliding, pain, difficulty in doing normal daily activities.

One of the best methods for visualizing cartilage is `MRI`. Acquisitions often restricted to **qualitative measurement**. It is mostly subjective and doesn't tell you what is the degree of severity.

With `T2 mapping`, information on early tissue degeneration (before clinical sign, radios...). So quantitative MRI can be used to quantitatively measure changes in tissue.
For quantitative MRI, you need to repeat the experiment many times.  
There is very close correlation between T2 map and water content/collagen content/collagen orientation/proteoglycans/`cartilage degeneration`.  
`Longer values of T2` when it is degenerated. If you are in the highest T2 of a population, you have high risk.  

First thing we need to know when we analyze cartilage is to isolate your target issue (segmentate it). Indeed, synovial fluid has higher T2 than cartilage and than ligaments/tendons.  
Deep-Learning is a good method for segmentation.  
It is easier to distinguish a healthy knee than a osteoarthritis knee.

DATA *(dicom)* -> Open data, create database -> Preprocessing *(change contrast, correct artifacts, exclude images)* -> Annotation *(cartilage segmentation)* -> Analysis *(creation of maps)* -> Results. And then corrections if needed.


## MRI mapper *(Evelina)*

Custom matlab script for each study. Make sure same phenoma cam be applied.  
MRI have quite poor resolution. Images were selected manually, manually save each region. Click on each pixel and draw all the regions separately. It was too long with the calculations and all...  
So Mokkula started, manually drawing to split the different regions. Still the segmentation is rather manual.

Manual segmentation is the gold standart but it is really time-consuming and there is a limit of the work that can be achieve with this.

Quite few problems in manual segmentation. Need to be quite precise to have a good segmentation.  
How to co-register images ? Having a higher resolution. Not so that easy to find the regions between cartilage and synovial liquid.  

--- 

Mokkula has been used worldwide (USA, Germany, Sweden...).

Problems with Mokkula :

- Files structures, identify them because they have different names
- Developing it with Matlab, userinterface was the most painful task
- How to fix T1 mapping which is inverted

## Some datas *(Ian, repu tcheque)*

1.5T data.  
**Undo button would be nice !!!**

## *(Eetu)*

3T data.  
Showed worst data he had to manage with, difficult to decide where the surface of cartilage is. Hard to determine precisely.  
Motion on the images which can be corrected.

## *(vilkanto)*

3T data.  
Relaxation parameters in cartilage. Different results depending on the angle the sample is placed.  
He is using Aedes, not Mokkula (similar).  
Focus on a small rectangular region of cartilage instead of a whole segmentation.  

---

Mokkula has a dedicated segmentation for knees. Aedes is used for little segmentations when you want to focus on a little region (pixel by pixel). When you want to segmentate the whole knee, too long and complicated.

