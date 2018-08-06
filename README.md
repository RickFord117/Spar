# python

This a Python cookbook that can be used within other provisioning projects. It installs Python, Python-pip, libncurses5 and libncursesw5.

To use it, include the name of the cookbook and the GitHub ssh link inside of a chef berksfile as the following example shows:

cookbook 'python', git: "git@github.com:RickFord117/Sparta_global_python.git"
