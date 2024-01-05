# Welcome to Pixlise

### What is Pixlise?

Pixlise is a platform for analyzing spectroscopy data. Originally designed for use with data from the Pixl instrument
which flies on the Mars Rover Perseverance, but has been designed with other instruments in mind.

PIXLISE is live at https://www.pixlise.org

### What components are there?

There are a few different repositories in the Pixlise project which when combined make a full, cloud ready, spectroscopy platform.

#### Core

Pixlise Core contains the majority of the platform API and data processing code. Written in Golang and can be compiled for a number of operating systems along with Docker/Kubernetes integration.

#### Pixlise UI

The UI is the interface for the user and is a web based UI written in Angular JS and Typescript.

#### Piquant

Piquant is the engine that drives the quantification support within Pixlise.

#### Data Formats

A number of protobuf data formats to allow us to move data around the platform in a predefined structure.
