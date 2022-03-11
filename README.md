# CustomRecorders
Custom Tcl Recorders for OpenSees

# How to use
Either copy the "CustomRecorders.tcl" file into your working directory and source directly, or place the repository folder within your Tcl library directory and include with "package require CustomRecorders".

# Note:
Since this implementation modifies the "analyze" command, breaking it into a for-loop that calls "analyze" for one step, it is incompatible the "VariableTransient" analysis type and the like. 

# Documentation
See the file "CustomRecorders.pdf".
