# Night Atlas Privacy Policy

Effective and last updated: August 5, 2026

Night Atlas is a geography quiz game that works offline without an account. Some versions may offer an optional account for progress synchronization. If the version installed on your device does not show the account feature, the app does not send your gameplay or personal data to the Night Atlas backend. The sections about server processing apply only if account features are available and you choose to use them.

## Data Stored On Your Device

Night Atlas stores gameplay data locally on your device, including:

- completed levels, best scores, and stars;
- country practice and proficiency statistics;
- streaks, rewards, and collection progress;
- arcade records;
- selected app language;
- a safety backup created before progress is merged, when applicable.

This data is stored using Apple-provided local storage and is used to operate the game. If you use an optional account, the app also stores session credentials in the iOS Keychain and a random installation identifier locally. After you confirm account deletion, a random deletion-recovery receipt stays in the Keychain only until the app can verify the server result.

Signing out or deleting an account does not delete local gameplay progress. You can remove the on-device copy by deleting the app and its data through iOS.

## Optional Account Data

If optional account features are available and you request an email code or use an account, Night Atlas may process:

- your email address;
- internal account, user, and profile identifiers, plus a private fallback display name or identifier used internally;
- a random app-installation identifier, a random deletion-recovery receipt, and related one-way hashes or migration identifiers;
- synchronized gameplay content, including progress, scores, level and country statistics, streaks, rewards, collection progress, and arcade records;
- product-interaction and technical metadata, such as account setup, synchronization, and deletion events and timestamps, app language and version, and dataset version;
- security and diagnostic information, such as IP address, User-Agent, and authentication or proxy logs.

This data is linked to your account while the account is active. Night Atlas does not ask for your legal name, phone number, precise location, contacts, or photos.

## How We Use Account Data

We use optional account data only to:

- send one-time email codes and authenticate you;
- synchronize, merge, and restore your gameplay progress;
- operate, secure, troubleshoot, and recover the service;
- prevent fraud, abuse, and unauthorized access;
- process account deletion and provide support.

We do not use this data for advertising, cross-app or cross-website tracking, analytics, profiling, or marketing, and we do not sell it.

## Support Email Data

If you choose to contact Night Atlas support, you send an email through your own email service. The Night Atlas app opens an external Support page and does not itself transmit your support message or attachments.

Support processing may include the sender and recipient email addresses; the raw RFC 5322 message, including its subject, text or HTML parts, and any attachments you choose to include; delivery, authentication, and threading headers; provider activity metadata; and limited private storage metadata consisting of the record version, receipt and expiry times, raw message size, and a bounded sender hint.

Only the exact address [support@night-atlas.isupden.me](mailto:support@night-atlas.isupden.me) accepts support mail; catch-all routing is disabled. Cloudflare Email Routing sends incoming mail to a dedicated Email Worker, which accepts raw messages of no more than 10 MiB and stores them in a private Workers KV namespace. There is no public inbox or automatic reply. The support tooling does not automatically open, extract, execute, or save attachments. The developer accesses messages manually through owner-authorized Cloudflare management tooling.

A human writes each reply. Replies are sent from `support@night-atlas.isupden.me` through a dedicated sender-only Yandex Cloud Postbox service account. Night Atlas does not add email-open or link-click tracking.

## Service Providers And Data Location

The optional account service uses a self-hosted, Supabase-compatible open-source backend running on Yandex Cloud in the `ru-central1` region in Russia. Supabase Inc. does not host the backend as a managed service. Yandex Cloud provides the hosting, storage, networking, and security infrastructure. Yandex Cloud Postbox is used to deliver one-time authentication codes and human support replies by email.

Cloudflare, Inc. provides Email Routing, Email Workers, and Workers KV for incoming support mail. Cloudflare processes incoming messages on its global network and stores the raw message in private KV, so support data may be processed or stored outside your country and transferred across borders. Your email provider also processes the message. Yandex Cloud Postbox in Russia processes human replies and related delivery metadata. Support messages are not stored in the Night Atlas account database or its disaster-recovery snapshots. Workers KV encrypts stored values at rest and service connections use encryption in transit.

Account data is transmitted over HTTPS/TLS. Service providers process data only as needed to provide these functions or comply with law.

## Retention And Account Deletion

Account data is kept while your account is active and is needed to provide synchronization.

Requesting the first code creates a pending email authentication record. If the code is never verified and the record has no session or profile, it is automatically deleted within 24 hours.

