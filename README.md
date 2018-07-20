# PythonIntro
Broad introduction to Python3, from basic Python to scientific modules.

This introduction will cover main aspects of Python, some of it's main libraries and functionalities, as well as scientific and plotting packages, and Jupyter Notebooks. We will begin from the basics of the language, assuming you have never seen it before, but also assuming you have had *some* programing experience.

Overview:

- [Python language](#intro_python)
    - Interpreted Modern Day Stuff
    - Installation (system package/Anaconda)
    - Python 3 vs 2
- [Jupyter Notebook (What is this thing I am looking at?)](#intro_notebook)
    - [Shortcuts!](#intro_shortcuts)
- [Variables and Collections](#intro_vac)
    - [Native Types and Dynamic Typing](#intro_ntdt)
    - [Everything is a class](#intro_eiac)
    - [Numbers](#intro_numbers)
    - [Strings/bytes](#intro_strings)
        - Basic methods
    - [Lists](#intro_lists)
        - Indexing, slicing, negative indices
        - Basic methods
    - [Tuples](#intro_tuples)
    - [Sets](#intro_sets)
        - Basic methods
    - [Dictionaries](#intro_dictionaries)
        - Basic methods
    - [is vs. equals  (or, value vs. reference)](#intro_ive)
    - [None](#intro_none)
- [Control Flow](#intro_controlflow)
    - [Indentation and Scope](#intro_ias)
    - [If/Else](#intro_ifelse)
    - [For/While Loops](#intro_fwl)
        - Continue/Break/Else
    - [Try/Except](#intro_tryexcept)
- [Functions](#intro_functions)
    - [Def/Lambda](#intro_deflambda)
    - [Arguments (and default arguments )](#intro_arguments)
        - \*args and \*\*kwargs
    - [Comments and Doc-Strings](#intro_cads)
    - [Scope](#intro_scope)
- [Classes](#intro_classes)
    - [Encapsulation](#intro_encapsulation)
    - [Inheritance](#intro_inheritance)
    - [Polymorphism](#intro_polymorphism)
- [Iterators and Generators](#intro_iag)
    - [Comprehensions/range/map](#intro_crm)
- [Modules](#intro_modules)
    - [Import syntax](#intro_importsyntax)
    - [Install new modules](#intro_inm)
- [File IO](#intro_fio)
    - [open() and *with*](#intro_oaw)
    - [csv/Pickle/Json](#intro_cpj)
- [Virtual Environments](#intro_ve)
    - [python -m venv](#intro_pve)
    - [conda new](#intro_condanew)
- [Scientific Modules](#intro_scientificmodules)
    - [Numpy/Scipy and Matplotlib](#intro_nsm)
    - [Pandas](#intro_pandas)
        - Wide vs Long data formats: melting and casting
    - [Plotnine](#intro_plotnine)
    - [Cython and Numba](#intro_can)
    - [Mpi4Py](#intro_mpi4py)
- [Jupyter](#intro_jupyter)
    - [ipywidgets](#intro_ipywidgets)
- [Integrations](#intro_integrations)
    - [Magics](#intro_magics)
    - [pybind11](#intro_pybind11)
- [Sources and Aknowledgements](#intro_saa)
