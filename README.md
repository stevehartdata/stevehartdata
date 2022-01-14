Hi, I'm Steve Hart! I am an independent software developer, specializing in using Haskell to build reliable systems in regulated environments. You can contact me at steve.hart@americandata.consulting!

I've been pretty busy working on projects for customers, but here's a little bit of what I've done recently:

* Designed and implemented a web application to help an S&P 500 manufacturer analyze the regulatory compliance of their products. The application performs sophisticated analysis to bring together chemical composition data about each of the component parts of the company's products in order to minimize the number of products that have to be sent to a lab for testing. The backend was originally written in Haskell and later ported to C#.

* Implemented [Docker View](https://dockerview.americandata.consulting) ([Haskell source code](https://github.com/stevehartdata/docker-view)), which helps visualize the contents of a Docker image, in greater detail than Docker Hub.

* Worked on a Haskell [web application](https://github.com/stevehartdata/sfdc) that provides Salesforce.com backups. (This is a work in progress.)

* Fixed bugs in and made improvements to:

  - An [Oracle Database driver](https://github.com/American-Data/takusen-oracle/commits?author=stevehartdata) for Haskell:

    + I implemented array binding and decimal numbers (Oracle NUMBER data type) in the course of a client project, but unfortunately these changes are not yet open source.
    + I'm working on simplifying the code, getting CI set up, and open sourcing the array binding functionality.

  - The SPICE [QXL display driver](https://github.com/stevehartdata/spice-qxl-wddm-dod/commit/1a07aa95f76975cce66cad49aee3652f8c3f33eb) for Windows. I fixed a bug in the driver that caused the cursor to be displayed in the wrong position if its hotspot was not in the upper left corner. While the fix was simple, tracking the root cause down to the driver through several layers of [SPICE](https://www.spice-space.org/) and [QEMU](https://www.qemu.org/) code was challenging.

* I'm currently working on implementing a dynamic programming algorithm to provide clear diffs for trees such as product bills of material.