To delete an account in the app, open **Profile → Account → Delete Account → Send Code**, enter the emailed code, and choose **Confirm Deletion**. Account deletion removes the authentication identity and email address, active sessions, private display name, server-side installation records, and synchronized gameplay and progress data.

Deleting an account does not erase gameplay progress stored locally on your device.

Minimal deletion, security, authentication, and proxy logs may be retained for no more than 30 days. These logs may include pseudonymous internal identifiers, the one-way hash of the random deletion-recovery receipt, event types and timestamps, IP address, User-Agent, and integrity metadata. The raw receipt is removed from the device when deletion completion is verified and is not stored in the database. These records are retained only for security, deletion verification, fraud prevention, troubleshooting, or legal compliance, and are not used for ads, tracking, analytics, or marketing.

Deleted server data may remain in encrypted disaster-recovery snapshots for up to 7 days. These snapshots are isolated from ordinary use and automatically expire or are overwritten. Any longer retention would occur only if required by law.

Each incoming support message and its private KV record are configured to expire 30 days after receipt. Sending a reply does not extend that period. The developer may delete a message earlier when it is no longer needed or when you request early deletion from the same sender address. Deleting a Night Atlas account does not automatically identify or delete separate support correspondence; request early deletion through the support address. Cloudflare, Yandex Cloud, and your email provider may separately retain limited security, activity, and delivery metadata under their service terms or legal obligations.

## Tracking, Advertising, And Analytics

Night Atlas does not show ads, use advertising identifiers, track you across apps or websites, or include third-party analytics SDKs. Support email does not use open or click tracking.

## Security

We use reasonable technical safeguards, including HTTPS/TLS in transit, access controls, encrypted disaster-recovery snapshots, exact-address-only support routing, private encrypted-at-rest Workers KV storage, owner-authorized mailbox access, a 10 MiB support message limit, no automatic attachment execution, and a dedicated sender-only Postbox service account. No system can guarantee absolute security.

## Children

Night Atlas is a general-audience geography game, and an account is optional. If you are not permitted to create an account in your jurisdiction, you can continue using the game without one. Account data is not used for advertising, tracking, profiling, or marketing.

## Purchases

The current version does not process payments inside the app. If purchases are added later, payments will be handled through Apple's App Store systems.

## Changes

If Night Atlas changes how it handles data, this policy and its updated date will be revised.

## Contact

Developer: Denis Isupov

For private support, account or deletion help, or privacy questions, email [support@night-atlas.isupden.me](mailto:support@night-atlas.isupden.me) or see the [support page](support.md).

Never send a one-time or login code, password, session or access token, deletion-recovery receipt, or any other secret. Night Atlas support will never ask for these secrets.

