# DynamicNumberVMandDataDisk
This template and parameter file will create a specified number of VM's and number of data disks per VM.  More information on parameter options can be found here http://www.ciraltos.com/dynamic-azure-arm-template-server-deployments/.

**Note - This template uses Azure Hybrid Benifits for licensing.  If you do not have Hybrid Benifits remove the line:
"licenseType": "Windows_Server",

Update 9/16/2018 -  Added Drive Encryption to the template http://www.ciraltos.com/?p=596&preview=true
                    Changed to Managed Disks
                    Added tags to the deployment