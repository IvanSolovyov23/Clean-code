# Clean-code
Здесь будут храниться все требования к коду


##### 1.Название PR,коммиты
Название PR должно выглядеть так: "Лабораторная работа №(Номер лабы)". Только в именительном подеже.
* Описательные сообщения коммитов: Напишите информативное и содержательное сообщение коммита, которое четко описывает внесенные изменения. Избегайте слишком общих или запутанных описаний. Хорошее сообщение коммита помогает другим разработчикам и вам самим понять, какие изменения были внесены в код.
 ##### 2. main. cpp
   Файл с кодом должен носить только такое название и иметь только такое расширение.
 ##### 3.Для изменения PR, меняем файл в локальной репозитории.
 ##### 4.В GIT, при переменовании, меняетя путь к файлу.
 ##### 5.Если лабораторная требует разбиения на, так называемые подзадачи, то необходимо называть файл следующим образом: main_название задания_.cpp.
 ##### 6. main_func.cpp при разбиении на файлы.
 ##### 7. Любое изменинея = новый коммит.
 ##### 8.Всегда использовать префиксное инкрементирование и декрементирорвание.
 ```c++
a = 1;                     a = 1;
a++;                       ++a;
(temp = a;                (a+=1;                          
a+=1;                      return a;)
return temp;)                        
```
 ##### 9.В конце кода принято оставлять одну пустую строку.
  ```c++
 7121. return 0;
 7122.}
 7123.

```
 ##### 10. Условие в файле
```
*/ tab ----------------------------------------
       ----------------------------------------
       ----------------------------------------
*/
```
 ##### 11. Передача size:
 1) const size_t& size;   2) size_t size;
 ##### 12.Имена функций
  * Функции: Обычные функции именуются в смешанном стиле (прописные и строчные буквы); 
 ```c++
 void AddTableEntry();
 void DeleteUrl();
 void OpenFileOrDie();
 
```
Так же стоит помнить, что функция выполнять только одно действие.
##### 13. Передаём int**& mtr по ссылке.
##### 14.Всегда используем {} при работе с циклами и условиями.
##### 15.Если много аргументов в функции, то её следует записать в таком виде:
```с++
void func
 (
   список аргументов;
   список аргументов;
   -
   -
 )
```
Отступ должен быть равен tab.
##### 16.
 ##### 11.Объявления переменных отдельно и всегда присваиваем значения: 
```c++
int a = 0;
 
```
 ##### 12. Правила комментирования:
 
  * Не используй комментарии, если ты можешь использовать функцию или переменную вместо этого.
  * Не комментируй плохой код — перепиши его. Не стоит объяснять, что происходит в плохом коде, лучше сделать его явным и понятным.
  * Комментарии можно использовать для передачи какой-то информации, предупреждения о последствиях, но не для объяснения того, как работает код.
  * Используй TODO и FIXME в тех случаях, когда нужно пометить, что код нуждается в доработке, но сейчас нет ресурсов на это.
  * Используй //region REGIONNAME //endregion REGIONNAME, а если используешь, то подумай можно ли разделить region на сущности.
  * Документируй код, который является сложным, но чистым.
  * Не оставляй старый закомментированный код. Ты можешь найти его в истории коммитов, если необходимо.
  * Комментарии должны быть краткими и понятными. В комментариях с информацией не должно быть много информации. Все должно быть кратко и по делу.
##### 13. Goto
  * Первое правило Критопанков: не использовать goto
  * Второе правило Криптопанков: не использовать НИГДЕ goto
  * Третье правило Криптопанков: Оставить goto в 1967
##### 14. Логическое разделение кода.



