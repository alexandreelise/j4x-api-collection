# Joomla Web Services Collection For Postman
An attempt to help the Joomla! 4.x/5.x/6.x early adopters mainly focused for developers. It's an unofficial Postman collection of official Joomla Web Services Specification.


[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/7443864-c678a936-c256-497c-9894-d8f193d81e7e?action=collection%2Ffork&collection-url=entityId%3D7443864-c678a936-c256-497c-9894-d8f193d81e7e%26entityType%3Dcollection%26workspaceId%3D9797ebcb-675e-4cd4-913e-15a8e23036e0#?env%5BJoomla%204%20Web%20Services%20Environment%20For%20Postman%5D=W3sia2V5IjoiYmFzZV91cmwiLCJ2YWx1ZSI6Imh0dHBzOi8vZXhhbXBsZS5vcmciLCJlbmFibGVkIjp0cnVlLCJzZXNzaW9uVmFsdWUiOiJodHRwczovL2V4YW1wbGUub3JnIiwic2Vzc2lvbkluZGV4IjowfSx7ImtleSI6ImJhc2VfcGF0aCIsInZhbHVlIjoiYXBpL2luZGV4LnBocC92MSIsImVuYWJsZWQiOnRydWUsInNlc3Npb25WYWx1ZSI6ImFwaS9pbmRleC5waHAvdjEiLCJzZXNzaW9uSW5kZXgiOjF9LHsia2V5IjoiYXV0aF9hcGlrZXkiLCJ2YWx1ZSI6IllPVVJfSk9PTUxBNF9BUElfS0VZIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6InNlY3JldCIsInNlc3Npb25WYWx1ZSI6IllPVVJfSk9PTUxBNF9BUElfS0VZIiwic2Vzc2lvbkluZGV4IjoyfSx7ImtleSI6ImJhbm5lcl9pZCIsInZhbHVlIjoie2Jhbm5lcl9pZH0iLCJlbmFibGVkIjp0cnVlLCJzZXNzaW9uVmFsdWUiOiJ7YmFubmVyX2lkfSIsInNlc3Npb25JbmRleCI6M30seyJrZXkiOiJjbGllbnRfaWQiLCJ2YWx1ZSI6IntjbGllbnRfaWR9IiwiZW5hYmxlZCI6dHJ1ZSwic2Vzc2lvblZhbHVlIjoie2NsaWVudF9pZH0iLCJzZXNzaW9uSW5kZXgiOjR9LHsia2V5IjoiY2F0ZWdvcnlfaWQiLCJ2YWx1ZSI6IntjYXRlZ29yeV9pZH0iLCJlbmFibGVkIjp0cnVlLCJzZXNzaW9uVmFsdWUiOiJ7Y2F0ZWdvcnlfaWR9Iiwic2Vzc2lvbkluZGV4Ijo1fSx7ImtleSI6ImNvbnRlbnRoaXN0b3J5X2lkIiwidmFsdWUiOiJ7Y29udGVudGhpc3RvcnlfaWR9IiwiZW5hYmxlZCI6dHJ1ZSwic2Vzc2lvblZhbHVlIjoie2NvbnRlbnRoaXN0b3J5X2lkfSIsInNlc3Npb25JbmRleCI6Nn0seyJrZXkiOiJjb21wb25lbnRfbmFtZSIsInZhbHVlIjoie2NvbXBvbmVudF9uYW1lfSIsImVuYWJsZWQiOnRydWUsInNlc3Npb25WYWx1ZSI6Intjb21wb25lbnRfbmFtZX0iLCJzZXNzaW9uSW5kZXgiOjd9LHsia2V5IjoiY29udGFjdF9pZCIsInZhbHVlIjoie2NvbnRhY3RfaWR9IiwiZW5hYmxlZCI6dHJ1ZSwic2Vzc2lvblZhbHVlIjoie2NvbnRhY3RfaWR9Iiwic2Vzc2lvbkluZGV4Ijo4fSx7ImtleSI6ImZpZWxkX2lkIiwidmFsdWUiOiJ7ZmllbGRfaWR9IiwiZW5hYmxlZCI6dHJ1ZSwic2Vzc2lvblZhbHVlIjoie2ZpZWxkX2lkfSIsInNlc3Npb25JbmRleCI6OX0seyJrZXkiOiJncm91cF9pZCIsInZhbHVlIjoie2dyb3VwX2lkfSIsImVuYWJsZWQiOnRydWUsInNlc3Npb25WYWx1ZSI6Intncm91cF9pZH0iLCJzZXNzaW9uSW5kZXgiOjEwfSx7ImtleSI6ImFydGljbGVfaWQiLCJ2YWx1ZSI6InthcnRpY2xlX2lkfSIsImVuYWJsZWQiOnRydWUsInNlc3Npb25WYWx1ZSI6InthcnRpY2xlX2lkfSIsInNlc3Npb25JbmRleCI6MTF9LHsia2V5IjoibGFuZ3VhZ2VfaWQiLCJ2YWx1ZSI6IntsYW5ndWFnZV9pZH0iLCJlbmFibGVkIjp0cnVlLCJzZXNzaW9uVmFsdWUiOiJ7bGFuZ3VhZ2VfaWR9Iiwic2Vzc2lvbkluZGV4IjoxMn0seyJrZXkiOiJhcHAiLCJ2YWx1ZSI6IihzaXRlfGFkbWluaXN0cmF0b3IpIiwiZW5hYmxlZCI6dHJ1ZSwic2Vzc2lvblZhbHVlIjoiKHNpdGV8YWRtaW5pc3RyYXRvcikiLCJzZXNzaW9uSW5kZXgiOjEzfSx7ImtleSI6ImxhbmdfY29kZSIsInZhbHVlIjoie2xhbmdfY29kZX0iLCJlbmFibGVkIjp0cnVlLCJzZXNzaW9uVmFsdWUiOiJ7bGFuZ19jb2RlfSIsInNlc3Npb25JbmRleCI6MTR9LHsia2V5IjoiY29uc3RhbnRfaWQiLCJ2YWx1ZSI6Intjb25zdGFudF9pZH0iLCJlbmFibGVkIjp0cnVlLCJzZXNzaW9uVmFsdWUiOiJ7Y29uc3RhbnRfaWR9Iiwic2Vzc2lvbkluZGV4IjoxNX0seyJrZXkiOiJtZW51X2lkIiwidmFsdWUiOiJ7bWVudV9pZH0iLCJlbmFibGVkIjp0cnVlLCJzZXNzaW9uVmFsdWUiOiJ7bWVudV9pZH0iLCJzZXNzaW9uSW5kZXgiOjE2fSx7ImtleSI6Im1lbnVfaXRlbV9pZCIsInZhbHVlIjoie21lbnVfaXRlbV9pZH0iLCJlbmFibGVkIjp0cnVlLCJzZXNzaW9uVmFsdWUiOiJ7bWVudV9pdGVtX2lkfSIsInNlc3Npb25JbmRleCI6MTd9LHsia2V5IjoibWVzc2FnZV9pZCIsInZhbHVlIjoie21lc3NhZ2VfaWR9IiwiZW5hYmxlZCI6dHJ1ZSwic2Vzc2lvblZhbHVlIjoie21lc3NhZ2VfaWR9Iiwic2Vzc2lvbkluZGV4IjoxOH0seyJrZXkiOiJtb2R1bGVfaWQiLCJ2YWx1ZSI6Inttb2R1bGVfaWR9IiwiZW5hYmxlZCI6dHJ1ZSwic2Vzc2lvblZhbHVlIjoie21vZHVsZV9pZH0iLCJzZXNzaW9uSW5kZXgiOjE5fSx7ImtleSI6ImZlZWRfaWQiLCJ2YWx1ZSI6IntmZWVkX2lkfSIsImVuYWJsZWQiOnRydWUsInNlc3Npb25WYWx1ZSI6IntmZWVkX2lkfSIsInNlc3Npb25JbmRleCI6MjB9LHsia2V5IjoicmVxdWVzdF9pZCIsInZhbHVlIjoie3JlcXVlc3RfaWR9IiwiZW5hYmxlZCI6dHJ1ZSwic2Vzc2lvblZhbHVlIjoie3JlcXVlc3RfaWR9Iiwic2Vzc2lvbkluZGV4IjoyMX0seyJrZXkiOiJjb25zZW50X2lkIiwidmFsdWUiOiJ7Y29uc2VudF9pZH0iLCJlbmFibGVkIjp0cnVlLCJzZXNzaW9uVmFsdWUiOiJ7Y29uc2VudF9pZH0iLCJzZXNzaW9uSW5kZXgiOjIyfSx7ImtleSI6InJlZGlyZWN0X2lkIiwidmFsdWUiOiJ7cmVkaXJlY3RfaWR9IiwiZW5hYmxlZCI6dHJ1ZSwic2Vzc2lvblZhbHVlIjoie3JlZGlyZWN0X2lkfSIsInNlc3Npb25JbmRleCI6MjN9LHsia2V5IjoidGFnX2lkIiwidmFsdWUiOiJ7dGFnX2lkfSIsImVuYWJsZWQiOnRydWUsInNlc3Npb25WYWx1ZSI6Int0YWdfaWR9Iiwic2Vzc2lvbkluZGV4IjoyNH0seyJrZXkiOiJ0ZW1wbGF0ZV9zdHlsZV9pZCIsInZhbHVlIjoie3RlbXBsYXRlX3N0eWxlX2lkfSIsImVuYWJsZWQiOnRydWUsInNlc3Npb25WYWx1ZSI6Int0ZW1wbGF0ZV9zdHlsZV9pZH0iLCJzZXNzaW9uSW5kZXgiOjI1fSx7ImtleSI6InVzZXJfaWQiLCJ2YWx1ZSI6Int1c2VyX2lkfSIsImVuYWJsZWQiOnRydWUsInNlc3Npb25WYWx1ZSI6Int1c2VyX2lkfSIsInNlc3Npb25JbmRleCI6MjZ9XQ==)

## Installation
- Click on the Run in Postman button above or below in this README
- Follow the instructions (You should fork the collection in your own postman workspace)
- You should now have a new collection of endpoints in Postman
- Click on the collection, then on the ... on the right of the collection to open the settings for the collection
- Set your own values for Authentication and Variables per the steps below
- Test a generic GET request from the list to then confirm your authentication is working and your base_url and base_path is set correctly.

## Authentication
Authentication is done using a Joomla API Token. To get the token, go to your Super User profile in your Joomla 4 Installation and activate then copy the API key. In Postman, edit the Collection and then click on the Authorization tab.
- Select Type = "API Key"
- For the Key field, enter "X-Joomla-Token"
- In the Value field, paste your Joomla API Token
- For the Add To field, leave the value as "Header"
- Click Update to save the settings or click on Variables tab to modify your Base Path variable.

## URLs
The URLs are set via *base_url* and *base_path*.  You should set this variable within your collection.
- Click the 3 dots on the collection.
- Select Edit.
- Click on the variables tab.
- Add (or update) the *base_url* and *base_path* variable, setting the Initial Value field to the URL for your Joomla for installation.

## Documentation
The Postman generated Api documentation of Joomla! 4 Webservices collection

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/7443864-c678a936-c256-497c-9894-d8f193d81e7e?action=collection%2Ffork&collection-url=entityId%3D7443864-c678a936-c256-497c-9894-d8f193d81e7e%26entityType%3Dcollection%26workspaceId%3D9797ebcb-675e-4cd4-913e-15a8e23036e0#?env%5BJoomla%204%20Web%20Services%20Environment%20For%20Postman%5D=W3sia2V5IjoiYmFzZV91cmwiLCJ2YWx1ZSI6Imh0dHBzOi8vZXhhbXBsZS5vcmciLCJlbmFibGVkIjp0cnVlLCJzZXNzaW9uVmFsdWUiOiJodHRwczovL2V4YW1wbGUub3JnIiwic2Vzc2lvbkluZGV4IjowfSx7ImtleSI6ImJhc2VfcGF0aCIsInZhbHVlIjoiYXBpL2luZGV4LnBocC92MSIsImVuYWJsZWQiOnRydWUsInNlc3Npb25WYWx1ZSI6ImFwaS9pbmRleC5waHAvdjEiLCJzZXNzaW9uSW5kZXgiOjF9LHsia2V5IjoiYXV0aF9hcGlrZXkiLCJ2YWx1ZSI6IllPVVJfSk9PTUxBNF9BUElfS0VZIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6InNlY3JldCIsInNlc3Npb25WYWx1ZSI6IllPVVJfSk9PTUxBNF9BUElfS0VZIiwic2Vzc2lvbkluZGV4IjoyfSx7ImtleSI6ImJhbm5lcl9pZCIsInZhbHVlIjoie2Jhbm5lcl9pZH0iLCJlbmFibGVkIjp0cnVlLCJzZXNzaW9uVmFsdWUiOiJ7YmFubmVyX2lkfSIsInNlc3Npb25JbmRleCI6M30seyJrZXkiOiJjbGllbnRfaWQiLCJ2YWx1ZSI6IntjbGllbnRfaWR9IiwiZW5hYmxlZCI6dHJ1ZSwic2Vzc2lvblZhbHVlIjoie2NsaWVudF9pZH0iLCJzZXNzaW9uSW5kZXgiOjR9LHsia2V5IjoiY2F0ZWdvcnlfaWQiLCJ2YWx1ZSI6IntjYXRlZ29yeV9pZH0iLCJlbmFibGVkIjp0cnVlLCJzZXNzaW9uVmFsdWUiOiJ7Y2F0ZWdvcnlfaWR9Iiwic2Vzc2lvbkluZGV4Ijo1fSx7ImtleSI6ImNvbnRlbnRoaXN0b3J5X2lkIiwidmFsdWUiOiJ7Y29udGVudGhpc3RvcnlfaWR9IiwiZW5hYmxlZCI6dHJ1ZSwic2Vzc2lvblZhbHVlIjoie2NvbnRlbnRoaXN0b3J5X2lkfSIsInNlc3Npb25JbmRleCI6Nn0seyJrZXkiOiJjb21wb25lbnRfbmFtZSIsInZhbHVlIjoie2NvbXBvbmVudF9uYW1lfSIsImVuYWJsZWQiOnRydWUsInNlc3Npb25WYWx1ZSI6Intjb21wb25lbnRfbmFtZX0iLCJzZXNzaW9uSW5kZXgiOjd9LHsia2V5IjoiY29udGFjdF9pZCIsInZhbHVlIjoie2NvbnRhY3RfaWR9IiwiZW5hYmxlZCI6dHJ1ZSwic2Vzc2lvblZhbHVlIjoie2NvbnRhY3RfaWR9Iiwic2Vzc2lvbkluZGV4Ijo4fSx7ImtleSI6ImZpZWxkX2lkIiwidmFsdWUiOiJ7ZmllbGRfaWR9IiwiZW5hYmxlZCI6dHJ1ZSwic2Vzc2lvblZhbHVlIjoie2ZpZWxkX2lkfSIsInNlc3Npb25JbmRleCI6OX0seyJrZXkiOiJncm91cF9pZCIsInZhbHVlIjoie2dyb3VwX2lkfSIsImVuYWJsZWQiOnRydWUsInNlc3Npb25WYWx1ZSI6Intncm91cF9pZH0iLCJzZXNzaW9uSW5kZXgiOjEwfSx7ImtleSI6ImFydGljbGVfaWQiLCJ2YWx1ZSI6InthcnRpY2xlX2lkfSIsImVuYWJsZWQiOnRydWUsInNlc3Npb25WYWx1ZSI6InthcnRpY2xlX2lkfSIsInNlc3Npb25JbmRleCI6MTF9LHsia2V5IjoibGFuZ3VhZ2VfaWQiLCJ2YWx1ZSI6IntsYW5ndWFnZV9pZH0iLCJlbmFibGVkIjp0cnVlLCJzZXNzaW9uVmFsdWUiOiJ7bGFuZ3VhZ2VfaWR9Iiwic2Vzc2lvbkluZGV4IjoxMn0seyJrZXkiOiJhcHAiLCJ2YWx1ZSI6IihzaXRlfGFkbWluaXN0cmF0b3IpIiwiZW5hYmxlZCI6dHJ1ZSwic2Vzc2lvblZhbHVlIjoiKHNpdGV8YWRtaW5pc3RyYXRvcikiLCJzZXNzaW9uSW5kZXgiOjEzfSx7ImtleSI6ImxhbmdfY29kZSIsInZhbHVlIjoie2xhbmdfY29kZX0iLCJlbmFibGVkIjp0cnVlLCJzZXNzaW9uVmFsdWUiOiJ7bGFuZ19jb2RlfSIsInNlc3Npb25JbmRleCI6MTR9LHsia2V5IjoiY29uc3RhbnRfaWQiLCJ2YWx1ZSI6Intjb25zdGFudF9pZH0iLCJlbmFibGVkIjp0cnVlLCJzZXNzaW9uVmFsdWUiOiJ7Y29uc3RhbnRfaWR9Iiwic2Vzc2lvbkluZGV4IjoxNX0seyJrZXkiOiJtZW51X2lkIiwidmFsdWUiOiJ7bWVudV9pZH0iLCJlbmFibGVkIjp0cnVlLCJzZXNzaW9uVmFsdWUiOiJ7bWVudV9pZH0iLCJzZXNzaW9uSW5kZXgiOjE2fSx7ImtleSI6Im1lbnVfaXRlbV9pZCIsInZhbHVlIjoie21lbnVfaXRlbV9pZH0iLCJlbmFibGVkIjp0cnVlLCJzZXNzaW9uVmFsdWUiOiJ7bWVudV9pdGVtX2lkfSIsInNlc3Npb25JbmRleCI6MTd9LHsia2V5IjoibWVzc2FnZV9pZCIsInZhbHVlIjoie21lc3NhZ2VfaWR9IiwiZW5hYmxlZCI6dHJ1ZSwic2Vzc2lvblZhbHVlIjoie21lc3NhZ2VfaWR9Iiwic2Vzc2lvbkluZGV4IjoxOH0seyJrZXkiOiJtb2R1bGVfaWQiLCJ2YWx1ZSI6Inttb2R1bGVfaWR9IiwiZW5hYmxlZCI6dHJ1ZSwic2Vzc2lvblZhbHVlIjoie21vZHVsZV9pZH0iLCJzZXNzaW9uSW5kZXgiOjE5fSx7ImtleSI6ImZlZWRfaWQiLCJ2YWx1ZSI6IntmZWVkX2lkfSIsImVuYWJsZWQiOnRydWUsInNlc3Npb25WYWx1ZSI6IntmZWVkX2lkfSIsInNlc3Npb25JbmRleCI6MjB9LHsia2V5IjoicmVxdWVzdF9pZCIsInZhbHVlIjoie3JlcXVlc3RfaWR9IiwiZW5hYmxlZCI6dHJ1ZSwic2Vzc2lvblZhbHVlIjoie3JlcXVlc3RfaWR9Iiwic2Vzc2lvbkluZGV4IjoyMX0seyJrZXkiOiJjb25zZW50X2lkIiwidmFsdWUiOiJ7Y29uc2VudF9pZH0iLCJlbmFibGVkIjp0cnVlLCJzZXNzaW9uVmFsdWUiOiJ7Y29uc2VudF9pZH0iLCJzZXNzaW9uSW5kZXgiOjIyfSx7ImtleSI6InJlZGlyZWN0X2lkIiwidmFsdWUiOiJ7cmVkaXJlY3RfaWR9IiwiZW5hYmxlZCI6dHJ1ZSwic2Vzc2lvblZhbHVlIjoie3JlZGlyZWN0X2lkfSIsInNlc3Npb25JbmRleCI6MjN9LHsia2V5IjoidGFnX2lkIiwidmFsdWUiOiJ7dGFnX2lkfSIsImVuYWJsZWQiOnRydWUsInNlc3Npb25WYWx1ZSI6Int0YWdfaWR9Iiwic2Vzc2lvbkluZGV4IjoyNH0seyJrZXkiOiJ0ZW1wbGF0ZV9zdHlsZV9pZCIsInZhbHVlIjoie3RlbXBsYXRlX3N0eWxlX2lkfSIsImVuYWJsZWQiOnRydWUsInNlc3Npb25WYWx1ZSI6Int0ZW1wbGF0ZV9zdHlsZV9pZH0iLCJzZXNzaW9uSW5kZXgiOjI1fSx7ImtleSI6InVzZXJfaWQiLCJ2YWx1ZSI6Int1c2VyX2lkfSIsImVuYWJsZWQiOnRydWUsInNlc3Npb25WYWx1ZSI6Int1c2VyX2lkfSIsInNlc3Npb25JbmRleCI6MjZ9XQ==)
