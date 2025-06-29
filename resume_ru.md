# Афанасьев Иван

### Опыт

#### [Unipro](https://unipro.ru)

> **Ведущий разработчик С++**  
> *06.2021 - ...*  
> C++, LLVM, python

Разработка out-of-tree backend для компилятора LLVM.

* Реализация и улучшение прохода unroll-and-jam на уровне MIR.
* Разработка платформо-специфичных проходов над IR.
* Разработка автогенераторов для интеграционных тестов (python).
* Разработка fuzzer-ов для платформо-специфичных проходов над IR / MIR.


#### [Align Technology](https://aligntech.com)

> **Ведущий разработчик С++**  
> *10.2018 - 06.2021*  
> C++, python, analytic geometry

Разработка медицинской CAD-системы.

Доведение до релиза и поддержка алгоритма предсказания положения отсутствующих
зубов. Реализованы фичи алгоритма: исправление корней, торчащих из десны,
гладкое масштабирования корня. Предложен и разработан алгоритм вычисления
челюстной арки на базе предсказания позиций коронок отсутствующих зубов.
Множественные улучшения производительности.

Доведение до результата длительного исследовательского проекта о применимости
ML-моделей предсказания положения границы десны на модели зубов. Предложен и
разработан алгоритм постобработки вероятностных предсказаний ML-модели.
Алгоритм основан на KNITRO-реализации метода градиентного спуска.

Роль performance guard: отслеживание регрессий производительности, анализ
причин, предлложения по исправлению, планирование улучшений и т.п.

Стандартная роль "на подхвате": помощь трём смежным командам вовремя завершить
проекты, выходящие за запланированные рамки. Требовалось быстро адаптироваться
под новые команды, разбираться с требованиями и вовремя доставить решение.

Помощь новичкам в команде, вывод стажёров в разработчики.

#### [Yandex](https://yandex.ru/)

> **C++ разработчик**  
> *10.2016 - 10.2018*  
> C++, python

Разработка chromium-based Я.Браузера. Команда SafeBrowsing: предотвращение
доступа пользователей к фишинговым сайтам, детектор биткоин-майнеров, поддержка
блокировщика рекламы, исследование проблем memory corruption, обработка отчётов
санитайзеров.

#### [Novosibirsk State University](https://www.nsu.ru)

> **Ведущий разработчик С++**  
> *05.2016 - 10.2016*  
> C++, python

NDA.

#### [2gis](https://2gis.ru/)

> **Руководитель команды С++ разработчиков**  
> *2015 - 2016*  
> C++, python

Руководитель группы интеграции навигационных севрисов в мобильные продукты
2ГИС. Задача команды - предоставить единый высокоуровневый С++ - интерфейс для
различных команд мобильной разработки (android / iOS / WinPhone), прозрачно для
них провязв функционал алгоритмов навигации с 3D-картой и данными справочника.
Команда ответственна за пробки, поиск маршрута на авто, общественном
транспорте и навигатор. Первый релиз навигатора.

> **Ведущий iOS разработчик**  
> *2014 - 2015*  
> Objective-C++, ReactiveCocoa

Выпуск первого релиза 2ГИС v4 для iOS.

> **Ведущий С++ разработчик / Руководитель команды**  
> *2013 - 2014*  
> C++, Qt 4.8, Objective-C++, Java, JNE

Завершение третьей серии мобильных версий 2ГИС (iOS, Android, WinCE, Symbian).
Релиз отдельной серии для Олимпийских игр в Сочи.

> **Разработчик С++**  
> *2011 - 2013*  
> C++, Qt 4.8, Objective-C++, Java, JNE

Разработка третьей серии мобильных версий 2ГИС (iOS, Android, WinCE, Symbian).
Поддержка функцониала "Этажи" (внутренний вид ТЦ), "Входы", реклама в
справочнке, статистика, интеграции новых версий поиска, справочника и карты,
алгоритмы обхода баблов на карте.

#### [Intel](https://www.intel.com)

> **Стажёр-практикант по разработке ПО**  
> *2010 - 2011*  
> C, Fortran, OpenMP

Разработка функций BLAS L1, L2 для Intel Xeon Phi с использованием интринсиков
компилятора.

> **Стажёр-практикант по разработке ПО**  
> *2008 - 2010*

