Блог Милой Няки
===============
* `Стандартное GWT-приложение. Добавление кнопки`: [http://milayanyaka.blogspot.com/p/blog-page_18.html](http://milayanyaka.blogspot.com/p/blog-page_18.html)



1. Создаем / Генерим проект с нуля средствами мавена ( [https://antonkirillov.wordpress.com/2011/03/22/creating-and-running-gwt-project-using-maven-and-intellij-idea-10/](https://antonkirillov.wordpress.com/2011/03/22/creating-and-running-gwt-project-using-maven-and-intellij-idea-10/) ):
   mvn -DarchetypeGroupId=org.codehaus.mojo -DarchetypeArtifactId=gwt-maven-plugin -DarchetypeVersion=2.2.0 -DgroupId=com.milayanyaka.standart -DartifactId=Standart3 -Dversion=1.0 org.apache.maven.plugins:maven-archetype-plugin:generate
2. Результатом выполненения мавена получим:
[INFO] Using property: groupId = com.milayanyaka.standart
[INFO] Using property: artifactId = sample
[INFO] Using property: version = 1.0
[INFO] Using property: package = com.milayanyaka.standart
Define value for property 'module': :
3. Вводим имя проекта: 'SampleApplication'
   Дальше мавен сгенерит дефолтный проект...
4. Настраиваем в IDE 'GWT configuration':
   Поле 'module' >> 'Standart'
   Поле 'VM parameters' >> '-Xmx256m'
   остальные поля можно оставить по дефолту...
5. Запускаем проект средствами 'GWT Development Mode' [http://kiahu.com/tutorial/working-with-gwt-maven-and-intellij-idea/](http://kiahu.com/tutorial/working-with-gwt-maven-and-intellij-idea/)
   'gwt:i18n'
   'gwt:run'
6. Запуститься консоль 'Run Maven Build'
   Кнопка 'Copy to Clipboard' >> генерит/выводит URL-адресс под которым проект можно запустить в веб-браузере [http://127.0.0.1:8888/Standart.html](http://127.0.0.1:8888/Standart.html)
   И вводим URL-адресс проекта в веб-браузере...