### OpenCV: Open Source Computer Vision Library (Raspberry PI)

### Cross Compile for Raspberry Pi (~45m)
Build OpenCV for Raspberry Pi:

1. Use an i86 64-bit Ubuntu 12.04 machine for cross compiling
1. Open a command prompt at your build root
1. `git clone https://github.com/firepick1/opencv`
1. `cd opencv`
1. `git checkout dev`
1. `./build.pi`

Install OpenCV on Raspberry Pi, named "firepick":

1. `rcp release.pi/install/opencv.zip pi@firepick:opencv.zip`
1. `ssh pi@firepick`
1. `sudo unzip opencv.zip /usr/local`

#### Resources

* Homepage: <http://opencv.org>
* Docs: <http://docs.opencv.org>
* Q&A forum: <http://answers.opencv.org>
* Issue tracking: <http://code.opencv.org>

#### Contributing

Please read before starting work on a pull request: <http://code.opencv.org/projects/opencv/wiki/How_to_contribute>

Summary of guidelines:

* One pull request per issue;
* Choose the right base branch;
* Include tests and documentation;
* Clean up "oops" commits before submitting;
* Follow the coding style guide.

[![Donate OpenCV project](http://opencv.org/wp-content/uploads/2013/07/gittip1.png)](https://www.gittip.com/OpenCV/)
[![Donate OpenCV project](http://opencv.org/wp-content/uploads/2013/07/paypal-donate-button.png)](https://www.paypal.com/cgi-bin/webscr?item_name=Donation+to+OpenCV&cmd=_donations&business=accountant%40opencv.org)
