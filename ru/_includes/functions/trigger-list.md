{% list tabs %}

- Консоль управления

    1. В [консоли управления]({{ link-console-main }}) перейдите в каталог, в котором хотите посмотреть список триггеров.
    1. Выберите сервис **{{ ui-key.yacloud.iam.folder.dashboard.label_serverless-functions }}**.
    1. На панели слева выберите ![image](../../_assets/console-icons/gear-play.svg) **{{ ui-key.yacloud.serverless-functions.switch_list-triggers }}**.

- CLI

    {% include [cli-install](../cli-install.md) %}

    {% include [default-catalogue](../default-catalogue.md) %}

    Получите список триггеров:

    ```bash
    yc serverless trigger list
    ```

    Результат:

    ```text
    +----------------------+------------+----------------------+
    |          ID          |    NAME    |      FOLDER ID       |
    +----------------------+------------+----------------------+
    | dd0gj5tsj2********** | my-trigger | aoek49ghmk********** |
    +----------------------+------------+----------------------+
    ```

- API

  Чтобы получить список триггеров, воспользуйтесь методом REST API [list](../../functions/triggers/api-ref/Trigger/list.md) для ресурса [Trigger](../../functions/triggers/api-ref/Trigger/index.md) или вызовом gRPC API [TriggerService/List](../../functions/triggers/api-ref/grpc/trigger_service.md#List).

{% endlist %}
