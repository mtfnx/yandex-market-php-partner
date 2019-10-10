1. **Прочитайте [пользовательское соглашение](http://legal.yandex.ru/market_api_partner/) и [документацию](https://tech.yandex.ru/market/partner/doc/dg/concepts/about-docpage/) партнерского API**

2. **[Зарегистрируйте](https://partner.market.yandex.ru/pre) свой магазин в личном кабинете Маркета**
   
   Подробнее см. раздел [Как разместить товары](https://yandex.ru/support/partnermarket/registration/how-to-register.html) Помощи Маркета для магазинов.

3. **[Зарегистрируйте](https://oauth.yandex.ru/client/new) свое приложение на OAuth-сервере Яндекса**

   В разделе **Платформы** выберите опцию **Веб-сервисы** и нажмите **Подставить URL для разработки**, чтобы иметь возможность получать отладочные токены. По окончании регистрации вы получите ID приложения — его нужно будет использовать для получения токена и авторизации. 
   
   Подробнее см. раздел [Регистрация приложения](https://tech.yandex.ru/oauth/doc/dg/tasks/register-client-docpage/) технической документации OAuth в Яндексе.
   
4. **Получите авторизационный токен**

   Вы можете получить [отладочный токен вручную](https://tech.yandex.ru/oauth/doc/dg/tasks/get-oauth-token-docpage/) или воспользоваться [библиотекой для работы с OAuth](https://github.com/yandex-market/yandex-market-php-oauth).