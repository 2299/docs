# Вопросы по работе с нерезидентами Российской Федерации и Республики Казахстан


#### Могу ли я стать клиентом {{ yandex-cloud }}, если являюсь нерезидентом Российской Федерации (РФ) или Республики Казахстан (РК)? {#non-resident}

Да, можете, но только если являетесь организацией. 


#### С резидентами каких стран вы сотрудничаете? {#countries}

Заключить договор и создать платежный аккаунт могут резиденты стран, перечисленных в списке ниже. 

{% include [non-resident-countries](../../billing/_includes/non-resident-countries.md) %}


#### Что делать, если я не нашел свою страну в списке? {#more-countries}

Если вы не нашли свою страну в [списке стран](#countries), с которыми сотрудничает {{ yandex-cloud }}, оставьте заявку в [форме](/#contact-form). Менеджер {{ yandex-cloud }} свяжется с вами.


#### Будет ли предоставлен договор на оказание и оплату услуг? {#contract}

{% include [contract-qa](../../billing/_includes/contract-qa.md) %}

#### Какие способы оплаты я могу использовать? {#payment-types}

Организации-нерезиденты РФ и РК могут пополнять лицевой счет и оплачивать потребленные ресурсы с помощью [банковской карты](../../billing/payment/payment-methods-card-business.md) или [перевода средств с расчетного счета](../../billing/payment/payment-methods-business.md).


#### В какой валюте нерезиденты РФ и РК могут оплачивать услуги {{ yandex-cloud }}? {#currency}

Нерезиденты РФ и РК могут оплачивать услуги {{ yandex-cloud }} только в долларах США ($), независимо от страны, в которой проживают.

#### Какие документы будут мне предоставлены после оплаты услуг? {#documents}

{{ yandex-cloud }} формирует [счет на оплату](../../billing/concepts/bill.md) для организаций-нерезидентов РФ и РК. Копия счета отправляется на электронную почту владельца платежного аккаунта в начале следующего отчетного периода. 


#### Как учитываются налоги при оплате услуг? {#taxes}

Налоги и сборы страны, в которой зарегистрирована организация-нерезидент РФ и РК, не добавляются к стоимости услуг на странице [детализации](../../billing/operations/check-charges.md) и не входят в итоговую сумму счета на оплату. 

Все налоги и сборы, предусмотренные законодательством страны проживания, нерезидент РФ и РК выплачивает самостоятельно. 

#### Почему платежный аккаунт был создан в статусе PAYMENT_NOT_CONFIRMED?  {#pending-status}

Для активации платежного аккаунта нерезидента РФ и РК необходимо подтверждение менеджеров {{ yandex-cloud }}. 

После того, как вы нажмете кнопку **{{ ui-key.yacloud.billing.accounts.button_empty-billing-create }}** на странице **{{ ui-key.yacloud.billing.account.create-new.label_title }}**, платежный аккаунт будет создан в статусе `PAYMENT_NOT_CONFIRMED`. На вашу почту, указанную в аккаунте Яндекса или Яндекс 360, будет отправлено письмо с описанием дальнейших действий. Активация может занять до трех рабочих дней.

#### Почему после создания платежного аккаунта я не получил письмо с описанием дальнейших действий?  {#account-notification}

Активация платежного аккаунта может занять до трех рабочих дней.
Если в течение этого времени вы так и не получили письмо, отправьте запрос на электронную почту [cloud_docs@support.yandex.ru](mailto:cloud_docs@support.yandex.ru).

В запросе укажите полное название организации и [идентификатор платежного аккаунта](../../billing/concepts/billing-account.md#billing-account-id), а также прикрепите копию свидетельства о регистрации организации (с переводом на английский или русский язык).