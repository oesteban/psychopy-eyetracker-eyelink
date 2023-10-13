# psychopy-eyetracker-eyelink

Extension for PsychoPy which adds support for EyeLink
eyetrackers (via ioHub)

## Supported Devices

Installing this package alongside PsychoPy will enable support for the following 
devices:

* Supported EyeLink eye trackers
    
## Installing

Install this package with the following shell command:: 

    pip install git+https://github.com/oesteban/psychopy-eyetracker-eyelink.git

You may also use PsychoPy's builtin plugin/package manager to install this 
package.

## Usage

Once the package is installed, PsychoPy will automatically load it when started 
and the `psychopy.iohub.devices.eyetracker.hw.sr_research.eyelink` namespace will contain the
loaded objects.
