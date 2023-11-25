# home_requests

---

# Определение погоды в указанном городе

---

## За основу был взят [сайт](https://openweathermap.org/)

####  Использовались **2 CONST :**  
* API_KEY
* URL

### Пример отрывка *кода:*

---
```python
def main():
    print("Привет!")
    while True:
        city = get_city()
        response = request(city)
        if response:
            break
        print("Не смог найти такой город, повторите попыту!")
    data = get_data(response)
    msg = massage(data, city)
    print(msg)
    
```
---

![Изображение](https://fikiwiki.com/uploads/posts/2022-02/1645010673_27-fikiwiki-com-p-kartinki-pro-pogodu-30.jpg)
    




