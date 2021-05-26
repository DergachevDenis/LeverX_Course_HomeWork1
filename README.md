# LeverX_Course_HomeWork1
Starting a java project from the console

<h3>Скачиваем проект с GitHub</h3>
<ul>
<li> Переходим по <a  href = "https://github.com/DergachevDenis/LeverX_Course_HomeWork1">ссылке</a>.</li>

<li> Нажимаем на зеленую кнопку <i>Code</i>, затем на всплывшем окне нажимаем <i>Download ZIP</i>.</li>

<li> Ждём пока скачается наш ZIP файл, затем разархивируем в нужную нам директорию.</li>
</ul>


<h3>Компилируем и запускаем наш java проект</h3>
<ul>
<li> В командной строке переходим на диск, где сохранён наш репазиторий, с помощью команды [имя_тома]: (Например <code>H:</code>). </li>

<li> В командной строке указываем полный путь, до папки <code>src</code> с помощью команды <code>cd</code> 

(Например: <code>cd H:/Java/LeverX_courseJava/HomeWork1</code>). Учтите, командная строка чувствительна к регистру.</li>

<li> Находясь в директории где хранится папка <code>src</code>, скачанная с GitHub, выполните команду:

<code>javac -d classes src/com/dergachev/homework1/Main.java</code>. 

Результатом выполнения этой команды, будет создание новой директории <code>classes</code> в каталоге <code>H:/Java/LeverX_courseJava/HomeWork1</code> в котором автоматически создатся структура каталогов как и в <code>src</code> c откомпилированым файлом <code>Main.class</code></li>

<li> Что бы запустить данную java программу, мы должны находиться в каталоге в котором находится наша директория <code>classes</code>, затем в командной строке выполняем команду <code>java -cp ./classes com.dergachev.homework1.Main</code>

Результатом выполнения данной команды будет вывод строки в консоль: <code>Hello, my friend</code>.</li>

<li> Что бы создать JAR файл переходим в директорию <code>classes</code>  c помощью команды <code>cd classes</code>, а затем используем команду 

<code>jar cfe homework.jar com.dergachev.homework1.Main com/dergachev/homework1/Main.class</code>.</li>

<li> Что бы запустить JAR файл, находясь в директории с созданным <code>homework.jar</code> файлом выполняем команду 

<code>java -jar homework.jar</code>. Результатом выполнения данный команды будет вывод строки в консоль: <code>Hello, my friend</code>.</li>
</ul>
