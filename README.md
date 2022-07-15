# Tau short exercise for the 2022 USCMS Summer Intern

The Tau exercise is organised in two Jupyter notebooks, both contained in this repository.

To run the notebooks locally:
* Install [Python](https://www.python.org/downloads/), [ROOT](https://root.cern/install/) and [Jupyter](https://jupyter.org/install)
* Open a terminal and create a working directory
* Download the working package by `git clone https://github.com/Fengwangdong/uscms-summer-intern-tau-exercise.git`
* Enter the package by `cd uscms-summer-intern-tau-exercise`
* Download the input files from LPC node by `scp -r YOURLPCUSERNAME@cmslpc-sl7.fnal.gov:/uscms/home/zfwd666/nobackup/CMSDAS/uscmsintern/uscms-summer-intern-tau-exercise/inputFiles .`
* You're all set and can launch the two exercises locally, `jupyter-notebook tau_short_exercise_1.ipynb` and `jupyter-notebook tau_short_exercise_2.ipynb`, which will open the kernel in your browser

If you finished the exercise, it would be great to send your feedback to 
the author with the information whether you were able to successfully tackle the exercise and ideally also with pointers to finished notebooks, either linked on github, made available as exported websites or documents, etc. At the same time, I'd be very interested in getting specific feedback, suggestions, etc, so I can improve the exercise for future usage.

Note:
* The exercise can also be made to run with Python 2, but I use f-strings so it will require a few changes. Given the end of lifecycle of Python 2, I decided to not retain backwards compatibility.
* The software stack can be installed with brew and/or pip (root, jupyter, python3).
