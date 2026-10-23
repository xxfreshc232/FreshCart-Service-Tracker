# FreshCart Service Tracker

Консольний модуль моделювання життєвого циклу замовлення e-Grocery супермаркету «FreshCart» (C# / .NET 8).

## Функціональність
- Обробка статусів: CREATED -> PICKING -> DELIVERED.
- Розрахунок холдування суми (+10% на вагові товари).
- Верифікація замовлення через 4-значний OTP код клієнта.

## Як розгорнути та запустити
1. Клонувати репозиторій:
   git clone https://github.com/xxfreshc232/FreshCart-Service-Tracker.git
2. Перейти до каталогу проєкту:
   cd FreshCart-Service-Tracker
3. Запустити додаток через .NET CLI:
   dotnet run
