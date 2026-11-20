<div align="center">
    <p align="center">
        <a href="https://wikipedia.org/wiki/Scikit-learn">
          <img width="25%" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/Scikitlearn_logo.svg" />
        </a>
    </p>

# **`Awesome`** [Scikit-learn](https://scikit-learn.org/) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
</div>

[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)]()
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://www.reddit.com/r/scikit_learn/new/)

<p align="center">
    <a href="https://github.com/cybersecurity-dev/"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/github.svg" alt="GitHub"></a>
    &nbsp;
    <a href="https://www.youtube.com/@CyberThreatDefense"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/youtube.svg" alt="YouTube"></a>
    &nbsp;
    <a href="https://cyberthreatdefence.com/my_awesome_lists"><img height="20" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/blog.svg" alt="My Awesome Lists"></a>
    <img src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/bar.gif">
</p>

```mermaid
timeline
    title scikit-learn Development Timeline

    2007 : Project initiated by David Cournapeau
         : Google Summer of Code project
         : Matthieu Brucher contributes through his thesis

    2010 : Project leadership moves to the INRIA team
         : First public release on 1 February
         : Unified machine-learning API develops

    2011 : Scikit-learn paper published in JMLR
         : Wider adoption in scientific Python workflows

    2012–2014 : Classification and regression tools expand
              : Clustering algorithms improve
              : Model-selection functionality matures

    2015–2017 : Pipelines and preprocessing improve
              : Ensemble-learning methods expand
              : Documentation and examples grow

    2018–2020 : Version 0.20 to 0.23 series
              : Improved model inspection
              : Better preprocessing and estimator consistency

    2021 : Version 1.0 released
         : Major stable-version milestone
         : Stronger API consistency

    2022 : Version 1.1 released
         : Performance and usability improvements

    2023 : Versions 1.2 and 1.3 released
         : Initial metadata-routing capabilities
         : Improved dataframe integration

    2024 : Versions 1.4 and 1.5 released
         : Broader Polars support
         : Improved model-selection and visualization tools

    2025 : Versions 1.6, 1.7, and 1.8
         : Expanded metadata routing
         : Free-threaded CPython support in 1.8

    2026 : Version 1.9 series
         : Improved dataframe interoperability
         : Narwhals introduced as a dependency
         : Continued performance and compatibility improvements
```

## 📖 Contents
- [Installation Steps](#installation-steps)
- [My Awesome Lists](#my-awesome-lists)
- [Contributing](#contributing)
- [Contributors](#contributors)


## Installation Steps

* Linux
    * **`PIP`** 
      ```bash
        python3 -m venv sklearn-env
        source sklearn-env/bin/activate  # activate
        pip3 install -U scikit-learn
      ```
      In order to check your installation, you can use:
      ```bash
        python3 -m pip show scikit-learn  # show scikit-learn version and location
        python3 -m pip freeze             # show all installed packages in the environment
        python3 -c "import sklearn; sklearn.show_versions()"
      ```
    * **`CONDA`** 
      ```shell
        conda install conda-forge::scikit-learn   
      ```
      Intel optimized version
      ```shell
       conda install scikit-learn-intelex
      ```
* Windows
    * **`PIP`** 
      ```powershell
        python -m venv sklearn-env
        sklearn-env\Scripts\activate  # activate
        pip install -U scikit-learn
      ```
      In order to check your installation, you can use:
      ```powershell
        python -m pip show scikit-learn  # show scikit-learn version and location
        python -m pip freeze             # show all installed packages in the environment
        python -c "import sklearn; sklearn.show_versions()"
      ```
    * **`CONDA`**
      ```powershell
        conda install conda-forge::scikit-learn   
      ```
      Intel optimized version:
      ```powershell
        conda install scikit-learn-intelex
      ```

##

### My Awesome Lists
You can access the my awesome lists [here](https://cyberthreatdefence.com/my_awesome_lists)

### Contributing
[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors
[Thanks goes to these contributors](https://github.com/cybersecurity-dev/awesome-scikit-learn/graphs/contributors)!

### License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

[🔼 Back to top](#awesome-scikit-learn-)
