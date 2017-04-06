ParaView Snap Package
=====================

Building
--------
This assumes you have a ParaView superbuild under the `paraview/` directory.

Then, simply run `snapcraft`.  If not installed (on Ubuntu) `sudo apt install
snapcraft`.

Installing
----------
`snap install paraview5`

Running
-------
The ParaView GUI can be run with `paraview`.  All other binaries can be called
with `paraview.[binary]`.  For example `paraview.pvbatch`.
