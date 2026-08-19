# MobilityAI Data Model

## 1. Employees

- employee_id
- first_name
- last_name
- department
- job_level
- home_country
- home_city
- hire_date

## 2. Relocations

- relocation_id
- employee_id
- origin_city
- origin_country
- destination_city
- destination_country
- relocation_type
- start_date
- expected_completion_date
- actual_completion_date
- status

## 3. Vendors

- vendor_id
- vendor_name
- service_type
- country
- vendor_rating
- active_status

## 4. Services

- service_id
- relocation_id
- vendor_id
- service_type
- service_start_date
- expected_completion_date
- actual_completion_date
- service_status

## 5. Relocation Costs

- cost_id
- relocation_id
- housing_cost
- moving_cost
- travel_cost
- immigration_cost
- storage_cost
- other_cost
- total_cost
- currency

## 6. Surveys

- survey_id
- relocation_id
- employee_id
- satisfaction_score
- vendor_rating
- nps_score
- comments
- survey_date