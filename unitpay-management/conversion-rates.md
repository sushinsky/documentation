# Курсы конвертации валют

| https://unitpay.money/api?       method=getCurrencyCourses       params\[login\]=partner@gmail.com       params\[secretKey\]=ключ |
| :--- |


|  | Значение | Описание |
| :--- | :--- | :--- |
| **login**  | строка | Email партнера в системе UnitPay |
| **secretKey** | строка | Секретный ключ партнера, доступен в [настройках профиля](https://unitpay.ru/partner/profile/edit) |

#### Успешный ответ

```text
{
   "result": {
      "in": {
         "wmz": 62.57,
         "uah": 2.55
      },
      "out": {
         "wmz": 64.9,
         "uah": 2.65
      }
   }
}
```

|  | Значение | Описание |
| :--- | :--- | :--- |
| **тип платежа** | текст | Тип конвертации: на прием \(in\) либо на выплату \(out\)  |
| **валюта** | текст | Валюта пдатежа/выплаты  |
| **курс** | число | Курс конвертации выбранной валюты  |

