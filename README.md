# Talend Command Line Interface #
## Version: 1.3.0 ##
### Author: Thomas Bennett <tbennett@talend.com> ###

The executables in this repository where built to support the following systems
* Windows <tcli.exe>
* Mac <tcli>
* Linux/Unix <tcli>

The log4j.properties file needs be downloaded as well and placed in the same directory
as the executable that you choose.

The following parameters can be used with the executable

| Command  | Description |
| --- | --- |
| -h,--help  | show help
| -j,--job \<arg> | The Talend Cloud Job Name to Execute
| -r,--region \<arg> | Talend Cloud Region [AWS_USA_EAST, AWS_EMEA, AWS_APAC, AZURE_USA_WEST]
| -t,--token \<arg> | Talend Cloud Token
| -te,--tokenenv \<arg> | Talend Cloud Token in Environment Variable
| -w,--wait | Will block any other commands from executing until Talend job is completed
| -e,--environment \<arg> | The environment the job is in. If not used name will be `default`
| -cv,--contextvariables \<arg> | Context Variables to pass. EX: name1=value1;name2=value2
| -v,--version | Product Version




`
  tcli -t <TOKEN> -r AWS_USA_EAST -j myjob -e DEV -cv connection=conn1;state=GA -w
 `






### License
MIT - <http://www.opensource.org/licenses/mit-license.php

