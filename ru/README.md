# Введение
 ## Что такое Tiedot?

<img src="http://golang.org/doc/gopher/frontpage.png" alt="Golang logo" align="right"/>

### tiedot - NoSQL база данных на Golang

tiedot  документоориентированная база данных которая использует нотацию JSON; В наличии мощный конструктор запросов, он может встраиваться в вашу программу или использоваться как сервер через HTTP. Он работает в ОС *nix и Windows.

tiedot имеет отказоустойчивые структуры данных и легко масштабируется от 4 ядер.

!> tiedot это стабильная производительность, даже с миллионами записей! Его пропусканая способность 120 тысяч записей или 80 тысяч сложных запросов в секунду. 
![](http://dl4.joxi.net/drive/2017/11/13/0015/0439/1012151/51/d7a1b7c2d5.png)

### Контрибьютеры добро пожаловать!
tiedot это маленький проект с большим комьюнити - благодаря уже более 800 звездам на github и наблюдателям которые следят за ним. Ваш вклад всегда для нас имеет большой значение.

Мы открыты для новых Pull requests и forks. Поделитись своими мыслями, задавайте вопросы, создавайте [Issues](https://github.com/HouzuoGuo/tiedot/issues)!

Вы всегда можете поблагодарить или поделиться чем нибудь, через мою [почту](mailto:guohouzuo@gmail.com), [твиттер](https://twitter.com/hzguo) или мой [блог](https://allstarnix.blogspot.ru/).
### Вперед tiedot!

tiedot распространяется под лизензией [Simplified BSD license](/contributors_and_license.md/) [Contributors and License](/contributors_and_license.md/).

### История проекта
Go это очень увлекательный язык и за последнее время он привлек большое внимание общественности с открытым исходным кодом. Однако оставаясь еще пока молодым языком программирования
Go is a fascinating language and it has attracted a lot of attention in the open source community over the past few years. But as a young programming language, there was a lack of database engine options for back-end development. As we all know, the design of Go was heavily inspired by C language, and there is sqlite for C - so I thought what about a making DB engine easily embeddable for Go programs?

Then tiedot was born - the name "tiedot" is a cute Finnish word meaning "data". Initially being a programming exercise, tiedot greatly helped me exploring the performance characteristics of Go.

Thanks to the very welcoming and helpful community of Go - when tiedot made its first release, a lot of people contributed feature ideas and suggestions pushing the project well beyond its initial goal. Till this day tiedot has been used in data analysis, embedded systems, utility applications, web applications, and some people also find it useful being a demo of several DB engine mechanisms.

I love Go because it offers stable and predictable performance characteristics, very fast compilation speed and a complete toolchain for all development activities. And unlike many other languages, Go does not require an intelligent IDE to improve productivity of users - many of which find a syntax-highlighted text editor to be sufficient for coding Go!

There are several other data structure servers/DB engines written in Go, namely "etcd", "leveldb-go" and "ql"; they emphasis on different usage scenarios, for example "etcd" is a data structure server designed for configuration management and service discovery, "leveldb-go" is a re-implementation of popular LevelDB in Go, and "ql" is an embeddable DB engine providing SQL capability. After all, when it comes to choosing a general purpose, embeddable NoSQL database engine, tiedot is perhaps the only choice so far (as far as I know).
