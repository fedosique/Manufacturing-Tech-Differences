# Manufacturing-Tech-Differences
<h1>Принципиальные различия в Manufacturing / Tech проектах </h1>

Излагаю свое видение о сходствах и различиях работы и управления в сферах производства и software-разработки.
Многие мысли и гипотезы оставлены читателю на размышление, я не настаиваю ни на каком из подходов и ни на какой из методик.
Такова доля моей major-специальности, что на некоторое время в начале своей карьеры мне удалось погрузиться в так называемую manufacturing-отрасль: я успел поработал инженером-конструктором, зачастую сочетая в себе компетенции оператора ЧПУ и аутсорсингового менеджера.

## Об операционных особенностях
Благо, мои университет и кафедра, а также усилия с моей стороны в первые семестры обучения дали мне неплохую фундаментальную базу технического "дизайна" проектируемых систем. Я, вообще, - радиоэлектронщик, но хорошая база в прикладной механике и сами прикладные навыки, данные мне университетом, наложились на опыт, полученный будучи инженером-конструктором в FMCG.

Правильно, конечно, назвать меня дизайнером-конструктором, так как я чаще занимался конструированием световых предметов интерьера по кастомным проектам архитекторов и дизайнеров, иногда погружаясь в электрическую часть изделий, делая тепловые и мощностные расчеты. Из-за длительного NDA, свои чудесные (и не очень) изделия показать я, к сожалению, не могу. Поверьте на слово - были и успешные результаты, красующиеся в фешенебельных местах столицы и за границей!

Сложность и, во многом, интерес к этим задачам были вызваны большой пропастью между видением дизайнера и между реальной возможностью реализации того или иного изделия. В погоне за визуалом зачастую страдает надежность, искусство заключается в нахождении баланса. Бывали и смешные ситуации, когда стеклянная часть изделия, которое я конструировал, должна была после выдувки весить более 15 килограмм, а я выбирал крепления и тросы. "Расчет на прочность, материаловедение, симуляция" - скажете вы. Это да. "Подвесим двух слесарей на трос и посмотрим, что произойдет" - скажем мы. Это шутка, хотя мы действительно это проверили, и всё сошлось. 

<img src="https://leonardo.osnova.io/66ed620d-a2f1-568c-9a20-aad817955fff/" alt="Форма для стекла">

Тут эмпирика, вероятно, не к месту, однако многолетний опыт сотрудников, которые руками собирают подобные изделия, зачастую дает гораздо более точную и надежную оценку, нежели использование правильных методик - это уже переходя к менеджменту. Важно то, что здесь, в процессе производства, и главное - прототипирования (хорошо, если оно вообще есть), у инженера и команды проекта есть право на ошибку. Это не совсем тот инженерный бизнес, который строится на основе советских ГОСТов и принципов заводов в отрасли машиностроения или тяжелой промышленности. Да, есть постулаты, которые нужно соблюдать (и кажется, что они в первую очередь фиксируются в учебниках и справочниках, а не в нормативных актах), но мой не окрепший до конца взгляд говорит о том, что методология тут важнее - и склоняюсь я к тому, что тут имеет место попробовать "гибкость".

<img src="https://sun9-49.userapi.com/impg/-9PfqeMSmg6eNFGqWR_1qRfSfIY8YL22JIWVQg/3qjPKAIPh-8.jpg?size=1017x334&quality=96&sign=10e3c71dbc91b2b61f3462445ab22f06&type=album" alt="Я - оператор ЧПУ">

