# Clean-code
Здесь будут храниться все требования к коду


 1.*Название PR,коммиты
Название PR должно выглядеть так: "Лабораторная работа №(Номер лабы)". Только в именительном подеже.
* Описательные сообщения коммитов: Напишите информативное и содержательное сообщение коммита, которое четко описывает внесенные изменения. Избегайте слишком общих или запутанных описаний. Хорошее сообщение коммита помогает другим разработчикам и вам самим понять, какие изменения были внесены в код.
* Маленькие и логические коммиты: Разбивайте большие изменения на маленькие и логические коммиты. Каждый коммит должен вносить только одно изменение или решать одну задачу. Это позволяет легче просматривать историю изменений, откатывать или вносить изменения в отдельные коммиты.
*  Избегайте коммитирования незавершенной работы: Коммитируйте только те изменения, которые полностью функциональны и прошли тестирование. Не коммитируйте незавершенный или испорченный код, так как это может затруднить работу других разработчиков и создать проблемы в будущем.
  2.*main. cpp
   Файл с кодом должен носить только такое название и иметь только такое расширение
  3.*Для изменения PR, меняем файл в локальной репозитории
  4.*В GIT, при переменовании, меняетя путь к файлу
  5.*Если лабораторная требует разбиения на так называемые под задачи, то необходимо называть файл следующим образом: main_название задания_.cpp
  6.*Всегда использовать префиксное инкрементирование и декрементирорвание
  7.*В конце кода принято оставлять одну пустую строку
  8.*При записи условия в файл необходимо отступить на расстояние раввное tab
  9.*Имена функций и переменных
  *Переменные: Имена переменных (включая параметры функций) и членов данных пишутся строчными буквами с подчёркиванием между словами. Члены данных классов (не структур) дополняются подчёркиванием в конце имени. По крайней мере, пользователь должен понимать с какой переменной он работает, а полное понимание этого достигается правильным наименованием переменной напрямую связанным с целью этой переменной.
   *Функции: Обычные функции именуются в смешанном стиле (прописные и строчные буквы); функции доступа к переменным (accessor и mutator) должны иметь стиль, похожий на целевую переменную.Обычно имя функции начинается с прописной буквы и каждое слово в имени пишется с прописной буквы.
void AddTableEntry();
void DeleteUrl();
void OpenFileOrDie();
(Аналогичные правила применяются для констант в области класса или пространства имён (namespace) которые представляют собой часть API и должны выглядеть как функции (и то, что они не функции — некритично))
  10.*Всегда используем {} при работе с циклами и условиями
  11.*Объявления переменных отдельно и всегда присваиваем значения: int a = 0;
