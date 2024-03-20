# UCS505 Lab Assignments 
(Jan 2024)

## Overview ##

There are 5 assignments; contributing a total sum of 15
marks towards your Lab Evaluation.

### The Do's ###
+ A submission is admissible only using a thapar.edu
  account.
+ Candidates are encouraged to sensibly use external
  resources and duly acknowledge them using citations,
  *e.g.*  geometry definitions for a tranformation
  exercise.  Failure to cite an external resource shall
  be tantamount to plagiarism.
+ All assignments shall be submit as a link to your
  fork of the git repository.
+ In order to ensure the integrity of submission, the
  submission form shall contain a *Commit* field that
  matches the `git-commit` of the submission.
+ The deadlines are soft in the sense, that a delayed
  submission is admissible, albeit with a penalty of
  30% rounded away from zero.
+ Invariably all assignments would require to modify
  your name and roll number on `experiment.js`, /eg./
  ```javascript
  class Experiment {
    // Candidate Details
    static rollNo = '10983743'
    static name = 'The Tutor'

    // ...
  }
  ```
  And it shall reflect on the top right of your page
  like:
  
  ![](./assets/name-roll-example.png)
+ The top right of the canvas is overlaid with a
  download button for quick capture of the canvas.
  This is better than Canvas > Right-click > "Save to
  image..." in that the filename contains roll number
  and submission code by default.
+ The assignments with controls, the controls might
  have to be enabled inside `Experiment.constructor` as
  follows,
  ```javascript
  class Experiment {
    // ...
    constructor() {
      //...

      // Uncomment to enable tranform controls
      // --------------------------------------------------
      this.controls.unhide()

      //...
    }
  }
  ```
  This shall reveal the controls on the page.
  

### The Don'ts ###

A submission shall be rendered null and void, if
+ Submission format is not followed; or
+ Submit using a personal email id etc; or
+ Code is plagiarised; or
+ Use of uncited external resources.

## Schedule of Assignments ##

### 0x07 : 2D Primitives ###
[Problem
Statement](./0x07.md) |
[Boilerplate](https://github.com/tiet-ucs505/0x07-2d-primitives)
| [Submission Form](https://docs.google.com/forms/d/e/1FAIpQLSdmWJoYQzw2B_xgiqTSuYdEumigXqnRTr8fCIaA9ptPvf_KTQ/viewform?usp=pp_url&entry.1189318782=3CO6&entry.294246879=10210000&entry.117129202=Shakti+Mann&entry.1197422271=https://github.com/shaktimann000/)

|                  |                          |
|------------------|--------------------------|
| Code             | 0x07                     |
| Submission Opens | Wed 3 Apr 2024 17:00 hrs |
| Deadline         | Mon 8 Apr 2024 08:00 hrs |
| Weightage        | 3 marks                  |

### 0x08 : 2D Animation (Project) ###
[Problem
Statement](./0x08.md) |
[Boilerplate](https://github.com/tiet-ucs505/0x08-2d-animation-project)
| [First Submission Form](https://docs.google.com/forms/d/e/1FAIpQLSed6kxNCwgWZhej7wNamH5KpcSx03WXtDFQN0u1yLY7AaQ5sQ/viewform?usp=pp_url&entry.1189318782=3CO6&entry.294246879=10210000&entry.117129202=Shakti+Mann&entry.1197422271=https://github.com/shaktimann000/0x08) | [Second Submission Form](https://docs.google.com/forms/d/e/1FAIpQLSfqPOC6JAZbnGd6d7kflzy94OFvDiBj654cON969e5US9b0zg/viewform?usp=pp_url&entry.1189318782=3CO6&entry.294246879=10210000&entry.117129202=Shakti+Mann&entry.1197422271=https://github.com/shaktimann000/0x08)

|                         |                           |
|-------------------------|---------------------------|
| Code                    | 0x08                      |
| First Submission Opens  | Wed 10 Apr 2024 17:00 hrs |
| First Deadline          | Sat 13 Apr 2024 08:00 hrs |
| Second Submission Opens | Wed 10 Apr 2024 17:00 hrs |
| Second Deadline         | Mon 22 Apr 2024 08:00 hrs |
| Weightage               | 6 marks                   |


### 0x09 : 2D Line Clipping ###
[Problem
Statement](./0x09.md) |
[Boilerplate](https://github.com/tiet-ucs505/0x09-2d-line-clipping)
| [Submission Form](https://docs.google.com/forms/d/e/1FAIpQLSc1mmH9ZBhpvH3ajKFbpPpzgTcvZBBG3_vs6kzND-H5_q3E_Q/viewform?usp=pp_url&entry.1189318782=3CO6&entry.294246879=10210000&entry.117129202=Shakti+Mann&entry.1197422271=https://github.com/shaktimann000/0x09)

|                  |                                     |
|------------------|-------------------------------------|
| Code             | 0x09                                |
| Submission Opens | Fri 19 Apr 2024 17:00 hrs           |
| Deadline         | Thu 25 Apr 2024 08:00 hrs           |
| Weightage        | 2 marks                             |
| Remark           | 3CS6 to have an extra lab on 19-Apr |


### 0x0a : Rotating Colourful Cube ###
[Problem Statement](./0x0a.md) |
[Boilerplate](https://github.com/tiet-ucs505/0x0a-rotating-colourful-cube)
| [Submission Form](https://docs.google.com/forms/d/e/1FAIpQLScBTZfmCkCzzmxTJflvpqvf628hT3GuNwgTAytvYyUImJc-cQ/viewform?usp=pp_url&entry.1189318782=3CO6&entry.294246879=10210000&entry.117129202=Shakti+Mann&entry.1197422271=https://github.com/shaktimann000/0x0a)

|                  |                              |
|------------------|------------------------------|
| Code             | 0x0a                         |
| Submission Opens | Wed 24 Apr 2024 17:00 hrs    |
| Deadline         | Mon 29 Apr 2024 08:00 hrs    |
| Weightage        | 2 marks                      |

### 0x0b : Solar System ###
[Problem Statement](./0x0b.md) |
[Boilerplate](https://github.com/tiet-ucs505/0x0b-solar-system)
| [Submission Form](https://docs.google.com/forms/d/e/1FAIpQLScBFxf5qgidlS_tVjWKTiwuYZ7aP07lvE9CxHi5AYRfyWfhDw/viewform?usp=pp_url&entry.1189318782=3CO6&entry.294246879=10210000&entry.117129202=Shakti+Mann&entry.1197422271=https://github.com/shaktimann000/0x0b)

|                  |                             |
|------------------|-----------------------------|
| Code             | 0x0b                        |
| Submission Opens | Wed 1 May 2024 17:00 hrs    |
| Deadline         | Mon 6 May 2024 08:00 hrs    |
| Weightage        | 2 marks                     |

