### IoMT Connector for Azure and Microsoft Teams Patient App

When combining the [IoMT Connector for Azure](https://github.com/microsoft/iomt-fhir), Azure API for FHIR, 
and Microsoft Teams customers can enable multiple care solutions. Below is the conceptual architecture for enabling IoMT connector, FHIR and Microsoft Teams Patient App. We can even embed Power BI Dashbaords inside 
the Microsoft Teams client. For more information on embeding Power BI in Microsoft Team visit [here.](https://powerbi.microsoft.com/en-us/blog/power-bi-teams-up-with-microsoft-teams/)

#### IoMT Connector and Team Reference Architecture 

![IoMTtoTeamsConcept](./images/IoMT2TeamsConcept.jpg)

The IoMT FHIR Connector for Azure can ingest IoT data from most IoT devices or gateways regardless of location, data center or cloud. We do encourage the use of Azure IoT services to 
assist with device/gateway connectivity. 


![IoMTtoTeamsConceptwithIoTHub](./images/IoMT2TeamswithIoTHUB.jpg)


For some solutions, Azure IoT Central can be used in place of Azure IoT Hub. We will be using Azure IoT Central in the sandbox setup. 

Azure IoT Edge can be used in conjunction with IoT Hub to create an on-premise end point for devices and/or in-device connectivity. 

![IoMTtoTeamsConceptwithIoTEdge](./images/IoMT2TeamswithIoTEdge.jpg)

#### Steps to create sandbox environment
Steps for creating a demo environment coming soon.

In the meantime, check out [IoMT FHIR Connector for Azure sandbox.](https://github.com/microsoft/iomt-fhir/blob/master/docs/Sandbox.md) Setting this up is the first step in creating
 a sample solution so why not get started today?

## More Information
- [Azure API for FHIR](https://docs.microsoft.com/en-us/azure/healthcare-apis/)
- [Microsoft Health](https://azure.microsoft.com/en-us/industries/healthcare/)
- Blog: [Accelerate IoMT on FHIR with new Microsoft OSS Connector](https://azure.microsoft.com/en-us/blog/accelerate-iomt-on-fhir-with-new-microsoft-oss-connector/)
- IoMT Complete Reference Architecture: [IoMT Solution](./IoMTReferenceArchitecture.md)
- More [Health References](https://github.com/microsoft/health-references)
- [Microsoft Teams for Healthcare](https://docs.microsoft.com/en-us/microsoftteams/expand-teams-across-your-org/healthcare/teams-in-hc)

