# so much depends upon... your python app's dependencies

## Python Web Conference 2022
[Event Website](https://2023.pythonwebconf.com)


### Abstract

How do you keep track of your project’s building blocks? Is it enough just pinning your dependencies in a requirements.txt file? Or is there any reason to learn one (or any) in a myriad of dependency management tools?

_It depends._

Untangling the complexity of this topic might not be worth it for certain small projects. But there are a lot of reasons why learning about (and using) a dependency management tool will help you in the future.

Find out why embracing proper dependency management can help your project’s predictability, sustainability, security, and yes, even simplicity. Learn how you can use a tool like pdm to help accomplish these goals.

### Notes

[William Carlos Williams](https://www.poetryfoundation.org/poets/william-carlos-williams)

<p>so much depends<br>upon</p>
<p>a red wheel<br>barrow</p>
<p>glazed with rain<br>water</p>
<p>beside the white<br>chickens</p>

[Poet By Night (aka Python By Night)](https://www.pythonbynight.com)

<p>so much depends<br>upon</p>
<p>your requirements.txt<br>file</p>
<p>pinned with library<br>versions</p>
<p>beside your venv<br>folder</p>

- [Python Packaging Authority (PyPA)](https://packaging.python.org/)
- [Python Packing Index (PyPI)](https://pypi.org)

Requirements files serve as a list of items to be installed by pip. There is actually a specification for this. Read about it on the [pip documentation site](https://pip.pypa.io/en/stable/reference/requirements-file-format/).

- [pipdeptree](https://github.com/tox-dev/pipdeptree)
  - pipdeptree is a command line utility for displaying the installed python packages in form of a dependency tree.

Some package managers:

- [pip](https://pip.pypa.io/en/stable/)
  - pip is the package installer for Python. You can use it to install packages from the Python Package Index and other indexes.
- [conda](https://docs.conda.io/en/latest/)
  - Conda is an open source package management system and environment management system that runs on Windows, macOS, and Linux. Conda quickly installs, runs and updates packages and their dependencies.
- [poetry](https://python-poetry.org)
  - Poetry comes with all the tools you might need to manage your projects in a deterministic way.
- [hatch](https://hatch.pypa.io/latest/)
  - Hatch is a modern, extensible Python project manager.
- [pdm](https://pdm.fming.dev/latest/)
  - PDM, as described, is a modern Python package and dependency manager supporting the latest PEP standards.

Where do virtual environments come from? Bret Cannon [wrote a great blog post](https://snarky.ca/how-virtual-environments-work/) detailing its history in Python.

Incidentally, he has also [written about pyproject.toml](https://snarky.ca/what-the-heck-is-pyproject-toml/) and what it is for.

With pipx, you can install and run python applications in isolated environments. It's very useful if you have CLI applications that you use on all your projects. Instead of installing them every single time in each of those environments, you can isolate them with pipx. See more: https://pypa.github.io/pipx/

Python Enhancement Proposals (PEP)
- [What is a PEP?](https://peps.python.org/pep-0001/#what-is-a-pep)
- [PEP 517](https://peps.python.org/pep-0517/) – A build-system independent format for source trees
- [PEP 518](https://peps.python.org/pep-0518/) – Specifying Minimum Build System Requirements for Python Projects
- [PEP 609](https://peps.python.org/pep-0609/) – Python Packaging Authority (PyPA) Governance
- [PEP 621](https://peps.python.org/pep-0621/) – Storing project metadata in pyproject.toml
- [PEP 582](https://peps.python.org/pep-0582/) – Python local packages directory

### Other Resources

[Talk Python (Michael Kennedy) recently had Ofek Lev on the show](https://www.youtube.com/watch?v=gcgMyRfE8a4). He is the creator of [Hatch](https://hatch.pypa.io/latest/blog/2022/10/08/hatch-v160/). This is a good introduction to the tool. I highly recommend watching!

Pamela Anderson writes about [how she manages her Python dependencies for web projects](http://blog.pamelafox.org/2023/02/managing-python-dependency-versions-for.html).

Brett Cannon also talks about [classifying virtual environments](https://snarky.ca/classifying-python-virtual-environment-workflows/).

If you want a little bit more control over dependency management, and don't want to depend on the opinionated tools mentioned above, you could also use pip-tools. Gabriel Augendre writes about how to use [pip-tools for Python dependencies management](https://gabnotes.org/pip-tools-for-python-dependencies-management/).

[The Big List of Python Packaging and Distribution Tools](https://chadsmith.dev/python-packaging/) - A website that lists and describes a many, many tools around python packaging (including the ones mentioned here), maintained by Chad Smith.

Oh, and I guess I've written about [using PDM as a dependency manager](https://www.pythonbynight.com/blog/building-decorator-for-fastapi) too!

### Credits
- [Red Wheel Barrow image](https://www.flickr.com/photos/number7cloud/14403838611) - Flickr
- [William Carlos Willam](http://montagnevide.blogspot.com/2011/02/william-carlos-williams-poema-fenomeno.html) portrait
- [Guacamole](https://unsplash.com/photos/9ND-qkGs1_8) - Unsplash
- [Confused Pug](https://unsplash.com/photos/K4mSJ7kc0As) - Unsplash
- [Happy Dog](https://unsplash.com/photos/BVqQNu5J7qI) - Unsplash
