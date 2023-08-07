# Відповіді на питання співбесіди на PHP програміста (українською)

У цьому репозиторії будуть зібрані відповіді на питання які ставлять на сбівбесідах PHP розробникам [опублікованих на порталі dou](https://dou.ua/lenta/articles/interview-questions-php-developer/).
Нижче буде наведено таблицю з питаннями, після неї буде наведено відповіді на питання. Після відповідей можуть бути наведені посилання на корисні ресурси які дозволять ознайомитись з питанням на іншому ресурсі, як правило, в більш розгорнутому вигляді. Список emoji які будуть показувати різні типи ресурсів:
* 📖 - документація PHP
* 🎥 - відео
* 🔗 - посилання на сторонній ресурс, який не є офіційною документацією

## Питання
| #  | Питання |
| ------------- |:-------------|
| --- |Junoir Загальне|
| 1   | [Що таке посилання? ](#1) |
| 2   | Які основні операції з використанням посилань?     |
| 3   | Назвіть прості типи даних, підтримувані в РНР?     |
| 4   | Що таке інкремент і декремент, у чому різниця між префіксним і постфіксним інкрементом і декрементом?     |
| 5   | Що таке рекурсія?     |
| 6   | У чому різниця між =, == і ===?     |
| 7   | Які знаєте принципи ООП?    |
| 8   | Яка система типів використовується в PHP? Опишіть плюси та мінуси.     |
| 9   | Чим відрізняються ключові слова: include і require, mysql_connect і mysql_pconnect?     |
| 10  | Що таке інтерфейси? Чи використовуєте їх? Якщо так — розкажіть про це.     |
| 11  | Що таке абстрактний клас і чим він відрізняється від інтерфейсу?     |
| 12  | Чи може абстрактний клас містити приватний метод?     |
| 13  | Які модифікатори видимості є в РНР?     |
| 14  | Які магічні методи ви знаєте і як їх застосовують?     |
| 15  | Що таке генератори і як їх використовувати?     |
| 16  | Що робить оператор yield?     |
| 17  | Що таке traits? Альтернативне рішення? Наведіть приклад.     |
| 18  | Опишіть поведінку під час використання traits з однаковими іменами полів і/або методів?     |
| 19  | Чи будуть доступні приватні методи trait в класі?     |
| 20  | Чи можна компонувати traits в trait?     |
| 21  | Розкажіть про обробку помилок і винятки (try catch, finaly і throw).     |
| 22  | Що таке type hinting, як працює, навіщо потрібен?     |
| 23  | Що таке namespace’и та навіщо вони?     |
| 24  | Порівняння значень змінних у РНР і підводні камені? Приведення типів. Що змінилося в PHP 8 у цьому контексті?     |
| 25  | Як працює session у РНР, де зберігається, як ініціалізується?     |
| 26  | Суперглобальні масиви. Які знаєте? Як використовували?     |
| 27  | Порівняйте include vs required, include_once vs required_once.     |
| 28  | Що означає складність алгоритму?     |
| 29  | Що таке замикання в PHP? Наведіть приклад.     |
| 30  | Яка різниця між замиканням у PHP і JavaScript?     |
| 31  | Що таке пізнє зв’язування? Розкажіть про поведінку та застосування static.     |
| 32  | Як перевизначити зберігання сесій?     |
| 33  | Розкажіть про SPL-бібліотеку (Reflection, autoload, структури даних).     |
| 34  | Розкажіть про принципи SOLID.     |
| 35  | Розкажіть про шаблони GRASP.     |
| 36  | Розкажіть про Dependency Injection: що таке DI-контейнери? Які є варіанти реалізацій?     |
| 37  | Що вам відомо про MVC?     |
| 38  | Що вам відомо про шаблони GoF?     |
| 39  | Що вам відомо про шаблони, які застосовуються в ORM?     |
| 40  | Напишіть/розкажіть на PHP приклад реалізації патерну Singleton.     |
| 41  | Що таке Docker? Яким є принцип його роботи?     |
| 42  | Що таке LAMP/NAMP?     |
| 43  | Розкажіть про regexp.     |
| 44  | Розкажіть про SSH-протокол.     |
| 45  | Що таке PDO?     |
| 46  | Що нового з’явилося в PHP 8?     |
| 47  | Що таке PHP PEAR?     |
| 48  | Які версії PHP досі підтримуються?     |
| 49  | У чому різниця між GET і POST?     |
| 50  | Чим відрізняються оператори BREAK і CONTINUE?     |
| 51  | Чи є різниця між одинарними та подвійними лапками?     |
| 52  | Що таке Cookie і навіщо вони використовуються?     |
| 53  | Що не можна зберігати в Cookie і чому?     |
| 54  | Якому середовищу розробки віддаєте перевагу й чому?     |
| --- | Junior Git |
| 55  | Якою командою додати зміни? |
| 56  | Якою командою зафіксувати зміни? |
| 57  | Якою командою відправити зміни у віддалений репозиторій? |
| --- | Junior Бази даних |
| 58  | Що таке транзакція? |
| 59  | Що таке нормалізація? |
| 60  | Що таке денормалізація? Для чого вона потрібна? |
| 61  | Які є типи зв’язків у базі даних? |
| 62  | Що означає твердження про те, що СУБД підтримує контроль посилальної цілісності зв’язків? |
| 63  | Якщо використовувана вами СУБД не підтримує каскадні видалення для підтримки посилальної цілісності зв’язків, що можна зробити для досягнення аналогічного результату? |
| 64  | Що таке первинний і зовнішній ключі? |
| 65  | Які відмінності між первинним і унікальним ключами? |
| 66  | Які є типи JOIN і в чому відмінності? |
| 67  | Що таке курсори в базах даних? |
| 68  | Що таке агрегатні функції SQL? Наведіть кілька прикладів. |
| 69  | Що таке міграції? |
| 70  | Розкажіть про зв’язки один до одного, один до багатьох, багато до багатьох. |
| 71  | Назвіть і поясніть три будь-які агрегувальні методи. |
| 72  | Навіщо використовують оператор угруповання GROUP BY? |
| 73  | У чому різниця між WHERE і HAVING? Наведіть приклади. |
| 74  | У чому різниця між операторами DISTINCT і GROUP BY? |
| 75  | Для чого потрібні оператори UNION, INTERSECT, EXCEPT? |
| 76  | Опишіть різницю типів даних DATETIME і TIMESTAMP. |
| 77  | Які ви знаєте рушії таблиць і чим вони відрізняються? |
| 78  | Які способи оптимізації продуктивності баз даних знаєте? |
| 79  | Що таке партиціонування, реплікація і шардинг? |
| 80  | Чим відрізняються SQL від NoSQL бази даних? |
| 81  | Які бувають NoSQL бази даних? |
| 82  | Які типи даних є в MySQL? |
| 83  | Різниця між LEFT JOIN, RIGHT JOIN, INNER JOIN? |
| 84  | Різниця між JOIN і UNION? |
| 85  | Що таке індекси? Як вони впливають на час виконання SELECT, INSERT? |
| 86  | Що таке збережені процедури, функції та тригери в MySQL? Для чого вони? Наведіть приклади використання. |
| 87  | Як організувати збереження вкладених категорій у MySQL? |
|     | Junior Laravel |
| 88  | Які є зв’язки і як вони реалізуються в Laravel? |
| 89  | Що таке поліморфні зв’язки, як вони працюють? |
| 90  | Що таке middleware? Навіщо це? На якому етапі виконується? |
| --- | Junior Composer |
| 91  | Що таке Composer? |
| 92  | Чим відрізняється require від require-dev? |
| --- | Junior Практичні завдання |
| 93  | Спроєктуйте базу даних для зберігання інформації про книги та їхніх авторів. Напишіть запит для вибірки всіх авторів і кількості написаних ними книг. |
| 94  | Є матриця 3×3. Порахуйте діагоналі, тільки парні/непарні числа в діагоналях. |
| 95  | Ваш застосунок видає 500 помилку. Опишіть послідовність пошуку проблеми. |
| 96  | Напишіть функцію, яка визначає, чи слово є паліндромом. |
| 97  | Який результат видасть такий код: If (-1) print "True" else print "False" |
| 98  | Який результат видасть такий код: $a = 3; $b = 2; echo (int) $a / (int) $b; |
| 99  | Який результат видасть такий код: var_dump (array_merge (\[2 => 'a'\], \[3 => 'b'\])); |
| 100 | Є масив товарів у випадковому порядку із вказанням виробників. Напишіть метод для його сортування, щоб максимальна кількість перших товарів відповідала такому критерію: кожний наступний товар мав виробника, відмінного від попереднього. |
| 101 | Чому буде дорівнювати $ x після виконання виразу $ x = 1 + «1%» + «$ 1»? |
| 102 | Є масив Integer, напишіть можливі способи, як збільшити кожен елемент на одиницю (+1). |
| 103 | Схематично реалізувати структуру (класи) для завдання: Створити API для розміщення постів у Facebook та Google. URL для розміщення постів Google www.google.com/new-post?text=. URL для розміщення постів Google facebook.com/add-post?message= |
| 104 | Є таблиці 2×3 і 3×2. Select * from a, b. Яка розмірність результату? (Більш детальний опис у відповіді) |
| 105 | Напишіть запит для збільшення значення column1 на +1 для id = 2 |
| 106 | Напишіть цикл for так, щоб аргумент циклу змінювався в геометричній прогресії. |
| 107 | Чому дорівнюють вирази: print (!! "false"); print (!! true); print ((int) '125g7'); print ((int) 'x52'); |
| 108 | Який результат виконання функції? Як виправити результат? in_array (1, \[0, '0', true\]) |
| 109 | Напишіть клас з реалізацією всіх можливих способів суворої типізації даних з урахуванням можливостей PHP 7.4. |
| 110 | Напишіть метод для зв’язку «багато до багатьох». У методі додайте умову для значення, яке збережено в поле проміжної таблиці. Наприклад, є студенти та курси, на які вони записалися. Запис студента на курс повинен бути підтверджений. Підтвердження зберігається в проміжній таблиці як is_approve. Для моделі студентів має бути метод approvedCourses. |
| 111 | Напишіть запит з використанням моделі Query Builder, який буде відповідати запиту: Select * from 'users' where ( 'age'> 21 and ( 'has_education' == 1 or 'work_experience'> 2)) |
| 112 | Напишіть artisan-команду для створення моделі та міграції для неї. |
| 113 | Напишіть artisan-команду для очищення кешу фреймворку. |
| --- | Middle Загальне |
| 114 | Як передаються змінні (за значенням або за посиланням)? |
| 115 | Які процеси відбуваються, коли користувач вводить у браузері URL? |
| 116 | Що таке варіативна функція або splat-оператор? |
| 117 | Що таке OWASP? |
| 118 | Які типи вразливостей знаєте? Як від них захищатися? |
| 119 | Що таке ідемпотентні методи? Які HTTP-методи є ідемпотентними для REST? |
| 120 | Що таке stateless? |
| 121 | SOAP vs REST. У чому різниця? |
| 122 | Які методи авторизації використовують для побудови API? |
| 123 | Що може містити інтерфейс? |
| 124 | Клас містить властивість, яка, своєю чергою, є об’єктом. Що буде містити ця властивість у клонованому об’єкті: посилання на той самий дочірній об’єкт чи копію дочірнього об’єкта? Що потрібно зробити, щоб це змінити? |
| 125 | Що таке Mock? Де використовують і навіщо? |
| 126 | Що таке PSR? |
| 127 | Опишіть реалізацію одного з шаблонів проєктування. |
| 128 | Що таке Redis? |
| 129 | Як зберігаються дані в Redis/Memcached? |
| 130 | Розкажіть про доцільність застосування Redis/Memcached для кешування. Які плюси та мінуси? |
| 131 | Назвіть відмінності між nginx і Apache. |
| 132 | Що таке Opcash? Як він працює? |
| 133 | Що таке JIT? Як він працює? |
| 134 | Навіщо потрібне ключове слово final? |
| 135 | Що нового в РНР 7/8? |
| 136 | Що таке SOLID, DRY, KISS, YAGNI? |
| 137 | Назвіть патерни проєктування, з якими доводилося працювати. |
| 138 | Що таке проста фабрика? |
| 139 | Що таке Service Layer і де його варто застосовувати? |
| 140 | Як влаштований Singleton і чому його вважають антипатерном? |
| 141 | Що таке ідемпотентність? |
| 142 | Опишіть життєвий цикл HTTP-запиту? |
| 143 | Що таке купа і стек? |
| 144 | Що таке рефлексія? |
| 145 | Що таке хеш-функція і де вона використовується? |
| 146 | Як застосовуються черги в РНР? |
| 147 | Як у загальних рисах працює OPcache? |
| 148 | Що таке GRASP? |
| 149 | Що таке TDD? |
| 150 | Чим відрізняються модульні тести від інтеграційних? |
| 151 | Що таке трейти? Як застосовувати на практиці? |
| 152 | Як вирішити конфлікти під час використання trait? |
| 153 | Як працює автозавантаження класів? |
| 154 | У чому різниця між стеком і чергою? |
| 155 | Розкажіть про Unit Tests (required), Functional Tests (optional). Моки і стаб у PHP. |
| 156 | Уявімо ситуацію, в якій нам потрібно викликати приватний метод, як це зробити? |
| 157 | Опишіть різницю між PHP-FPM і PHP на сокеті. |
| 158 | Як би ви реалізували завантаження великих звітів з великою кількістю даних (файли від 1 гігабайта до N гігабайтів). |
| 159 | Як би ви імпортували 50-гігабайтний файл xml в базу даних? |
| 160 | Чому після PHP 5 йде відразу 7, куди поділася 6? |
| 161 | Чи є різниця між self і this у PHP? |
| 162 | Що таке PuTTY? |
| 163 | У нас є важливий PHP-файл, його треба запускати кожні 20 секунд, як би ви це зробили? |
| 164 | Як розшифрувати 644 в правах на файл у Linux? |
| 165 | Що таке Opcode? |
| --- | Middle Git |
| 166 | У чому різниця між merge і rebase? |
| 167 | Якою командою можна зробити ресет змін, не втративши їх? |
| 168 | Що таке stash і навіщо він потрібен? |
| --- | Middle Бази даних |
| 169 | Яка різниця між MyISAM i InnoDB? У яких випадках і що краще застосовувати? |
| 170 | Як знайти та оптимізувати «важкі» запити? |
| 171 | Які є типи індексів? |
| 172 | Як зберігати координати точки на карті в БД? |
| 173 | Які типи індексів бувають у RDBMS? |
| 174 | Яку властивість полів БД потрібно враховувати під час вибору типу індексу? |
| 175 | Коли варто використовувати індекси, які є переваги та недоліки? |
| 176 | Що таке ACID? |
| 177 | Що таке план виконання запиту і як його дізнатися? |
| 178 | У чому різниця між типами даних CHAR і VARCHAR у SQL? |
| 179 | Яке призначення транзакцій? Розкажіть про принцип роботи. |
| 180 | Назвіть 3–4 нормальні форми реляційних БД. |
| 181 | Яке призначення реплікації? Які є типи зв’язків і в чому різниця між ними? |
| 182 | Що таке індексація? Які є типи індексів? Який сенс їх використовувати? |
| 183 | Що таке повнотекстовий пошук у MySQL? Як він реалізується? |
| 184 | Що таке cursor у MySQL-процедурах? |
| 185 | Розкажіть про RabbitMQ або Gearman. |
| 186 | Що знаєте про Solr/ElasticSearch ? |
| 187 | Що знаєте про Solr/ElasticSearch ? |
| 188 | Чи впливає порядок JOIN на план виконання MySQL-запиту? |
| --- | Middle Laravel |
| 189 | Як і які формуються запити під час використання методу with ()? |
| 190 | Чим відрізняються методи with () і load ()? |
| --- | Middle Практичні завдання |
| 191 | Вам потрібно спарсити продукти та їхні ціни з інтернет-магазину. За допомогою чого будете це робити і які основні нюанси потрібно врахувати? |
| 192 | Для сайту користувачів необхідно зробити механізм додавання і відображення аватарок. Як би ви його реалізували? |
| 193 | Який результат видасть такий код: (Більш детальний опис у відповіді) |
| 194 | Які модифікатори доступу допустимі в реалізації методу getName: (Більш детальний опис у відповіді) |
| 195 | Реалізуйте чергу повідомлень, використовуючи MySQL для зберігання даних. Як уникнути ситуації, коли декілька воркерів отримають в обробку однакове повідомлення? |
| 196 | Є матриця з числами 3×3. Як знайти числа, що не мають парних/непарних сусідів? |
| 197 | Є мануал на API від Європейського центрального банку з курсом валют. Потрібно знайти мінімуми-максимуми за 5 років, а потім те саме, але з розбивкою за місяцями. |
| 198 | Збережіть свою бібліотеку в БД. Потрібно зберегти назви книг і імена авторів. Запропонуйте структуру таблиць. Виведіть звіт «книга — кількість співавторів». |
| 199 | Реалізуйте примітивний роутинг, який забезпечує роботу Рауса за шаблоном "/ {class_name} / {method_name} /" |
| 200 | Напишіть архітектуру, яка ґрунтується на базовій абстракції. Дочірні класи розширюються за допомогою інтерфейсів. Реалізацію однакових методів виконайте, використовуючи трейти (реалізовувати в абстракції). |
| 201 | Напишіть запит, у результаті виконання якого виведеться значення «id» і «val», якщо значення стовпця column> 5 => val = val1 інакше val2. |
| 202 | Laravel: напишіть розклад, який буде виконуватися щоп’ятниці кожної години у 15 хвилин. |
| 203 | Напишіть кастомну artisan-команду, яка в консоль буде виводити поточний час. |


## Відповіді

1. #### <a name="1"></a>Що таке посилання?

Посилання в PHP є засобом доступу то тієї ж змінної за допомогою різних імен. В PHP імена змінних посилаються на об'єкт, а не не адреси в пам'яті, в свою чергу за допомогою посилань ми можемо створити декілька посилань на той самий об'єкт.

```
$a = 10;
$b =& $a;

echo $b; // 10

echo $a === $b; // true
```

📖 - [What References Are](https://www.php.net/manual/en/language.references.whatare.php)

