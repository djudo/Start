# Logic App Tester

This client can be initialized with your Logic App Base URI and pull the key value from KeyVault, or you can paste it into the provided variable

The Until loop can be tuned with the Delay node and the number of loops before exit.  The test is meant to poll a logic app until the target app's key expires, so the until loop will exit when a non-200 status is observed.  The target logic app will lodge all requests to a storage account.
