# NET.S.2017.Yarosh.09

Разработать класс Book с 4-5 свойствами, переопределив для него необходимые методы класса Object. Для объектов класса реализовать отношения эквивалентности и порядка. Для выполнения основных операций со списком книг, который можно загрузить и, если возникнет необходимость, сохранить в некоторое хранилище BookListStorage разработать класс BookListService (как сервис для работы с коллекцией книг) с функциональностью AddBook (добавить книгу, если такой книги нет, в противном случае выбросить исключение); RemoveBook (удалить книгу, если она есть, в противном случае выбросить исключение); FindBookByTag (найти книгу по заданному критерию); SortBooksByTag (отсортировать список книг по заданному критерию). 
Работу классов продемонстрировать на примере консольного приложения. 
В качестве хранилища использовать
- двоичный файл, для работы с которым использовать только классы BinaryReader, BinaryWriter. Хранилище в дальнейшем может измениться (добавиться).
- двоичный файл, для работы с которым использовать двоичный сериализатор;
- XML-файл (любая технология без ограничений).
<hr>
Для приложения с сервисом книг (Day 9) реализовать возможность логирования сообщений различного уровня, предусмотрев возможность использования различных фреймворков.


