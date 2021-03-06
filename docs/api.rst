Pypipegraph API
================

Core functionality
---------------------------
.. autofunction:: pypipegraph.new_pipegraph
.. autoclass:: pypipegraph.graph.Pipegraph
.. autofunction:: pypipegraph.graph.run_pipegraph

Jobs
------------------------------

Data loading jobs
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
.. autoclass:: pypipegraph.DataLoadingJob
.. autoclass:: pypipegraph.CachedDataLoadingJob
.. autoclass:: pypipegraph.AttributeLoadingJob
.. autoclass:: pypipegraph.CachedAttributeLoadingJob

File generating jobs
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
.. autoclass:: pypipegraph.FileGeneratingJob
.. autoclass:: pypipegraph.MultiFileGeneratingJob
.. autoclass:: pypipegraph.TempFileGeneratingJob
.. autoclass:: pypipegraph.PlotJob
.. autoclass:: pypipegraph.CombinedPlotJob

Invariant checking jobs
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
.. autoclass:: pypipegraph.FunctionInvariant
.. autoclass:: pypipegraph.FileTimeInvariant
.. autoclass:: pypipegraph.FileChecksumInvariant
.. autoclass:: pypipegraph.ParameterInvariant

Job graph modifiying jobs
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
.. autoclass:: pypipegraph.DependencyInjectionJob
.. autoclass:: pypipegraph.JobGeneratingJob


Exceptions:
------------------------------
A Pipegraph may throw the following exceptions:
.. autoclass:: pypipegraph.ppg_exceptions.PyPipeGraphError
.. autoclass:: pypipegraph.ppg_exceptions.CycleError
.. autoclass:: pypipegraph.ppg_exceptions.RuntimeError
.. autoclass:: pypipegraph.ppg_exceptions.RuntimeException
.. autoclass:: pypipegraph.ppg_exceptions.JobContractError
.. autoclass:: pypipegraph.ppg_exceptions.JobDiedException


Utility functions
------------------------------
.. autofunction:: pypipegraph.util.change_logging_port
.. autofunction:: pypipegraph.util.output_file_exists


