## Скрипт для проверки EVM кошельков на дроп Pyth network

Подробнее о дропе [описали челы из IDO research](https://t.me/idoresearch/2805).

Связь с создателем: https://t.me/CrytoBusher <br>
Если ты больше по Твиттеру: https://twitter.com/CryptoBusher <br>

Залетай сюда, чтоб не пропускать дропы подобных скриптов: https://t.me/CryptoKiddiesClub <br>
И сюда, чтоб общаться с крутыми ребятами: https://t.me/CryptoKiddiesChat <br>

## Первый запуск
1. Устанавливаем Python 3.10
2. Качаем репозиторий
3. Открываем терминал, переходим в папку с файлами и пишем команду "pip install -r requirements.txt"
4. Открываем файл "wallets.txt" и вбиваем адреса своих кошельков, каждый с новой строки
5. Открываем файл "proxies.txt" и вбиваем свои прокси (согласно порядку кошельков), или оставляем файл пустым для проверки без использования прокси. Если вбить 20 кошельков и 10 прокси - первые 10 кошельков проверит запросами через прокси, остальные 10 - без прокси. Прокси должны иметь формат "http://user:password@ip:port"
6. В терминале, находясь в папке проекта, вписываем команду "python3 pyth_network_airdrop_checker.py" и жмем ENTER
