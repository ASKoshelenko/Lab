## Хорошая практика составления сообщений к коммитам в Git

### Резюме
- **Цель**: Улучшение качества истории изменений в Git.
- **Подход**: Структурное разделение изменений и информативное описание в сообщениях коммитов.

### Структурное разделение изменений
- **Одно логическое изменение на коммит**: Это упрощает ревью и позволяет точнее отслеживать изменения.
- **Избегайте**:
  - Смешивания изменений пробелов с функциональными изменениями.
  - Смешивания несвязанных функциональных изменений.
  - Отправки больших новых функций одним коммитом.

### Примеры плохой практики
- **Пример 1**: Смешивание двух независимых изменений в одном коммите.
- **Пример 2**: Отправка большой новой функции одним гигантским коммитом.

### Примеры хорошей практики
- **Пример 1**: Разделение внесения новой функции на несколько коммитов, начиная с рефакторинга существующего кода.
- **Пример 2**: Явное разделение изменения конфигурации и добавления новых функций.

### Информация в сообщениях коммитов
- **Включение внешних ссылок**: Должны быть информативны и самодостаточны, не требующие доступа к внешним ресурсам.
- **Структура сообщения коммита**:
  1. Краткое описание изменений в первой строке.
  2. Подробное описание изменений после одной пустой строки.
  3. Ссылки на задачи, баги или флаги влияния на документацию в конце сообщения.

### Некоторые примеры плохой практики
- **Пример 1**: Недостаточно информации о том, какие импорты были добавлены и почему.
- **Пример 2**: Отсутствие описания текущего формата и того, что исправлено.

### Некоторые примеры хорошей практики
- **Пример 1**: Четкое разделение обновления политик по умолчанию и добавления поддержки новых функций.
- **Пример 2**: Детальное описание добавленной функции и проведенных тестов.

### Общие рекомендации
- **Подробно описывайте, что изменено и почему**.
- **Сообщения должны быть понятны без дополнительных внешних источников**.
- **Используйте информацию о багах, блюпринтах и влиянии на документацию для уточнения деталей**.
- **Используйте 'Test Plan' для описания проведенных тестов**.

Эти рекомендации помогут улучшить понимание и качество вашей работы с Git, делая историю изменений более понятной и полезной для всех участников проекта.