# churn_model

`telecom_users.csv` содержит следующие значения:

`customerID` – id клиента
`gender` – пол клиента (male/female)
`SeniorCitizen` – яляется ли клиент пенсионером (1, 0)
`Partner` – состоит ли клиент в браке (Yes, No)
`Dependents` – есть ли у клиента иждивенцы (Yes, No)
`tenure` – сколько месяцев человек являлся клиентом компании
`PhoneService` – подключена ли услуга телефонной связи (Yes, No)
`MultipleLines` – подключены ли несколько телефонных линий (Yes, No, No phone service)
`InternetService` – интернет-провайдер клиента (DSL, Fiber optic, No)
`OnlineSecurity` – подключена ли услуга онлайн-безопасности (Yes, No, No internet service)
`OnlineBackup` – подключена ли услуга online backup (Yes, No, No internet service)
`DeviceProtection` – есть ли у клиента страховка оборудования (Yes, No, No internet service)
`TechSupport` – подключена ли услуга технической поддержки (Yes, No, No internet service)
`StreamingTV` – подключена ли услуга стримингового телевидения (Yes, No, No internet service)
`StreamingMovies` – подключена ли услуга стримингового кинотеатра (Yes, No, No internet service)
`Contract` – тип контракта клиента (Month-to-month, One year, Two year)
`PaperlessBilling` – пользуется ли клиент безбумажным биллингом (Yes, No)
`PaymentMethod` – метод оплаты (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
`MonthlyCharges` – месячный размер оплаты на настоящий момент
`TotalCharges` – общая сумма, которую клиент заплатил за услуги за все время
`Churn` – произошел ли отток (Yes or No)
