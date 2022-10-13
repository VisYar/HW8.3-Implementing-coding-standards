# Задание 3*. Внедряем стандарты кодирования (необязательная задача)

[CheckStyle](https://checkstyle.sourceforge.io/) и [Maven Plugin для него](https://maven.apache.org/plugins/maven-checkstyle-plugin/usage.html) предоставляют возможность производить проверки, чтобы выявить соответствия стиля написания кода заданным стандартам.

Стандарты в организации формируют ведущие программисты, и от организации к организации стандарты могут отличаться.

Мы будем использовать [Google Java Style Guide](https://checkstyle.sourceforge.io/styleguides/google-java-style-20180523/javaguide.html).

Используйте приложенный файл [checkstyle.xml](https://raw.githubusercontent.com/netology-code/javaqa2-homeworks/main/files/checkstyle.xml) в качестве набора правил. Положите его в корень проекта и укажите в качестве настройки `configLocation`.

Ваша задача
1. Подключить плагин к вашему проекту. Возьмите проект из первой задачи или создайте новый на его базе.
1. Настроить goal `check` в фазу `verify`.
1. Удостовериться, что код не проходит проверки CheckStyle, фиксить не нужно.
1. Сделать push в GitHub и удостовериться, что сборка не проходит именно по причине наличия ошибок CheckStyle.
