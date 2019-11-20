# Model_Deployment
Model Deployment Repository

Author:<br>
Nirta Ika Yunita & Samuel Natamihardja

<br>
API description:
German Credit Scoring, this API call provide credit scoring of worthiness of an individual based on set of information.

* **URL**: http://samuelnatami.pythonanywhere.com/api  


* **Method**: `POST`
	
* **Parameters**
	
	* **Body**: 
		* duration_in_month: 
		* credit_amount: 
		* unemployed: 
		* installment_as_income_perc: 
		* present_res_since: 
		* age: 
		* credits_this_bank: 
		* people_under_maintenance: 
		* foreign_worker_yes: 


			example:
			```python
				{
					"duration_in_month": 6,
					"credit_amount": 1169,
					"unemployed": 0,
					"installment_as_income_perc": 4,
					"present_res_since": 4, 
					"age":67,
					"credits_this_bank": 2,
					"people_under_maintenance":1,
					"foreign_worker_yes:1
				}
			```
