# CourseWork
Машинобудівне підприємство, а саме, його плановий відділ планує випуск продукції з урахуванням її укрупненої номенклатури і лише ключових ресурсів. Планування продажу і операцій (Sales and Operation Plan, S&OP) – щомісячний циклічний процес, де в результаті серії нарад плановий відділ визначає попит на продукцію підприємства, випуск продукції підприємством, нові продукти, фінансові та інші ресурси. Основні характеристики процесу планування продажу і операцій:
•	Горизонт планування – ковзаючий, 18-24 місяці,
•	Інтервал планування – 1 місяць,
•	Об’єкт планування – товарні групи, як правило, не більше 10, як правило, у грошовому виразі, або в умовно-натуральних одиницях(як-от тонни умовної продукції).
•	Вхідна інформація – прогноз попиту, отриманий в результаті прогнозування. Планується лише незалежний попит (не пов’язаний з попитом на інші номенклатурні позиції), як-от готова продукція, запчастини. 
Плановий відділ розраховує необхідну кількість ключових ресурсів, які можуть бути „вузьким місцем” (матеріальні, трудові, час обладнання), теж по укрупненій номенклатурі. Для цього використовується матриця технологічних коефіціентів витрат ресурсів на кожний вид продукції, де в рядках перелічені ключові ресурси, а в колонках – ключові продукти.
У звітності необхідно на підставі прогнозу попиту на ключові продукти відображати потреби у ключових ресурсах на півтора-два роки з моменту планування. 

-	Production (таблиця призначена для зберігання назви продукції)
-	ResourceDictionary (таблиця призначена для зберігання назви ресурсів)
-	LoadingPlanRow (таблиця зберігає рік, місяць та кількість продукції яку потрібно відвантажити в цей період)
-	ConsumptionElement (таблиця зберігає кількість ресурсів, що необхідна для виготовлення одиниці продукції) 