## Об управленческих особенностях
СМК в производстве - это, в целом, крайне сложно и требует качественного образования и опыта со стороны ответственных за это людей. За время работы в производстве я видел разных людей на подобных позициях - максимально расслабленных и следующих только собственному мнению, и максимально педантичных, работая по методичке "Менеджмент" столетней давности. Думаю, всем понятно, что ни тот, ни другой подход адекватно не работал. Каждое производство так или иначе подвергается менеджменту (когда я был студентом 3 курса и меня изнутри разрывало от неудачного менеджмента моего производства - а в ВУЗе мне рассказывали, в чем разница между винтами и болтами, я параллельно слушал книгу "Dao Toyota" о том, как появился Lean-подход и верил, что когда-то смогу оказаться в подобной бизнес-вселенной), но здесь важен аспект уменьшения издержек, как бы банально это не звучало. Я периодически стоял за ЧПУ-станком, по паре часов в день закрывая позицию оператора и тестируя гипотезы о своих прототипах, и день ото дня тратил уйму ресурсов из-за своей неопытности. Потом это делал другой человек, потом еще один, и вряд ли эти мероприятия были финансово эффективными. Простая технологическая проверка чертежей, необходимость запроса на материалы и контроль качества производства (что складывается в систему) могли бы в разы улучшить ситуацию с себестоимостью, даже если это был прототип. И это не просто я попал на плохо организованное предприятие, таких у нас пруд пруди.

"Детский сад" - скажете вы. Но печаль сей ситуации видится мне в том, что десятки подрядчиков, с которыми я поработал за время своего частичного "менеджмента" этой стороны нашего производства, вели себя абсолютно так же - факапили сроки, сами изделия, допускали глупые ошибки из-за человеческого фактора. Это натолкнуло меня на мысли о системных управленческих проблемах у малых компаний в сфере производства, в частности о повсеместно плохом технологическом контроле и даже о пропущенных звеньях в цепи создания ценности.
 
## Разница с IT?
Большая (чисто исходя из специфики), но есть и схожие черты.

Что касается проектного отдела и управления проектами в классическом смысле слова (хотя производство здесь никак не исключить), во многом, классическое waterfall-планирование здесь не имеет смысла. Каждый инженер, работающий над своим проектом, по сути был его менеджером или, как минимум, координатором. Я не помню ни одного проекта, на котором бы не вырос срок сдачи: допускайте специфику рынка - это дизайнерские изделия, бизнес-требования и выбранные технологии и материалы производства зачастую меняются каждую неделю. Это натолкнуло меня на мысли в схожести процесса с IT, в частности - с Agile.

Однажды я собеседовался в компанию-конкурент (уже после ухода!) по тому же профилю. Отлично прошел собеседование, успешно выполнил тестовое задание, и в разговоре с нанимающими менеджерами позволил себе задать вопрос: "Какова ваша средняя просрочка?", на что получил строгий ответ: "Просрочка в нашей компании не допускается - за это сотрудник лишается значительной части премии при несвоевременной сдаче этапа, или штрафуется за просрочку при окончательной сдаче проекта". Это меня изрядно посмешило, потому что отзывы в Яндексе и на специализированных сайтах говорили, что просрочка в компании очень даже допускается.

К чему это я? До сих пор, даже через год после ухода, осталась интересная гипотеза о том, что даже в таком оффлайновом, неповоротливом и не flexible бизнесе есть смысл думать нестандартно, искать и применять современные подходы, работающие по разному для каждой отдельной ситуации.

Интересно еще то, что "срок проявления ошибки" в IT, по моему опыту, составляет около нескольких дней или в рамках соседних этапов (если угодно, спринтов) проекта. Такой же срок в производстве (manufacturing) конечного продукта зачастую доходит до нескольких недель или даже месяцев, и эти риски необходимо хеджировать: например, правильными прототипами, упрощенными до core-механики или визуала, да еще и собранными буквально из бумаги, дерева и пластика - если нет возможности реализовать подобное без обращения к подрядчикам; достигается многообразием технологических решений и тщательнейшим контролем не в виде микроменеджмента (!), а в форме увеличения количества milestone (вех). Заметьте - эти вещи возможно применить и в разработке, просто переложив их в другую терминологию.

<h2>Эти мысли вызваны многообразием выводов и сомнений, полученных за время работы в двух упомянутых отраслях. Глубоко советую всем прочитавшим книгу Д. Лайкера "Путь Toyota. 14 принципов менеджмента ведущей компании мира" - она может помочь людям из обеих отраслей, да и вообще уже во многом считается мейнстримом.</h2>
