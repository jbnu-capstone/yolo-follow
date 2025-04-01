### Setup and Requirements

First, clone the project from GitHub:

`git clone https://github.com/jbnu-capstone/yolo-follow.git`

Move to the cloned folder:

`cd page_turner`

In the cloned folder you will find an anaconda environment file which you should install using the following command:

`conda env create -f environment.yml`

This will also install the score following system from `https://github.com/CPJKU/cyolo_score_following`

Activate the environment:

`conda activate page_turner`

Finally, install the project in the activated environment:

`python setup.py develop --user`

### Check if everything works

To verify that everything is correctly set up, move to the `page_turner` directory and run the following command:

 ```python automatic_page_turner.py```
 
This opens a window with two buttons on the bottom. 
Clicking on `Start tracking...` will then open a dialog window that allows 
you to select different performances, scores and models. 
(The `#Pages` is intended for the live mode of the score to indicate 
how often a page should be turned by a physical page turner. 
Just keep it to 0 if you load the score from the disk.) 
Once everything is set, press the `ok` button to start tracking.

