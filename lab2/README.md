# LAB 2 Razor Pages

Цель лабораторной - освоение движка серверного рендеринга Razor и технологии Razor Pages.

## Допущения и ограничения

1. Работа выпоняется на языке C# в среде Visual Studio.
2. Данные в работе будут сохраняться в файловой системе.
3. Для организации доступа к данным из веб-страниц будет использоваться специализированный класс - репозитарий.
4. Репозитарий пробрасывается в код страницы через механизм внерения зависимостей.
5. В коде cshtml реализуется только логика разметки, бизнес-логика реализуется в codebehind файле.

## Последовательность выполнения

1. Выберите вариант задания, выданный преподавателем.
2. Определите класс данных и сопутствующие типы в файле DataClass. Переименуйте класс средствами рефакторинга. 
3. Напишите код сериализации / десериализации данных в файловой системе  используя схему описанную в комментариях.
4. Зарегистрируйте репозитарий в подсистеме DI в классе Startup как singleton.
5. Добавьте тестовые данные в файл.
6. Реализуйте разметку и поведение страницы просмотра списка данных.
7. Реализуйте разметку и поведение страницы добавления нового элемента.
8. Добавьте и реализуйте разметку и поведение страницы редактирования элемента.
9. Добавьте и реализуйте поведение страницы удаления элемента.
10. Реализуйте навигацию между страницами и протестируйте приложение.

## Варианты задания

1. Список дел (атрибуты: строка-тема, флаг выполнено/невыполнено, число-приоритет)
2. Список занятий (атрибуты: строка-дисциплина, дата, форма заниятия - лабораторная, лекция, практика)
3. Меню на неделю (атрибуты: название блюда, день недели, время приема пищи - завтрак, обед, ужин).
4. Список студентов группы (атрибуты: строка-ФИО, номер зачетки, флаг староста)
5. Список композиций (атрибуты: строка-название песни, исполнитель, авторы музыки, авторы текста, число-рейтинг)
6. Список фильмов (атрибуты: строка-название, режиссер, число-рейтинг)
7. Список языков программирования (атрибуты: строка-название, вид (функциональный, императивный, логический, другой), число-рейтинг)
8. Список сотрудников (атрибуты: строка-ФИО, должность, флаг увольнения, число-оклад)