* Performance-тестирование Intel MKL на серверных и кластерных архитектурах.
* Интеграция новых тестов в тестовую инфраструктуру.
* Разработка алгоритмов валидации для функций BLAS.

#### [Boner](http://boner.ru)

> **Программист С**  
> *2006 - 2008*  

Разработка микроконроллеров.

### Образование

#### [Институт вычислительной математики и математической геофизики СО РАН](https://icmmg.nsc.ru)

> **Кандидат наук. Вычислительная математика и математическое моделирование. 05.13.18**  
> *2011 - 2014*

Клеточно-автоматное моделирование динамики популяций.

#### [Новосибирский государственный университет](https://www.nsu.ru)

> **Магистр. Механико-математический факультет.**  
> *2005 - 2011*  

Красный диплом.

### Дополнительная информация.

* Коммиты в clang libcxx:  
  [speedup std::to_string for integers](https://reviews.llvm.org/D59178)  
  [fix leading zeros in std::to_chars](https://reviews.llvm.org/D63047)  
  [Fix UB in filesystem  copy for non-existent destination](https://github.com/llvm/llvm-project/pull/87615)

* Bug report-ы в clang libcxx:  
  [race condition in steady_clock::now](https://bugs.llvm.org/show_bug.cgi?id=41323#c4)

* Коммиты в llvm:  
  [AsmPrinter fix nullptr dereference for MBBs with hasAddressTaken property without BB](https://reviews.llvm.org/D108092)  
  [Fix assertion in SmallDenseMap constructor with reserve from non-power-of-2 buckets count](https://reviews.llvm.org/D129825)  
  [Fix dst subreg replacement during remat copy trick](https://reviews.llvm.org/D125657)  
  [Fix debug location info strip for bundled instructions](https://github.com/llvm/llvm-project/pull/113676)  
  [Fix NumPromoted statistic for SROA pass](https://github.com/llvm/llvm-project/pull/115586)  
  [[EarlyIfConverter] Fix reg killed twice after early-if-predicator and ifcvt](https://github.com/llvm/llvm-project/pull/133554)  
  [[CodeGen][CodeLayout] Fix segfault on access to deleted block in MBP.](https://github.com/llvm/llvm-project/pull/142357)  

* Bug report-ы в llvm:  
  [Clang generates incorrect code for unions of types with padding](https://github.com/llvm/llvm-project/issues/76017)

* Коммиты в иные open source проекты:  
  [GoogleBenchmark: Fix unit tests compilation by non-gnu/msvc compilers with c++11 support](https://github.com/google/benchmark/pull/1691)  
  [GoogleBenchmark: Fix division by zero for low frequency timers for CV statistics](https://github.com/google/benchmark/pull/1724)  
  [fmtlib: Fix UB in format_arg_store implementation](https://github.com/fmtlib/fmt/pull/3833)  
  [opencv: speedup random forest getVotes method](https://github.com/opencv/opencv/pull/26046)  

* Выступления на конференциях:  
  [CppSiberia 2017: C++ performance testing tool (RU)](https://www.youtube.com/watch?v=K_YkyXeZ8tU)  
  [CppRussia  2020: std::to_string faster than light (RU)](https://www.youtube.com/watch?v=xCv84sSz204)  
  [CppSiberia 2021: Compilation time. Profile / Visualize / Speedup (RU)](https://youtu.be/VdXk0nJsXgI)  
  [CppRussia  2023: Loop Unrolling в деталях (RU)](https://www.youtube.com/watch?v=Tst3MbTrYzk)

* Курсы C++ в [CSC](https://compscicenter.ru/)/SHAD :  
  Продвинутый C++
  [2020](https://my.compscicenter.ru/courses/2021-spring/2.914-cpp-2/),
  [2021](https://my.compscicenter.ru/courses/2020-spring/2.500-cpp-2/)  
  Базовый C++
  [2017](https://my.compscicenter.ru/courses/2017-autumn/2.320-cpp-1/),
  [2018](https://my.compscicenter.ru/courses/2018-autumn/2.388-cpp-1/),
  [2019](https://my.compscicenter.ru/courses/2019-autumn/2.453-cpp-1/),
  [2020](https://my.compscicenter.ru/courses/2020-spring/2.500-cpp-2/)  
  [Materials](https://github.com/ivafanas/cpp_shad_students)

### Контактная информация
* email: ivafanas (at) gmail.com
* tel.: 8-923-180-7637

