# pulse-cli
Pulse time estimator CLI is used to predict estimated time taken to provision terraform resources of IBM-Cloud.

## Usage

predict            - Predicts estimated time for given plan file
```
./pulse-time-estimation-cli predict --plan=iam.json
```
predict-get        - Get predicted time for a given job id
```
./pulse-time-estimation-cli predict-get --id=<JobId>
```
predict-delete     - Delete predict job id
```
./pulse-time-estimation-cli predict-delete --id=<JobId>
```
predict-get-status - Get predict job status
```
./pulse-time-estimation-cli predict-get-status --id=<JobId>
```
