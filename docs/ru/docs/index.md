



<p align="center">
  <a href="https://fastapi.tiangolo.com"><img src="https://fastapi.tiangolo.com/img/logo-margin/logo-teal.png" alt="FastAPI"></a>
</p>
<p align="center">
    <em>FastAPI — высокопроизводительный фреймворк, легкий в изучении, позволяющий быстрое написание кода, готовый к использованию</em>
</p>
<p align="center">
<a href="https://travis-ci.com/tiangolo/fastapi" target="_blank">
    <img src="https://travis-ci.com/tiangolo/fastapi.svg?branch=master" alt="Build Status">
</a>
<a href="https://codecov.io/gh/tiangolo/fastapi" target="_blank">
    <img src="https://img.shields.io/codecov/c/github/tiangolo/fastapi" alt="Coverage">
</a>
<a href="https://pypi.org/project/fastapi" target="_blank">
    <img src="https://badge.fury.io/py/fastapi.svg" alt="Package version">
</a>
</p>

---

**Документация**: <a href="https://fastapi.tiangolo.com" target="_blank">https://fastapi.tiangolo.com</a>

**Исходный код**: <a href="https://github.com/tiangolo/fastapi" target="_blank">https://github.com/tiangolo/fastapi</a>

---

FastAPI является современным, быстродейственным (высокопроизводительным) веб-фреймворком для создания API с помощью Python 3.6+, основанным на стадартных аннотациях типов в Python.

Основные возможности:

* **Быстродействие**: Имеет очень высокую производительность, сравнимую с  **NodeJS** и **Go** (благодаря Starlette и Pydantic). [Один из самых производительных фреймворков из доступных ](#performance).

* **Быстрота написания кода**: Ускоряет процесс добавления нового функционала на 200%-300%.*
* **Меньше ошибок**: Позволяет уменьшить вероятность человеческой ошибки (допущенной разработчиком) приблизительно на 40%. *
* **Удобство**: Превосходно поддерживается редактором. <abbr title="also known as auto-complete, autocompletion, IntelliSense">Автодополнение</abbr> в любом месте. Требуется меньше времени на поиск и исправление ошибок.
* **Простота**: Специально разработан с упором на простоту в понимании и использовании. Не требуется много времени на изучение документации.
* **Краткость**: Минимизирует повторение элементов кода. Каждый объявленный параметр способен иметь множество функций. Уменьшает количество ошибок.
* **Полноценность**: Производит готовое к использованию ПО с автоматически сгененрированной интерактивной документацией.
* **Соответствие стандартам**: Основан на открытых стандартах для API и полностью с ними совместим: <a href="https://github.com/OAI/OpenAPI-Specification" class="external-link" target="_blank">OpenAPI</a> (ранее известный как Swagger) и <a href="https://json-schema.org/" class="external-link" target="_blank">JSON-схема</a>.

<small>* Оценка основана на результатах тестов, проведенных с группой разработчиков внутри компании, ответственных за прикладное ПО.</small>

## Gold Sponsors

<!-- sponsors -->

{% if sponsors %}
{% for sponsor in sponsors.gold -%}
<a href="{{ sponsor.url }}" target="_blank" title="{{ sponsor.title }}"><img src="{{ sponsor.img }}"></a>
{% endfor %}
{% endif %}

<!-- /sponsors -->

<a href="https://fastapi.tiangolo.com/fastapi-people/#sponsors" class="external-link" target="_blank">Other sponsors</a>

## Отзывы

"_[...] Я пользуюсь **FastAPI** очень часто в последнее время. Я даже планирую использовать его для всех **сервисов машинного обучения Microsoft**, создаваемых моей командой. Некоторые из этих сервисов будут встраиваться в базовый продукт **Windows**, и некоторые  приложения **Office**._"

<div style="text-align: right; margin-right: 10%;">Kabir Khan - <strong>Microsoft</strong> <a href="https://github.com/tiangolo/fastapi/pull/26" target="_blank"><small>(ref)</small></a></div>

---

"_Мы взяли на вооружение библиотеку **FastAPI** чтобы создавать **REST** сервера, которые могут принимать запросы и возвращать **прогнозы**. [для Людвига]_"

<div style="text-align: right; margin-right: 10%;">Piero Molino, Yaroslav Dudin, и Sai Sumanth Miryala - <strong>Uber</strong> <a href="https://eng.uber.com/ludwig-v0-2/" target="_blank"><small>(ref)</small></a></div>

---

"_**Netflix** с радостью сообщает о запуске нашего открытого фреймворка оркестрации для **кризис-менеджмента**: **Dispatch**!_"

<div style="text-align: right; margin-right: 10%;">Kevin Glisson, Marc Vilanova, Forest Monsen - <strong>Netflix</strong> <a href="https://netflixtechblog.com/introducing-dispatch-da4b8a2a8072" target="_blank"><small>(ref)</small></a></div>

---

"_Я безумно восхищаюсь **FastAPI**. Это так круто!_"

<div style="text-align: right; margin-right: 10%;">Brian Okken - <strong><a href="https://pythonbytes.fm/episodes/show/123/time-to-right-the-py-wrongs?time_in_sec=855" target="_blank">Python Bytes</a> podcast host</strong> <a href="https://twitter.com/brianokken/status/1112220079972728832" target="_blank"><small>(ref)</small></a></div>

---

"_Если честно, то, что вы создали выглядит просто замечательно и доведено до совершенства. По многим параметрам, это именно то, каким я бы хотел видеть **Hug** -  очень воодушевляет тот факт, что кто-то сделал что-то подобное._ "

<div style="text-align: right; margin-right: 10%;">Timothy Crosley - <strong><a href="https://www.hug.rest/" target="_blank">Hug</a> creator</strong> <a href="https://news.ycombinator.com/item?id=19455465" target="_blank"><small>(ref)</small></a></div>

---

"_Если вы ищете, какой **современный фреймворк** лучше всего изучить для создания REST API, взгляните на **FastAPI**. Он производительный, легкий в использовании и изучении [...]_"

"_Мы перешли на **FastAPI** для наших **API** [...]. Я думаю, что вам понравится [...]_"

<div style="text-align: right; margin-right: 10%;">Ines Montani - Matthew Honnibal - <strong><a href="https://explosion.ai" target="_blank">Explosion AI</a> founders - <a href="https://spacy.io" target="_blank">spaCy</a> creators</strong> <a href="https://twitter.com/_inesmontani/status/1144173225322143744" target="_blank"><small>(ref)</small></a> - <a href="https://twitter.com/honnibal/status/1144031421859655680" target="_blank"><small>(ref)</small></a></div>

---

## **Typer**, FastAPI среди интерфейсов командных строк

<a href="https://typer.tiangolo.com" target="_blank"><img src="https://typer.tiangolo.com/img/logo-margin/logo-margin-vector.svg" style="width: 20%;"></a>

Если Ваша цель - создание приложения c <abbr title="Command Line Interface">интерфейсом командной строки</abbr> вместо Веб-API, оцените <a href="https://typer.tiangolo.com/" class="external-link" target="_blank">**Typer**</a>.

**Typer** - младший брат FastAPI. Поэтому он создавался для того, чтобы быть **FastAPI среди интерфейсов командных строк**. ⌨️ 🚀

## Требования

Python 3.6+

FastAPI стоит на плечах гигантов:

* <a href="https://www.starlette.io/" class="external-link" target="_blank">Starlette</a> for the web parts.
* <a href="https://pydantic-docs.helpmanual.io/" class="external-link" target="_blank">Pydantic</a> for the data parts.

## Установка

<div class="termy">

```console
$ pip install fastapi

---> 100%
```

</div>

Вам также понадобится ASGI сервер для работы сервисов, таких как <a href="https://www.uvicorn.org" class="external-link" target="_blank">Uvicorn</a> or <a href="https://gitlab.com/pgjones/hypercorn" class="external-link" target="_blank">Hypercorn</a>.

<div class="termy">

```console
$ pip install uvicorn[standard]

---> 100%
```

</div>

## Пример

### Создание

* Создайте файл `main.py` с содержанием:

```Python
from typing import Optional

from fastapi import FastAPI

app = FastAPI()


@app.get("/")
def read_root():
    return {"Hello": "World"}


@app.get("/items/{item_id}")
def read_item(item_id: int, q: Optional[str] = None):
    return {"item_id": item_id, "q": q}
```

<details markdown="1">
<summary>Или используйте <code>async def</code>...</summary>

Если Ваш в вашем коде встречается `async` / `await`, используйте `async def`:

```Python hl_lines="9  14"
from typing import Optional

from fastapi import FastAPI

app = FastAPI()


@app.get("/")
async def read_root():
    return {"Hello": "World"}


@app.get("/items/{item_id}")
async def read_item(item_id: int, q: Optional[str] = None):
    return {"item_id": item_id, "q": q}
```

**Note**:

Если Вы не уверены, смотрите раздел _"Торопитесь?"_ в документации о функциях<a href="https://fastapi.tiangolo.com/async/#in-a-hurry" target="_blank">`async` и `await`.</a>.

</details>

### Запуск

Запустите сервер следующей командой:

<div class="termy">

```console
$ uvicorn main:app --reload

INFO:     Uvicorn running on http://127.0.0.1:8000 (Press CTRL+C to quit)
INFO:     Started reloader process [28720]
INFO:     Started server process [28722]
INFO:     Waiting for application startup.
INFO:     Application startup complete.
```

</div>

<details markdown="1">
<summary>О команде <code>uvicorn main:app --reload</code>...</summary>

Команда `uvicorn main:app` относится к:

* `main`: файл `main.py` ("модуль" Python).
* `app`: объект, созданный внутри `main.py` строкой `app = FastAPI()`.
* `--reload`: заставляет сервер перезапускаться после каждого изменения в коде. Используется только на стадии разработки.

</details>

### Проверка

Откройте в браузере данную страницу: <a href="http://127.0.0.1:8000/items/5?q=somequery" class="external-link" target="_blank">http://127.0.0.1:8000/items/5?q=somequery</a>.

Вы увидите JSON-отклик в виде:

```JSON
{"item_id": 5, "q": "somequery"}
```

На этом этапе, Вы уже создали API, который:

* Получает HTTP-запросы по _адресам_ `/` и `/items/{item_id}`.
* Оба _адреса_ получают `GET` <em>команды</em> (также известные как _методы_ HTTP).
* _Путь_ `/items/{item_id}` имеет _параметр пути_ `item_id`, который должен быть типа `int`.
* _Путь_ `/items/{item_id}` имеет необязательный _параметр запроса_ `q` типа `str`.

### Интерактивная API-документация

Теперь перейдите на <a href="http://127.0.0.1:8000/docs" class="external-link" target="_blank">http://127.0.0.1:8000/docs</a>.

Вы увидите автоматически сгенерированную интерактивную API-документацию (посредством <a href="https://github.com/swagger-api/swagger-ui" class="external-link" target="_blank">Swagger UI</a>):

![Swagger UI](https://fastapi.tiangolo.com/img/index/index-01-swagger-ui-simple.png)

### Альтернативная API-документация

А теперь, перейдите на <a href="http://127.0.0.1:8000/redoc" class="external-link" target="_blank">http://127.0.0.1:8000/redoc</a>.

Вы увидите альтернативную автоматически сгенерированную документацию (посредством <a href="https://github.com/Rebilly/ReDoc" class="external-link" target="_blank">ReDoc</a>):

![ReDoc](https://fastapi.tiangolo.com/img/index/index-02-redoc-simple.png)

## Дальнейшее усовершенствование примера

Теперь измените файл `main.py` таким образом, чтобы принимать тело `PUT` запроса.

Объявите тело запроса, используя стандартные типы данных Python - благодаря Pydantic.

```Python hl_lines="4  9-12  25-27"
from typing import Optional

from fastapi import FastAPI
from pydantic import BaseModel

app = FastAPI()


class Item(BaseModel):
    name: str
    price: float
    is_offer: Optional[bool] = None


@app.get("/")
def read_root():
    return {"Hello": "World"}


@app.get("/items/{item_id}")
def read_item(item_id: int, q: Optional[str] = None):
    return {"item_id": item_id, "q": q}


@app.put("/items/{item_id}")
def update_item(item_id: int, item: Item):
    return {"item_name": item.name, "item_id": item_id}
```

Сервер должен перезагрузиться автоматически (поскольку Вы добавили `--reload` к команде `uvicorn` выше).

### Усовершенствование интерактивной API-документации

Теперь перейдите на <a href="http://127.0.0.1:8000/docs" class="external-link" target="_blank">http://127.0.0.1:8000/docs</a>.

* Интерактивная документация автоматически обновится, включая добавленную часть кода:

![Swagger UI](https://fastapi.tiangolo.com/img/index/index-03-swagger-02.png)

* Нажмите кнопку "Try it out", это позволит вам заполнить поля параметров и напрямую взаимодействовать с API:

![Swagger UI interaction](https://fastapi.tiangolo.com/img/index/index-04-swagger-03.png)

* Теперь нажмите кнопку "Execute", пользовательский интерфейс свяжеться с Вашим API, передаст параметры, получит результаты, и отобразит их на экране:

![Swagger UI interaction](https://fastapi.tiangolo.com/img/index/index-05-swagger-04.png)

### Усовершенствование альтернативной API-документации

Теперь перейдите на <a href="http://127.0.0.1:8000/redoc" class="external-link" target="_blank">http://127.0.0.1:8000/redoc</a>.

* Альтернативная документация также отразит новые параметры запроса и добавленный код:

![ReDoc](https://fastapi.tiangolo.com/img/index/index-06-redoc-02.png)

### Итог

Таким образом, Вы объявляете **однократно** типы параметров, тело и т.д. как параметры функций. 


Вы делаете это с помощью стандартных современных типов данных Python.

Вам не нужно изучать новый синтаксис, методы, или классы конкретной библиотеки и т.д.

Лишь стандартный **Python 3.6+**.

К примеру, для `int`:

```Python
item_id: int
```

или для более сложной модели `Item`:

```Python
item: Item
```

...и с этим разовым объявлением Вы получаете:

* Поддержку в редакторе, включая:
    * Дополнение.
    * Проверку написания.
* Валидацию данных:
    * Автоматические и ясные сообщения об ошибках когда формат данных недопустимый.
    * Валидация даже для глубоко вложенных JSON-объектов.
* <abbr title="также известная как: сериализация, парсинг, маршалинг">Конверсия</abbr> входных данных: с сетевых в стандартные данные и типы Python. Считываются с:
    * JSON.
    * Параметров пути.
    * Параметров запроса.
    * Cookies.
    * Заголовки.
    * Forms.
    * Формы.
* <abbr title="также известная как: сериализация, парсинг, маршалинг">Конверсия</abbr> выходных данных: конвертирование стандартных данных и типов Python в сетевые (такие как JSON):
    * Конверсия типов Python (`str`, `int`, `float`, `bool`, `list`, etc).
    * `datetime` объекты.
    * `UUID` объекты.
    * Модели баз данных.
    * ...и многое другое.
* Автоматическая интерактивная API-документация, включающая вы себя 2 альтернативных пользовательских интерфейса:
    * Swagger UI.
    * ReDoc.

---

Возвращаясь к предыдущему примеру программы, **FastAPI** будет:

* Проверять, чтобы `item_id` существовал в адресе `GET` и `PUT` запросов.
* Проверять, чтобы `item_id` был типа `int` для `GET` и `PUT` запросов.
    * Если это не так, клиент увидит понятное и ясное сообщение об ошибке.
* Проверять, если существует необязательный параметр с именем `q` (как в `http://127.0.0.1:8000/items/foo?q=somequery`) для запросов `GET`.
    * Поскольку параметр `q` объявлен с `= None`, он необязателен.
    * Без `None` он являлся бы обязательным (как тело в случае с `PUT`).
* Для `PUT` запросов на `/items/{item_id}`, читать тело как JSON:
    * Проверяя, чтобы оно имело обязательный атрибут `name`, и он был типа `str`. 
    * Проверяя, чтобы оно имело обязательный атрибут `price`, и он был типа `float`.
    * Проверяя, имеет ли оно необязательный атрибут `is_offer`, и он был типа `bool`, если он имеется.
    * Все вышеуказанное также работает для глубоко вложенных JSON-объектов.
* Конвертировать в и из JSON автоматически.
* Все документировать посредством OpenAPI, что впоследствии может быть использовано:
    * Интерактивными системами документации.
    * Автоматическими системами генерации клиентского кода, для многих языков.
* Предоставлять 2 интерактивные версии веб-интерфейсов документации напрямую.

---

Это все лишь капля в море, но у Вас уже есть представление о том, как это все работает.

Попробуйте заменить строку, содержащую:

```Python
    return {"item_name": item.name, "item_id": item_id}
```

...вместо:

```Python
        ... "item_name": item.name ...
```

...вставьте:

```Python
        ... "item_price": item.price ...
```

...и посмотрите, как редактор автоматически дополнит атрибуты, зная их типы:

![editor support](https://fastapi.tiangolo.com/img/vscode-completion.png)

Для более полного примера, включающего больше функций, смотрите <a href="https://fastapi.tiangolo.com/tutorial/">Обучение - Руководство Пользователя</a>.

**Осторожно, спойлер**: Обучение - руководство пользователя включает:

* Объявление **параметров** из различных мест, таких как: **заголовки**, **cookies**, **поля**, и **файлы**.
* Как задать **ограничения валидации**, вроде `maximum_length` или `regex`.
* Очень мощная и легкая в использовании система **<abbr title="also known as components, resources, providers, services, injectables">Внедрения Зависимости</abbr>**.
* Безопасность и аутентификация, включая поддержку **OAuth2** с **JWT tokens** и **HTTP Basic**.
* Более продвинутые (но все такие же простые) методы объявления **глубоко вложенных JSON-моделей** (благодаря Pydantic).
* Множество дополнительных функций (благодаря Starlette), таких как:
    * **WebSockets**
    * **GraphQL**
    * совершенно простые в использовании тесты, основанные на `requests` и `pytest`
    * **CORS**
    * **Cookie Sessions**
    * ...и многое другое.

## Результативность

Независимые тесты производительности TechEmpower показывают приложения **FastAPI**  запущенные под Uvicorn как <a href="https://www.techempower.com/benchmarks/#section=test&runid=7464e520-0dc2-473d-bd34-dbdfd7e85911&hw=ph&test=query&l=zijzen-7" class="external-link" target="_blank">один из самых быстродейственных фреймворков Python из доступных</a>, уступающих только самим Starlette и Uvicorn (оба используются внутри FastAPI). (*)

Чтобы узнать больше, смотрите раздел <a href="https://fastapi.tiangolo.com/benchmarks/" class="internal-link" target="_blank">Тесты производительности</a>.

## Дополнительные библиотеки

Используется Pydantic:

* <a href="https://github.com/esnme/ultrajson" target="_blank"><code>ujson</code></a> - для более быстрого JSON <abbr title="converting the string that comes from an HTTP request into Python data">"парсинга"</abbr>.
* <a href="https://github.com/JoshData/python-email-validator" target="_blank"><code>email_validator</code></a> - для email-валидации.

Используется Starlette:

* <a href="https://requests.readthedocs.io" target="_blank"><code>requests</code></a> - Требуется, если Вы хотите испаользовать `TestClient`.
* <a href="https://github.com/Tinche/aiofiles" target="_blank"><code>aiofiles</code></a> - Требуется, если Вы хотите использовать `FileResponse` или `StaticFiles`.
* <a href="https://jinja.palletsprojects.com" target="_blank"><code>jinja2</code></a> - Требуется, если Вы хотите использовать конфигурацию шаблона по умолчанию.
* <a href="https://andrew-d.github.io/python-multipart/" target="_blank"><code>python-multipart</code></a> - Требуется, если Вы хотите иметь поддержку <abbr title="converting the string that comes from an HTTP request into Python data">"парсинга"</abbr> формы, с `request.form()`.
* <a href="https://pythonhosted.org/itsdangerous/" target="_blank"><code>itsdangerous</code></a> - Требуется для поддержки `SessionMiddleware`.
* <a href="https://pyyaml.org/wiki/PyYAMLDocumentation" target="_blank"><code>pyyaml</code></a> - Треубется для поддержки Starlette `SchemaGenerator` (Наверное, Вам это не потребуется в FastAPI).
* <a href="https://graphene-python.org/" target="_blank"><code>graphene</code></a> - Треубется для поддержки `GraphQLApp`.
* <a href="https://github.com/esnme/ultrajson" target="_blank"><code>ujson</code></a> - Требуется, если вы хотите использовать `UJSONResponse`.

Используется FastAPI / Starlette:

* <a href="https://www.uvicorn.org" target="_blank"><code>uvicorn</code></a> - необходимо для сервера, который загружает и запускает Ваше приложение.
* <a href="https://github.com/ijl/orjson" target="_blank"><code>orjson</code></a> - Требуется, если Вы хотите использовать `ORJSONResponse`.

Вы можете установить все вышеперечисленное с помощью `pip install fastapi[all]`.

## Лицензия

Этот проект лицензирован в соответствии с условиями лицензии MIT.
