The Rivery API allows users to interact with Rivery resources.

Authentication:
The administrator of an account has the ability to add, view, and delete tokens for the account.
Only admin users are allowed to access this functionality.
Please Note:
This functionality can only be accessed by admin users.


New API Documentation:
In this New API documentation, the following API endpoints are outlined:

Authorization - Rivery API Token, Scopes.
Rivers - List River Versions, Get River Version, Get River, Delete River, List Rivers, Get CDC Config, Set CDC Config, Delete CDC Config, Cancel River Run, Run River, Run Sub River, Get River Variables, Update River Variable.
Beta Endpoints - Edit River, Add River, Copy River, Restore River Version, Enable CDC.
Activities - Get Activities Statistic, Get River Activities Statistic, Get River Activities Targets, List River Activities Run Groups, List River Activities Run Groups, Get River Activities Run Groups, Get River Activities Sub Rivers, Get River Activities Runs, Get River Activities Run, Get River Activities Run Logic Steps, Get Activities Logic Variables, Get Activities Logic Step Log, Get Activities, Get Run Logs.
Connections - Delete Connection.
DataFrames - Get Dataframes, Add Dataframe, Get Dataframe by Name, Update Dataframe, Delete Dataframe, Download Dataframe, Clear Dataframe Values.
Environments - Get Environment, List Environments.
Audit Events- List Audit Events, Get Audit Event.
Beta Endpoints - Add Environment, Patch Environment ,Delete Environment.

Endpoints:
List river versions - https://api.rivery.io/v1/accounts/{account_id}/environments/{environment_id}/rivers/{river_cross_id}/versions
List rivers - https://api.rivery.io/v1/accounts/{account_id}/environments/{environment_id}/rivers
activities statistics - https://api.rivery.io/v1/accounts/{account_id}/environments/{environment_id}/activities_statistics
connection types - https://api.rivery.io/v1/connections_types
get dataframes - https://api.rivery.io/v1/accounts/{account_id}/environments/{environment_id}/dataframes
get user permissions - https://api.rivery.io/v1/accounts/{account_id}/users/{user_id}/permissions


