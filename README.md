# Fruit Defects Inspection :camera: :apple:
## Computer Vision and Image Processing (IPCV) Exam

- Course: Computer Vision and Image Processing
- Professor: Luigi Di Stefano
- Student: Alessandro D'Amico

The task consists in locating and isolating defects in two kind of fruits (apples and kiwis) and is precisely described in the file ```tasks-description.pdf```.

The task is divided in 3 subtasks:

##  First task :apple:
  

<table style="padding:10px">
  <tr>
    <td> 
         <img src="./first task/src/C0_000001.png"  alt="1" width = 360px >
    </td>
    <td>
        <img src="./first task/src/C0_000002.png"  alt="1" width = 360px >
    </td>
    <td>
        <img src="./first task/src/C0_000003.png"  alt="1" width = 360px >
    </td>
    <td>
        <img src="./first task/src/C1_000001.png"  alt="1" width = 360px >
    </td>
    <td>
        <img src="./first task/src/C1_000002.png"  alt="1" width = 360px >
    </td>
    <td>
        <img src="./first task/src/C1_000003.png"  alt="1" width = 360px >
    </td>
  </tr>
</table>

Detecting defects in the apples building a pipeline that takes advantage of the strong edges of the defects (this subtask is mostly involving operations on binary and grayscale images).

## Second task :apple:
  
<table style="padding:10px">
  <tr>
    <td> 
         <img src="./second task/src/C0_000004.png"  alt="1" width = 360px >
    </td>
    <td>
        <img src="./second task/src/C0_000005.png"  alt="1" width = 360px >
    </td>
    <td>
        <img src="./second task/src/C1_000004.png"  alt="1" width = 360px >
    </td>
    <td>
        <img src="./second task/src/C1_000005.png"  alt="1" width = 360px >
    </td>
  </tr>
</table>
Detecting defects (russet) in the apples building a pipeline that takes advantage of the typical reddish color (this task is mostly involving operations on color images - color segmentation - but also operations on the binary mask as done in the first task).

## Final task :apple:
  
<table style="padding:10px">
  <tr>
    <td> 
         <img src="./final challenge/src/C0_000006.png"  alt="1" width = 360px >
    </td>
    <td>
        <img src="./final challenge/src/C0_000007.png"  alt="1" width = 360px >
    </td>
    <td>
        <img src="./final challenge/src/C0_000008.png"  alt="1" width = 360px >
    </td>
    <td>
        <img src="./final challenge/src/C0_000009.png"  alt="1" width = 360px >
    </td>
    <td>
        <img src="./final challenge/src/C0_000010.png"  alt="1" width = 360px >
    </td>
  </tr>
</table>
<table>
  <tr>
    <td> 
         <img src="./final challenge/src/C1_000006.png"  alt="1" width = 360px >
    </td>
    <td>
        <img src="./final challenge/src/C1_000007.png"  alt="1" width = 360px >
    </td>
    <td>
        <img src="./final challenge/src/C1_000008.png"  alt="1" width = 360px >
    </td>
    <td>
        <img src="./final challenge/src/C1_000009.png"  alt="1" width = 360px >
    </td>
    <td>
        <img src="./final challenge/src/C1_000010.png"  alt="1" width = 360px >
    </td>
  </tr>
</table>

Detect defects in kiwis using mostly the techniques described in the first task. 
  
In order to solve the subtasks, a mix of traditional IP and CV techniques has been applied in combination to my intuitive (handcrafted) ideas/function.


## Project structure
```
│   .gitattributes
│   tasks-description.pdf
│
├───.ipynb_checkpoints
│       tasks-description-checkpoint.pdf
│
├───final challenge
│   │   fruit inspection - ex3.ipynb
│   │
│   ├───.ipynb_checkpoints
│   │       fruit inspection - ex3-checkpoint.ipynb
│   │
│   └───src
│           C0_000006.png
│           C0_000007.png
│           C0_000008.png
│           C0_000009.png
│           C0_000010.png
│           C1_000006.png
│           C1_000007.png
│           C1_000008.png
│           C1_000009.png
│           C1_000010.png
│
├───first task
│   │   fruit inspection - ex1.ipynb
│   │
│   ├───.ipynb_checkpoints
│   │       fruit inspection - ex1-checkpoint.ipynb
│   │
│   └───src
│           C0_000001.png
│           C0_000002.png
│           C0_000003.png
│           C1_000001.png
│           C1_000002.png
│           C1_000003.png
│
├───other
│       gamma_correction.png
│       pipeline_ex1.png
│       pipeline_ex2.png
│       pipeline_ex3.png
│
└───second task
    │   fruit_inspection - ex2.ipynb
    │
    ├───.ipynb_checkpoints
    │       fruit_inspection - ex2-checkpoint.ipynb
    │
    └───src
            C0_000004.png
            C0_000005.png
            C1_000004.png
            C1_000005.png
```
