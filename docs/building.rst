Building
========

Once you've installed `mint-dev-tools`, building Linux Mint projects from source is extremely easy.

Downloading the source code
---------------------------

Use `git clone` to get the source from github.

For instance, to get the source for mintinstall type:

.. code-block:: console

	cd ~/Sandbox
	git clone https://github.com/linuxmint/mintinstall.git


Building a project for the first time
-------------------------------------

Use `mint-build` to build a project for the first time.

`mint-build` doesn't just build the project, it also fetches and installs the build dependencies (i.e. the packages which are required for the build to succeed).

To build mintinstall you would type:

.. code-block:: console

	cd ~/Sandbox/mintinstall
	mint-build

When the build is complete, the resulting binary .deb packages are located in the parent directory (in this example in `~/Sandbox`).


Building a project
------------------

If all the build dependencies are already installed for a particular project (this is done by `mint-build` the first time you build a project), you can build faster by just calling `dpkg-buildpackage`.

To build mintinstall you would type:

.. code-block:: console

	cd ~/Sandbox/mintinstall
	dpkg-buildpackage

Respecting the build order
--------------------------

If new changes in the project you're trying to build require new changes in another project you might need to build and install that other project first.

In general it's a good idea to build `mint-common` and `xapps` first.
