## Набор тестовых данных

|      Логин         |      Пароль        | 				                        Описание 				                            |
|:------------------:|:------------------:| ----------------------------------------------------------------------------|
| `Test0@mail.ru`    | `!#$%&*)_+-1Ab`    | *Корректные данные (Смешанный пароль из разрешенных символов, букв и цифр)* |
| `Test1@mail.ru`    | `1234567890098`    | *Корректные данные (Пароль из цифр)*       				                          |
| `Test2@mail.ru`    | `QWERTYUIOPAS`     | *Корректные данные (Пароль из латыни верхнего регистра)* 		                |
| `Test3@mail.ru`    | `qwertyuiopas`     | *Корректные данные (Пароль из латыни нижнего регистра)* 		                |
| `Test4@mail.ru`    | `! # A%*)_+-b`     | *Корректные данные (Смешанный пароль с пробелами)*       		                |
| `Test5@mail.ru`    | `1xX#$%^8`         | *Корректные данные (Пароль из 8 символов)* 		    		                      |
| `Test6@mail.ru`    | `123456781xX#$%^8` | *Корректные данные (Пароль из 16 символов)* 		    	                      |
|  `Test5@mail.ru`   | `1xX#$%^8`         | *Корректные данные (Пробел перед и после логина)* 		                      |		
| `Test5 @mail.ru`   |  `1xX#$%^8`        | *Корректные данные (Пробел посредине логина)*		    	                      |
| `8-909-259-56-81`  |   `1xX#$%^8`       | *Корректные данные (Формат с 8 и -)*		    		                            |  
| `+7-909-259-56-91` |    `1xX#$%^8`      | *Корректные данные (Формат с +7 и -)*		    		                            |    
| `89092595681`      |   `1xX#$%^8`       | *Корректные данные (Формат с 8 без пробелов)*		    	                      |
|`+79092595681`      |    `1xX#$%^8`      | *Корректные данные (Формат с +7 без пробелов)*		    	                    |		
| `8 909 259 56 81`  |   `1xX#$%^8`       | *Корректные данные (Формат с 8 и пробелами)*		    	                      |
| `+7 909 259 56 81` |  `1xX#$%^8`        |*Корректные данные (Формат с +7 и пробелами)*		    	                      |	
| `7-909-259-56-81`  |   `1xX#$%^8`       | *Корректные данные (Формат с 7  и - )*		    	                            |
| `79092595681`      |    `1xX#$%^8`      | *Корректные данные (Формат с 7 без пробелов)*		    	                      |	
| `7 909 259 56 81`  |   `1xX#$%^8`       | *Корректные данные (Формат с 7  и пробелами)*		    	                      |
| `8-909-259-56-81`  |   `1xX#$%^8`       | *Корректные данные (Формат с 8 и -, с пробелом перед номером и после)*      |
| `8 909 259 56 81`  |    `1xX#$%^8`      | *Корректные данные (Формат с 8 и пробелами, с пробелом перед номером и после)*  |
| `89092595681`      |    `1xX#$%^8`      |*Корректные данные (Формат с 8 без пробелов, с пробелом перед номером и после)*  |
| `+7-909-259-56-81` |   `1xX#$%^8`       | *Корректные данные (Формат с +7 и -, с пробелом перед номером и после)*         |
| `+7 909 259 56 81` | `1xX#$%^8`         | *Корректные данные (Формат с +7 и пробелами, с пробелом перед номером и после)* |
| `+79092595681`     |    `1xX#$%^8`      | *Корректные данные (Формат с +7 без пробелов, с пробелом перед номером и после)*|
|  `7-909-259-56-81` |  `1xX#$%^8`        | *Корректные данные (Формат с 7 с -, с пробелом перед номером и после)*          |
|  `7 909 259 56 81` |  `1xX#$%^8`        | *Корректные данные (Формат с 7 с пробелами, с пробелом перед номером и после)*  |
| `79092595681`      | `1xX#$%^8`         | *Корректные данные (Формат с 7 без пробелов, с пробелом перед номером и после)* |
| `8-909-259-56-811` |  `1xX#$%^8`        | *Некорректный номер (На 1 цифру больше)*	      			                          |
| `+7-909-259-56-8`  | `1xX#$%^8`         | *Некорректный номер (На 1 цифру меньше)*	      			                          |
|  `!@#$%^&*()_+`    | `1xX#$%^8`         | *Некорректные данные (Спецсимволы  в поле логина)*		    	                    |	
| `Test5mail.ru`     | `1xX#$%^8`         | *Некорректный логин (Почтовый ящик без @)*		    	                            |
| `Test5@@mail.ru`   | `1xX#$%^8`         | *Некорректный логин (Почтовый ящик с двумя @)*	    	      	                  |	    	      
|`11111111111111111111111111111111111111`| `1xX#$%^8`        | *Некорректный логин (Количество символов более 17)*	    	  |	
|`Тест5@mail.ru`     | `1xX#$%^8`         | *Некорректный логин (Используются буквы русского алфавита)*    	                |
|`Test5@mail`        | `1xX#$%^8`         | *Некорректный логин (Без домена)*   	       			                            	| 	
|`@mail`             | `1xX#$%^8`         | *Некорректный логин (Без имени)*  	      				                              | 	
|`Test5@mail.ru`     | `1xX#$%^8`         | *Некорректный пароль (Количество символов 7)*  	        	                      | 			
|`Test5@mail.ru`     | `12345678909876543`| *Некорректный пароль (Количество символов 17)* 	       			                    | 
|`Test5@mail.ru`     | `11111111111111111111111111111111111111`| *Некорректный пароль (Количество символов более 17)*       | 	
|`Test5@mail.ru`     |`1xX#$%^Б`          | *Некорректный пароль (Содержится буква русского алфавита)*	       		          |
|                    |                    | *Пустые строки*	      						                                              |	
|         ` `        |         ` `        | *Пробелы*	       								                                                |	
|                    |   `1xX#$%^8`       | *Пустой логин*	      						                                              |			
| `Test5@mail.ru`    |                    | *Пустой пароль*	       							                                            |
| `<script>`         | `<script>`         |*Некорректные данные (HTML - теги)*	     				                                |	
| `Test5@mail.ru`    | `1xX#$%^8' OR '1'='1`|*Некорректные данные (SQL инъекция)*	     				                              |	
