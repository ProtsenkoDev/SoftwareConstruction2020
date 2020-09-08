Курс "Конструирование программного обеспечения"
======

Подробнее о курсе: https://www.hse.ru/edu/courses/339554661

## Семинар 01. Знакомство с разработкой программного обеспечения на Java-платформе

### Версия Java
Проверить текущую версию Java можно вводом в командную строку
```
java --version
```
### Установка jdk 11

Нужно установить один из вариантов:
* [OpenJDK 11.0.2](https://jdk.java.net/archive/)
  Необходимо задать **переменную окружения** JAVA_HOME и добавить "%JAVA_HOME%\bin" в переменную PATH
  https://www.java.com/ru/download/help/path.xml
  https://docs.oracle.com/cd/E19182-01/820-7851/inst_cli_jdk_javahome_t/

* [Java SE Development Kit 11](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)

После установки проверяем версию Java.

### Первая программа: "Hello, Word"
1. Создаем файл в любом текстовом редакторе: "HelloWorld.java"
2. Добавляем в файл код:
```java
public class HelloWorld {
   public static void main(String[] args) {
      System.out.println("Hello, World");
   }
}
```
3. Из командной строки, находясь в той же директории, выполняем команду:
```javac HelloWorld.java```
На выходе получаем файл: "HelloWorld.class"
4. Из командной строки, находясь в той же директории, выполняем команду:
```java HelloWorld```
Получаев вывод строки: "Hello, World"

#### Установка IntelliJ IDEA Ultimate
Компания JetBrains предоставляет бесплатные студенчиские лицензии на свои продукты.
Одним из способов получения является предоставление уникального адреса электронной почты, например "*@hse.ru"
Форма регистрации: https://www.jetbrains.com/shop/eform/students

После регистрации и входа в свой аккаунт на странице https://account.jetbrains.com/licenses на вкладке JetBrains Product Pack for Students, вы можете сказать IntelliJ IDEA Ultimate.

#### Именование пакетов
Пакет будет иметь имя: ```ru.hse.edu.sс.y2020.seminar01```

Подробнее про имена пакетов: https://docs.oracle.com/javase/tutorial/java/package/namingpkgs.html

#### Cоглашение об оформлении кода
Можно использовать например: Google Java Style
0. Скачиваем один из файлов: [intellij-java-google-style.xml](https://raw.githubusercontent.com/google/styleguide/gh-pages/intellij-java-google-style.xml) или [intellij-java-google-style.xml](https://github.com/google/styleguide/blob/gh-pages/intellij-java-google-style.xml)
1. Переходим в раздел: File → Settings → Editor → Code Style.
2. Нажимаем на настройки (Шестеренка) и Import.
3. Выбираем IntelliJ IDEA Code Style XML.
4. Выбираем ранее загруженный файл: intellij-java-google-style.xml.

Команда форматирования кода, в соответствии с выбранным стилем: ```Ctrl+Alt+L```