The [Night Atlas GitHub Issues form](https://github.com/IsupDen/night-atlas-pages/issues/new) is only for non-sensitive general bug reports and feature requests. GitHub issues are public. Do not post your email address, account, user, or installation identifier, or any other personal or sensitive data there.

---

# Политика конфиденциальности Night Atlas

Дата вступления в силу и последнего обновления: 5 августа 2026 г.

Night Atlas — игра-викторина для изучения географии, которая работает офлайн без аккаунта. В некоторых версиях может быть доступен необязательный аккаунт для синхронизации прогресса. Если в установленной на вашем устройстве версии нет функции аккаунта, приложение не отправляет игровой прогресс или персональные данные на backend Night Atlas. Разделы об обработке данных на сервере применяются только тогда, когда функции аккаунта доступны и вы решили ими воспользоваться.

## Данные, которые хранятся на устройстве

Night Atlas хранит игровой прогресс локально на вашем устройстве, включая:

- пройденные уровни, лучшие очки и звезды;
- статистику практики и знания стран;
- стрики, награды и прогресс коллекции;
- рекорды аркады;
- выбранный язык приложения;
- резервную копию, созданную перед объединением прогресса, если применимо.

Эти данные хранятся в локальном хранилище Apple и используются для работы игры. Если вы используете необязательный аккаунт, приложение также хранит данные сессии в Связке ключей iOS и случайный идентификатор установки локально. После подтверждения удаления аккаунта случайная квитанция восстановления хранится в Связке ключей только до проверки результата на сервере.

Выход из аккаунта или удаление аккаунта не удаляют локальный игровой прогресс. Копию на устройстве можно удалить, удалив приложение и его данные средствами iOS.

## Данные необязательного аккаунта

Если функции аккаунта доступны и вы запрашиваете код по email или используете аккаунт, Night Atlas может обрабатывать:

- ваш адрес email;
- внутренние идентификаторы аккаунта, пользователя и профиля, а также закрытое резервное отображаемое имя или идентификатор для внутреннего использования;
- случайный идентификатор установки приложения, случайную квитанцию восстановления удаления и связанные односторонние хеши или идентификаторы миграции;
- синхронизированные игровые данные, включая прогресс, очки, статистику уровней и стран, стрики, награды, прогресс коллекции и рекорды аркады;
- технические метаданные и сведения о взаимодействии с продуктом, например события и время создания аккаунта, синхронизации и удаления, язык и версию приложения, версию набора данных;
- сведения для безопасности и диагностики, например IP-адрес, User-Agent, журналы аутентификации или прокси-сервера.

Эти данные связаны с вашим аккаунтом, пока он активен. Night Atlas не запрашивает настоящее имя, номер телефона, точную геолокацию, контакты или фотографии.

## Как мы используем данные аккаунта

Мы используем данные необязательного аккаунта только для того, чтобы:

- отправлять одноразовые коды по email и выполнять аутентификацию;
- синхронизировать, объединять и восстанавливать игровой прогресс;
- обеспечивать работу, безопасность, диагностику и восстановление сервиса;
- предотвращать мошенничество, злоупотребления и несанкционированный доступ;
- обрабатывать удаление аккаунта и оказывать поддержку.

Мы не используем эти данные для рекламы, отслеживания между приложениями или сайтами, аналитики, профилирования или маркетинга и не продаем их.

## Данные обращений в поддержку по email

Если вы решаете обратиться в поддержку Night Atlas, вы отправляете письмо через собственный почтовый сервис. Приложение Night Atlas открывает внешнюю страницу поддержки и само не передает текст обращения или вложения.

При обработке обращения могут использоваться адреса отправителя и получателя; исходное письмо в формате RFC 5322, включая тему, текстовую или HTML-часть и добровольно добавленные вложения; заголовки доставки, аутентификации и цепочки переписки; служебные метаданные активности провайдеров; а также ограниченные закрытые метаданные хранения: версия записи, время получения и удаления по сроку, размер исходного письма и ограниченная подсказка об отправителе.

Письма в поддержку принимает только точный адрес [support@night-atlas.isupden.me](mailto:support@night-atlas.isupden.me); маршрутизация catch-all отключена. Cloudflare Email Routing передает входящие письма в отдельный Email Worker, который принимает исходные сообщения размером не более 10 МиБ и хранит их в закрытом пространстве Workers KV. Публичного почтового ящика и автоматического ответа нет. Инструменты поддержки не открывают, не извлекают, не запускают и не сохраняют вложения автоматически. Разработчик просматривает обращения вручную через средства управления Cloudflare с доступом только владельца.

Каждый ответ пишет человек. Ответы отправляются с адреса `support@night-atlas.isupden.me` через отдельную сервисную учетную запись Yandex Cloud Postbox с правом только на отправку. Night Atlas не добавляет отслеживание открытия писем или переходов по ссылкам.

## Поставщики услуг и место хранения данных

Необязательный сервис аккаунтов использует самостоятельно размещенный открытый backend, совместимый с Supabase и работающий в Yandex Cloud в регионе `ru-central1` в России. Supabase Inc. не размещает этот backend как управляемый сервис. Yandex Cloud предоставляет инфраструктуру хостинга, хранения, сети и безопасности. Yandex Cloud Postbox используется для отправки одноразовых кодов аутентификации и ответов человека из поддержки по email.

Cloudflare, Inc. предоставляет Email Routing, Email Workers и Workers KV для входящих обращений в поддержку. Cloudflare обрабатывает входящие письма в своей глобальной сети и хранит исходное сообщение в закрытом KV, поэтому данные поддержки могут обрабатываться или храниться за пределами вашей страны и передаваться через границы. Письмо также обрабатывает ваш почтовый провайдер. Yandex Cloud Postbox в России обрабатывает ответы человека и связанные метаданные доставки. Обращения в поддержку не хранятся в базе данных аккаунтов Night Atlas или ее аварийных снимках. Workers KV шифрует сохраненные значения, а соединения между сервисами защищаются при передаче.

Данные аккаунта передаются по HTTPS/TLS. Поставщики услуг обрабатывают данные только в объеме, необходимом для выполнения этих функций или соблюдения закона.

## Сроки хранения и удаление аккаунта

Данные аккаунта хранятся, пока аккаунт активен и они нужны для синхронизации.

При запросе первого кода создается ожидающая подтверждения запись аутентификации с адресом email. Если код не подтвержден и у записи нет сессии или профиля, она автоматически удаляется в течение 24 часов.

Чтобы удалить аккаунт в приложении, откройте **Профиль → Аккаунт → Удалить аккаунт → Отправить код**, введите код из письма и выберите **Подтвердить удаление**. При удалении аккаунта удаляются данные аутентификации и адрес email, активные сессии, закрытое отображаемое имя, серверные записи об установке приложения, синхронизированный игровой прогресс и игровые данные.

Удаление аккаунта не стирает игровой прогресс, сохраненный локально на вашем устройстве.

Минимальные журналы удаления, безопасности, аутентификации и прокси-сервера могут храниться не более 30 дней. Они могут включать псевдонимные внутренние идентификаторы, односторонний хеш случайной квитанции восстановления удаления, типы и время событий, IP-адрес, User-Agent и метаданные целостности. Исходная квитанция удаляется с устройства после подтверждения завершения удаления и не хранится в базе данных. Эти записи хранятся только для безопасности, подтверждения удаления, предотвращения мошенничества, диагностики или соблюдения закона и не используются для рекламы, трекинга, аналитики или маркетинга.

Удаленные серверные данные могут оставаться в зашифрованных снимках аварийного восстановления до 7 дней. Эти снимки изолированы от обычного использования и автоматически удаляются или перезаписываются. Более длительное хранение возможно только тогда, когда этого требует закон.

Каждое входящее обращение и его закрытая запись в KV автоматически удаляются через 30 дней после получения. Отправка ответа не продлевает этот срок. Разработчик может удалить письмо раньше, когда оно больше не нужно или когда вы запрашиваете досрочное удаление с того же адреса отправителя. Удаление аккаунта Night Atlas не позволяет автоматически найти и удалить отдельную переписку с поддержкой; запросите досрочное удаление через адрес поддержки. Cloudflare, Yandex Cloud и ваш почтовый провайдер могут отдельно хранить ограниченные метаданные безопасности, активности и доставки в соответствии со своими условиями или требованиями закона.

## Трекинг, реклама и аналитика

Night Atlas не показывает рекламу, не использует рекламные идентификаторы, не отслеживает вас между приложениями или сайтами и не содержит сторонних SDK аналитики. В письмах поддержки нет отслеживания открытия или переходов по ссылкам.

## Безопасность

Мы применяем разумные технические меры защиты, включая HTTPS/TLS при передаче данных, контроль доступа, зашифрованные снимки аварийного восстановления, прием писем только на точный адрес поддержки, закрытое зашифрованное при хранении пространство Workers KV, доступ к обращениям только владельца, ограничение сообщения 10 МиБ, отсутствие автоматического запуска вложений и отдельную сервисную учетную запись Postbox только для отправки. Ни одна система не может гарантировать абсолютную безопасность.

## Дети

Night Atlas — географическая игра для широкой аудитории, а аккаунт необязателен. Если в вашей юрисдикции вам не разрешено создавать аккаунт, вы можете продолжать использовать игру без него. Данные аккаунта не используются для рекламы, трекинга, профилирования или маркетинга.

## Покупки

Текущая версия не обрабатывает платежи внутри приложения. Если покупки будут добавлены позже, платежи будут обрабатываться через системы Apple App Store.

## Изменения

Если Night Atlas изменит подход к обработке данных, эта политика и дата ее обновления будут пересмотрены.

## Контакты

Разработчик: Денис Исупов

Для приватного обращения в поддержку, помощи с аккаунтом или его удалением, а также вопросов о конфиденциальности напишите на [support@night-atlas.isupden.me](mailto:support@night-atlas.isupden.me) или откройте [страницу поддержки](support.md).

Никогда не отправляйте одноразовый код или код входа, пароль, токен сессии или доступа, квитанцию восстановления удаления или другой секрет. Поддержка Night Atlas никогда не запросит эти секреты.

[Форма GitHub Issues Night Atlas](https://github.com/IsupDen/night-atlas-pages/issues/new) предназначена только для общих сообщений об ошибках и предложений без конфиденциальных данных. Обращения в GitHub Issues публичны. Не публикуйте там адрес email, идентификатор аккаунта, пользователя или установки, а также другие персональные или конфиденциальные данные.
