# CryptoPulse

**CryptoPulse** — приложение для отслеживания цен криптовалют в реальном времени с использованием API CoinGecko. Программа позволяет выбрать криптовалюту, узнать ее текущую стоимость в USD и автоматически конвертировать цену в рубли для удобного анализа.

## Основные возможности

- **Получение списка криптовалют**: просматривайте актуальный список доступных криптовалют с их символами и именами.
- **Отслеживание цен**: получайте текущую стоимость выбранной криптовалюты в USD.
- **Конвертация валют**: конвертируйте цену из USD в рубли на основе актуального курса.

## Установка

**1. Клонируйте репозиторий**:

   git clone https://github.com/yourusername/cryptopulse.git
   cd cryptopulse
   
**2. Соберите проект с помощью Maven**:
   
   mvn clean install
   
**3. Запустите программу с помощью Maven**:

   mvn exec:java -Dexec.mainClass="com.myapp.MainCryptoApp"
   
## Зависимости

Проект использует:

**CoinGecko Java API**: для получения данных о криптовалютах
**Gson**: для обработки JSON данных
**JUnit**: для тестирования
