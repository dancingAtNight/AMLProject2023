# Santander Product Recommendation

## Introduction

This project aims to analyze the ownership of financial products by bank customers. The data provided contains information about the demographics of the customers, the products they own, and other relevant information such as their country of residence, age, gross income, etc.

## Data

The data contains the following fields:

- `fecha_dato`: Date
- `ncodpers`: Customer code
- `ind_empleado`: Employee index (A active, B ex employed, F filial, N not employee, P pasive)
- `pais_residencia`: Customer's Country residence
- `sexo`: Customer's sex
- `age`: Age
- `fecha_alta`: The date in which the customer became as the first holder of a contract in the bank
- `ind_nuevo`: New customer Index (1 if the customer registered in the last 6 months)
- `antiguedad`: Customer seniority (in months)
- `indrel`: 1 (First/Primary), 99 (Primary customer during the month but not at the end of the month)
- `ult_fec_cli_1t`: Last date as primary customer (if he isn't at the end of the month)
- `indrel_1mes`: Customer type at the beginning of the month (1 First/Primary customer, 2 co-owner, P Potential, 3 former primary, 4 former co-owner)
- `tiprel_1mes`: Customer relation type at the beginning of the month (A active, I inactive, P former customer, R Potential)
- `indresi`: Residence index (S (Yes) or N (No) if the residence country is the same than the bank country)
- `indext`: Foreigner index (S (Yes) or N (No) if the customer's birth country is different than the bank country)
- `conyuemp`: Spouse index (1 if the customer is spouse of an employee)
- `canal_entrada`: Channel used by the customer to join
- `indfall`: Deceased index (N/S)
- `tipodom`: Address type (1, primary address)
- `cod_prov`: Province code (customer's address)
- `nomprov`: Province name
- `ind_actividad_cliente`: Activity index (1, active customer; 0, inactive customer)
- `renta`: Gross income of the household
- `segmento`: Segmentation (01 - VIP, 02 - Individuals 03 - college graduated)
- `ind_ahor_fin_ult1`: Saving Account
- `ind_aval_fin_ult1`: Guarantees
- `ind_cco_fin_ult1`: Current Accounts
- `ind_cder_fin_ult1`: Derivada Account
- `ind_cno_fin_ult1`: Payroll Account
- `ind_ctju_fin_ult1`: Junior Account
- `ind_ctma_fin_ult1`: Más particular Account
- `ind_ctop_fin_ult1`: Particular Account
- `ind_ctpp_fin_ult1`: Particular Plus Account
- `ind_deco_fin_ult1`: Short-term deposits
- `
