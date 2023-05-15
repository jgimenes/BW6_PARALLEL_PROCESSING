# TIBCO BusinessWorks 6 - Parallel Processing

<p>This proof of concept demonstrates how it is possible to execute multiple processes in parallel. In this example, the main process invokes the processes Service01, Service02, and Service03 simultaneously and waits for the completion of all three to finish the main process. Each of the executed subprocesses has a different execution time. The execution control is performed by the ExecutionControl process, which uses the Notify activity to inform the main process about the completion of execution.</p>
