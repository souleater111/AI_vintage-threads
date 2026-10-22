```mermaid
flowchart TD
    Start([👤 Пользователь заходит]) --> Land[🏠 index.html]
    Land --> Choice{Куда идёт?}
    Choice -->|Купить| Cat[👕 Каталог]
    Choice -->|Узнать| About[ℹ️ О нас]
    Choice -->|Посмотреть| Gal[🖼️ Галерея]
    Choice -->|Связаться| Cont[📞 Контакты]

    Cat --> Filter[🔍 Фильтр по категории]
    Filter --> Card[👆 Клик на товар]
    Card --> Btn[Подробнее]

    Gal --> Click[👆 Клик на фото]
    Click --> Zoom[🔦 Lightbox]

    Cont --> Fill[📝 Заполнить форму]
    Fill --> Submit[✅ Отправить]
    Submit --> Alert[💬 Alert спасибо]

    style Start fill:#d4a574,color:#2c2c2c
    style Land fill:#f0e6d6,color:#2c2c2c
    style Choice fill:#b8885a,color:#fff
    style Cat fill:#faf8f3,color:#2c2c2c
    style Gal fill:#faf8f3,color:#2c2c2c
    style Cont fill:#faf8f3,color:#2c2c2c
```