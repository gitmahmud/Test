# Test
By monitoring the frequency of your data transfers, and the amount of data transferred during each connection, you can identify areas of your application that can be made more battery-efficient. Generally, you should look for short spikes that can be delayed, or that should cause a later transfer to be pre-empted.

To better identify the cause of transfer spikes, the TrafficStats


LogCat is integrated into DDMS, and outputs the messages that you print out using the Log class along with other system messages such as stack traces when exceptions are thrown. View the Reading and Writing Log Messages. topic for more information on how to log messages to the LogCat.

When you have set up your logging, you can use the LogCat feature of DDMS to filter certain messages with the following buttons:

Verbose
Debug
Info
Warn
Error
