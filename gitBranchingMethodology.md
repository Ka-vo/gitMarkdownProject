# Методологии ветвления

1. **Central Workflow** - одна ветка master, все изменения комитятся в нее. Подходит для одиночного проекта.</br>
2. **Developer branch Workflow** - у каждого разработчика есть своя ветка или несколько. Вся разработка ведется в них, но потом должна быть слита в одну главную ветвь. Подходит для небольшого проекта с малым количеством разработчиков.</br>
3. **Feature branch Workflow** - в репозитории есть второстепенная основная ветка (dev) с рабочим кодом. Фичи[^1] начинают свой код от этой ветки. Подходит, если команда использует какой-то метод управления проектами.</br>
4. **Issure branch Workflow** - очень похожа на Feature branch Workflow, но ветки создаются по задачам, а не по фичам(каждая фича состоит из разных задач).</br>
5. **Forking Workflow** - есть два репозитория, в первый - оригинальный сливаются все изменения. Второй - форк репозиторий является копией оригинального репозитория. Находится во владении разработчика, который хочет внести изменения в оригинальный репозиторий. Используется в проектах с открытым кодом.</br>
6. **GitHub flow** - код в master работоспособный и готов к развертыванию в любое время. Все изменения идут в отдельных ветках, созданных от master. После изменения, его проверяет руководитель команды и еще один специалист. После успешной проверки, изменения вливают в проект.</br>
7. **Gitflow** - две постоянные ветки:</br>

- _Master_ - стабильная ветка, доступная пользователям. В ней напрямую изменения не производятся.
- _Developer_ - для разработки. При большом количестве изменений, из developer создается release[^2] - ветка. Feature - ветки берут начало от develop. Также используются ветки hotfix[^3].</br>

---

[^1]: Функциональные ветки. В методологии Gitflow сливаются в dev.</br>
[^2]: Подготовка стабильного кода, для публикации пользователям. Сливается в prod и dev.</br>
[^3]: Быстрое решение критических проблем prod. Сливается в prod и dev.
