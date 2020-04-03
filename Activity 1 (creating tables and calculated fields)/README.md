# SAS - Actividad 1

a) Importar el fichero CUSTOMER_CHURN_TELCO.csv a la tabla TABSAS.CUSTOMER_CHURN_TELCO

 
b) Crear una tabla llamada CUSTOMERS_ANT_XXX (donde XXX son las iniciales del alumno) que sea un filtro de la anterior para los clientes con tenure > 36.


c) Crear un campo calculado llamado: tenure_year como resultado de dividir por 12 el campo tenure. El nuevo campo debe tener 2 decimales


d) Crear un campo calculado llamado charges_level que tome 3 posibles valores:


charges_level = 1 para MonthlyCharges entre 0 y 20 (incluido)  
charges_level = 2 para MonthlyCharges entre 20 y 50 (incluido)  
charges_level = 3 para MonthlyCharges mayor que 50  


e)	Añadir paso adicional a elegir por el alumno (tratar de que quede como algo separado)

# SAS - Activity 1

a)	Import _CUSTOMER_CHURN_TELCO.csv_ file and create a table named _TABSAS.CUSTOMER_CHURN_TELCO_ .

b)	Create a new table with the name _CUSTOMERS_ANT_XXX_ (where XXX represent the student’s name initials) by filtering all tenure values greater than 36 from the previous table.

c)  Create a new calculated field named _tenure_year__by dividing the value of tenure by 12. The new field must be a decimal with 2 points.

d)  Create a new calculated field with the name _charges_level_ allowing for three different values:


charges_level = 1 for MonthlyCharges values between 0 y 20 (included)  
charges_level = 2 for MonthlyCharges values between 20 y 50 (included)  
charges_level = 3 MonthlyCharges greater than 50  

e) Perform an additional task of your choice, making sure it is included as a separate step within the Sas flow.
