<div>
  <h2>Маршрут: С.Петербург - Житомир</h2>
  <p>Имеется транспортная сеть, связывающая города СНГ. Сеть представлена в виде таблицы связей между городами. Связи являются двусторонними, т.е. допускают движение в обоих направлениях. Необходимо проложить маршрут из одной заданной точки в другую.</p>
  <h3>Этап 1. Неинформированный поиск.</h3>
  <p>На этом этапе известна только топология связей между городами. Выполнить:</p>
  <ol>
    <li>Поиск в ширину;</li>
    <li>Поиск глубину;</li>
    <li>Поиск с ограничением глубины;</li>
    <li>Поиск с итеративным углублением;</li>
    <li>Двунаправленный поиск.</li>
  </ol>
  <p>Отобразить движение по дереву на его графе с указанием сложности каждого вида поиска. Сделать выводы.</p>
  <h3>Этап 2. Информированный поиск.</h3>
  <p>Воспользовавшись информацией о протяженности связей от текущего узла, выполнить:</p>
  <ol>
    <li>Жадный поиск по первому наилучшему соответствию;</li>
    <li>Затем, использую информацию о расстоянии до цели по прямой от каждого узла, выполнить поиск методом минимизации суммарной оценки А*.</li>
  </ol>
  <p>Отобразить на графе выбранный маршрут и сравнить его сложность с неинформированным поиском. Сделать выводы.</p>
</div>

![Граф](https://user-images.githubusercontent.com/70958074/227378041-48a86227-14e1-46da-9f1e-55d68f5e0c2b.png)
