# PyLink Example

## Installation

You will need Python 3.8.10 and Poetry installed.

Create a new Poetry shell

```shell
poetry shell
```

Then, to install the libraries, run

```shell
poetry install --no-root
```

Once everything is installed, you can run Psychopy

```shell
poetry run psychopy
```

### EyeLink

You’ll need to download the Eyelink Developers Kit provided by SR Research. To do that, register an account [here](https://www.sr-support.com/).

Note that they moderate the accounts fairly heavily, so it may take 24 hrs+ for the registration to go though. Once you’re registered, you can download the developers kit API ( Windows, Linux, MacOS ). You’ll need that kit to be able to call Eyelink functions from within PsychoPy (otherwise you get an error about missing files). Registering also gives access to a support forum.

The link to the download page, once you have access:
<https://www.sr-research.com/support/thread-13.html>

## Description

Source code is inside `pylink_example/`.

`main.py` is a very simple EyeLink setup test script. Run it to make sure everything is working.

`stroop_task/` is a very simple task with Eyelink without PsychoPy.

`mri_demo/` is a mri demo task with Eyelink and PsychoPy.