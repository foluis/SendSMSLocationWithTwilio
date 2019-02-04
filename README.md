# SendSMSLocationWithTwilio
Test Send SMS Location With Twilio

https://docs.microsoft.com/en-us/learn/modules/send-location-over-sms-using-azure-functions-twilio/

Don't forget to add local.settings.json to ImHere.Functions

{
  "IsEncrypted": false,
  "Values": {
    "AzureWebJobsStorage": "UseDevelopmentStorage=true",
    "FUNCTIONS_WORKER_RUNTIME": "dotnet",
    "TwilioAccountSid": "<YourTwilioAccountSid>",
    "TwilioAuthToken": "<YourTwilioAuthToken>"
  }
}

