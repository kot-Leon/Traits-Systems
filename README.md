<h1>kotLeon Traits Systems</h1>
<h2>Новые трейтовые системы для RTW 1.5</h2>
<p>
    <b>Делалось и тестировалось под RTW 1.5</b><br />
    <b>За основу был взят мод от Egermejster: <a target="_blank" href="https://imtw.ru/topic/7155-egermejster-traits-systems/">Egermejster Traits Systems</a></b>
</p>
    <h3><i>Краткое описание:</i></h3><p> -----старое------</p>
    <ul>
<li><b> - Счетчик побед (Когда генерал
    получает победу ему присваивается трейт с количеством одержанных побед).</b><i>
    Изменения к Egermejster</i> - "счетчик побед" был увеличен до 81 победы.</li>
<li><b> - Военный "стаж" (Когда генерал завершает ход вне города ему засчитывается
    военный стаж).</b> <i>Изменения к Egermejster</i> - "военная служба" была увеличена до
    45 лет, бонусы остались почти теми же только растянуты на более длительный
    срок.</li>
<li><b> - Губернаторский "стаж" (Когда генерал завершает ход в городе в
    качестве губернатора ему засчитывается губернаторский стаж).</b><i> Изменения к
    Egermejster</i> - "губернаторская служба" была увеличена до 45 лет, бонусы
    остались почти теми же только растянуты на более длительный срок.</li>
<li><b> - Обучение    в академии (Когда генерал или агент завершает ход в городе с построенной
    академией ему засчитывается обучение в академии).</b><i> Изменения к Egermejster</i> -
    "обучение" было разделено на три этапа: в академии; в скриптории; в Ludus
    Magna. Бонусы остались теми же только разделенными по этапам.</li>
<li><b> - Карьера для римлян (Когда генерал достигает определенных условий в количестве побед и
    полученного стажа ему присваиваются звания).</b> <i>Изменения к Egermejster</i> -
    Количество уровней карьеры было доведено до девяти. Бонусы от званий карьеры
    были существенно изменены, полностью убраны плюсы к командованию вместо них
    были добавлены плюсы к влиянию.</li>
<li><b> - Триумф для римлян (Генерал становится претендентом на триумф когда одерживает 10 сокрушительных побед в период после 100 хода и удерживая 15 и более городов).</b> <i>Изменения к Egermejster</i> -
    "Система римских триумфов" осталась без изменений, единственно
    что было исправлено это несколько технических ошибок.</li>
<li><b> - Система наместничества (Когда вашей фракции принадлежат определенные города а генерал завершает ход в главном из
    этих городов ему в свиту может прийти наместник того региона).</b> <i>Изменения к
    Egermejster</i> - "система наместничества" осталась без изменений, единственно
    что было исправлено это несколько технических ошибок.<b> Внимание: этот модуль
    работает только если названия задействованных городов будут на английском!</b></li>
<li><b> - Рождение персонажа в знаменитом городе (Когда генерал завершает первый ход
    после совершеннолетия в определенном городе ему присваивается трейт рождения
    в городе).</b> <i>Изменения к Egermejster</i> - "Рождение в знаменитом городе" теперь
    работают, но только в конце хода. То есть новый генерал который появился
    (при совершеннолетии, свадьбе или усыновлении) должен завершить свой первый
    ход в городе иначе трейт рождения в знаменитом городе присвоен не будет...
    Также сюда были добавлены несколько городов которые участвуют в системе
    наместничества. <b>Внимание: этот модуль работает только если названия
    задействованных городов будут на английском!</b></li>
</ul>
<p>-----новое-----</p>
<ul>
<li><b>- новые триггеры для начальных данных.</b> Теперь файл \data\world\maps\campaign\imperial_campaign\descr_strat.txt не нужен для этого мода.</li>
<li><b>- появление новых ancillary "Смотрители храмов"</b> (Когда генерал завершает ход в городах с храмами других фракций ему в свиту могут прийти смотрители).</li>
<li><b>- появление других новых ancillary:</b>
	<ul>
<li>   <b>- новый ancillary "Клеопатра".</b> Она будет появляться у генерала который будет останавливаться в городе Александрия в период с 402 по 481 ходы. <b>Внимание: этот ancillary будет работать только при английском названии города!</b></li>
<li>   <b>- новый ancillary "Боудикка".</b> Она будет появляться у генерала варварской культуры который будет останавливаться в городе с Храмом Андрасте в период с 600 по 662 ходы.</li>
<li>   <b>- новый ancillary "Вещая дева".</b> Она будет появляться у генерала варварской культуры который будет вне города и у которого будут оставшиеся очки движения на конец хода находиться в зоне больше 45% и меньше 55%.</li>
<li>   <b>- новый ancillary "Мастерица общины".</b> Она будет появляться у генерала варварской культуры который будет останавливаться в городе с отстроенной фермой первого уровня и выше. А также если у генерала будет в наличии трейт "Садовод" первого уровня и выше.</li>
<li>   <b>- новый ancillary "Дочь трактирщика".</b> Она будет появляться у генерала который будет останавливаться в городе с Таверной или постройкой выше уровнем. А также если у генерала будет в наличии трейт "Прелюбодей" первого уровня и выше.</li>
<li>   <b>- новый ancillary "Дочь купца".</b> Она будет появляться у генерала который будет останавливаться в городе с Форумом или постройкой выше уровнем. А также если у генерала будут в наличии: трейт "Прелюбодей" первого уровня и выше; трейт "Торговец" первого уровня и выше.</li>
<li>   <b>- новый ancillary "Брат по оружию".</b> Он будет появляться у варварского генерала-губернатора при найме пехоты, если у генерала будет командование равно 4 и более.</li>
<li>   <b>- новый ancillary "Старейшина".</b> Он будет появляться у варварского генерала при совершеннолетии, если у отца генерала будет трейт "Невежда" меньше второго уровня или вообще его не будет.</li>
<li>   <b>- новый ancillary "Попугай".</b> Он будет появляться у адмирала если будут оставшиеся очки движения на конец хода находиться в зонах: больше 35% и меньше 45% ; больше 55% и меньше 65%.</li>
	</ul></li>
<li><b>- новые изображения для некоторых ancillary.</b> Теперь все жрецы имеют уникальные изображения, а также некоторые другие персонажи.</li>
<li><b>- Система наследуемых достижений (как хороших так и плохих).</b> К примеру если генерал достиг трейта "Легендарный командир" то его сыну будет присвоен новый трейт "Знамя полководца"... Все новые трейты: "Знамя полководца", "Меч полководца", "Щит полководца", "Печатка губернатора", "Упавшее знамя", "Сломанный меч", "Сломанный щит", "Сломанная печатка".</li>
<li><b>- Система родовой принадлежности генералов.</b> Были введены трейты обозначающие к какой ветви принадлежит генерал: главной; побочной или принятой.</li>
<li><b>- трейты обозначающие изначальную принадлежность дипломатов.</b></li>
<li><b>- Счетчик побед для адмиралов</b> (Когда адмирал получает победу ему присваивается трейт с количеством одержанных побед).</li>
<li><b>- Карьера для не римлян</b> (Когда генерал достигает определенных условий в количестве побед и полученного стажа ему присваиваются звания).</li>
<li><b>- Карьера для адмиралов</b> (Когда адмирал достигает определенных условий в количестве побед и полученного стажа ему присваиваются звания).</li>
<li><b>- Лечение в храмах.</b> Теперь в некоторых храмах генерал может избавиться от каких то из плохих своих черт. К примеру в храме правителей генерал может избавиться от трейта "расточительный", а в храме исцеления может избавиться от трейта "пьяница" и др.</li>
<li><b> - Счетчик поражений для генералов и адмиралов</b> (Когда генерал или адмирал получает поражение ему присваивается трейт с количеством полученных поражений). Счетчик до 81 поражения. <i>NEW</i></li>
<li><b>- Исправления к оригинальным трейтам от kotLeon.</b></li>
<li><b>- Исправления к оригинальным триггерам для трейтов от kotLeon.</b></li>
<li><b>- Новые триггеры для оригинальных трейтов.</b></li>
<li><b>- Несколько новых трейтов для генерала.</b></li>
<li><b>- Несколько новых трейтов "пасхалок на пиратскую тематику" для адмирала.</b></li>
</ul>
<br /><p><b>Файлы:</b></p>
<ul>
<li><b>Папка: <i>kotLeon_Traits_Systems_(2_move)_for_standard</i></b><br />Версия мода для стандартных двух ходов в год. Без файла с английскими наименованиями городов.</li>
<li><b>Папка: <i>kotLeon_Traits_Systems_(4_move)_for_script</i></b><br />Версия мода для скриптовых четырех ходов в год. Без файла с английскими наименованиями городов.</li>
<li><b>Папка: <i>kotLeon_Traits_Systems_(city)</i></b><br />Файл с английскими наименованиями городов. Необходим для работы "Система наместничества" и "Рождение персонажа в знаменитом городе". Файл подходит для ванильной (стандартной) RTW 1.5</li>
<li><b>Файл: <i>Information_RTW_(by_kotLeon).xlsx</i></b><br />Информационный файл по свите и трейтам</li>
</ul>
<h3>Установка мода - скопируйте папку data в корневую папку RTW, с заменой файлов.<br />
	Чтобы мод на трейты нормально заработал нужно начинать компанию заново.</h3>

<div><b>Совместимость с другими модами:</b>
<ol><li>
Мод на трейты изменяет 6 файлов оригинальной игры:<br />
<i>\data\text\export_ancillaries.txt</i><br />
<i>\data\text\export_VnVs.txt</i><br />
<i>\data\export_descr_ancillaries.txt</i><br />
<i>\data\export_descr_character_traits.txt</i><br />
<i>\data\export_descr_ancillary_enums.txt</i><br />
<i>\data\export_descr_VnVs_enums.txt</i><br />
<p>Все эти файлы отвечают исключительно за свиту и трейты генералов. Так что если в другом моде изменения не затрагивают свиту и трейты то никаких конфликтов между модами не должно быть. Ну а если затрагивают значит придется выбирать какой вариант свиты и трейтов вам нужен.</p></li>
<li>
<p>Для того чтобы в моде работали "Система наместничества" и "Рождение персонажа в знаменитом городе" нужно чтобы названия задействованных городов были на английском. Предоставленный мною файл городов с английскими названиями подходит для ванильной (стандартной) RTW 1.5. Но если в другом вашем моде есть другие города (например мод Mundus Magnus) то предоставленный мною файл не будет подходить для другого мода. И нужно будет вручную перенести английские названия городов из моего файла в файл мода который вы будете использовать.</p></li>
<li>
<p>Новые ancillary "Смотрители храмов" делались под ванильную (стандартную) RTW 1.5 и если в другом вашем моде затрагиваются такие строения как храмы, то возможно некорректное срабатывание триггеров для смотрителей храмов. Смысл в том что у каждой фракции есть свой набор храмов для строительства и если другой мод этот набор как то меняет, то о корректной работе говорить не приходится.</p></li>
</ul></div>

<h3><i>Подробное описание:</i></h3>

<b>Новое к оригиналу от kotLeon:</b>
- добавил появление новых ancillary "Смотрители храмов". Они будут появляться у тех генералов которые останавливаются в городах с храмами других фракций.
- добавил появление нового ancillary "Клеопатра". Она будет появляться у генерала который будет останавливаться в городе Александрия в период с 402 по 481 ходы.
- добавил появление нового ancillary "Боудикка". Она будет появляться у генерала варварской культуры который будет останавливаться в городе с Храмом Андрасте в период с 600 по 662 ходы.
- добавил появление нового ancillary "Вещая дева". Она будет появляться у генерала варварской культуры который будет вне города и у которого будут оставшиеся очки движения на конец хода находиться в зоне больше 45% и меньше 55%.
- добавил появление нового ancillary "Мастерица общины". Она будет появляться у генерала варварской культуры который будет останавливаться в городе с отстроенной фермой первого уровня и выше. А также если у генерала будет в наличии трейт "Садовод" первого уровня и выше.
- добавил появление нового ancillary "Дочь трактирщика". Она будет появляться у генерала который будет останавливаться в городе с Таверной или постройкой выше уровнем. А также если у генерала будет в наличии трейт "Прелюбодей" первого уровня и выше.
- добавил появление нового ancillary "Дочь купца". Она будет появляться у генерала который будет останавливаться в городе с Форумом или постройкой выше уровнем. А также если у генерала будут в наличии: трейт "Прелюбодей" первого уровня и выше; трейт "Торговец" первого уровня и выше.
- добавил появление нового ancillary "Брат по оружию". Он будет появляться у варварского генерала-губернатора при найме пехоты, если у генерала будет командование равно 4 и более.
- добавил появление нового ancillary "Старейшина". Он будет появляться у варварского генерала при соершеннолетии, если у отца генерала будет трейт "Невежда" меньше второго уровня или вообще его не будет.
- добавил появление нового ancillary "Попугай". Он будет появляться у адмирала если будут оставшиеся очки движения на конец хода находиться в зонах: больше 35% и меньше 45% ; больше 55% и меньше 65%.
- добавил новые изображения для некоторых ancillary. Теперь все жрецы имеют уникальные изображения, а также некоторые другие персонажи.
- причесал файл export_ancillaries.txt, чтобы информация по одному объекту была в одном блоке, а не раскидана частями по всему файлу.
- причесал файл export_VnVs.txt, чтобы информация по одному объекту была в одном блоке, а не раскидана частями по всему файлу.
- в файлы export_descr_ancillary_enums.txt и export_descr_VnVs_enums.txt внес все изменения с именами которые были проделаны и заодно причесал оба файла, чтобы информация по одному объекту была в одном блоке, а не раскидана частями по всему файлу.
- исправил опечатки перевода где заметил огрехи.
- Добавил новые трейты: "Знамя полководца", "Меч полководца", "Щит полководца", "Печатка губернатора", "Упавшее знамя", "Сломанный меч", "Сломанный щит", "Сломанная печатка". Трейты появляются у сыновей генералов в то время когда генералы достигают предельных значений трейтов командования , атаки , защиты и управления.
- Добавил новые трейты для отображения родовой принадлежности генералов.
- Добавил новый трейт "Легендарная ветвь рода".
- Добавил новые трейты для отображения происхождения дипломатов.
- Добавил новые трейты: "Начинающий в подготовке" ; "Разбирающийся в подготовке
" ; "Специалист по подготовке" ; "Мастер по подготовке" ; "Неинтересующийся подготовкой" ; "Безразличный к подготовке" ; "Некомпетентный в подготовке" ; "Невежественен в подготовке".
- Добавил новые трейты: "Терпим к другой культуре" ; "Уважает другую культуру" ; "Толерантен" ; "Предвзят к другой культуре" ; "Несправедлив к другой культуре" ; "Враждебен к другой культуре".
- Добавил новые трейты - новые города для "Рождение персонажа в знаменитом городе". Это города в которых появляются намесники.
- Добавил новый триггер - для "Рождение персонажа в знаменитом городе". Теперь в самом начале компании если генерал первый свой ход завершит в городе то получит трейт рождения в городе.
- добавил карьеры для культур: barbarian, carthaginian, eastern, egyptian, greek. Описание уровней поверхностное, главное работает механика, информацию по званиям в древние времена у меня не было ни времени ни желания чтобы начинать поиски. Условия появления званий такие же как и у римской культуры.
- добавил карьеры для адмиралов, описание уровней также поверхностные. Для начала карьеры необходимо чтобы адмирал получил любой из трейтов или любого из свиты. Так сделано для того чтобы у адмиралов без трейтов и свиты была возможность соединять войска. Условия появления званий:<br />
	1 уровень - 5 побед + 5 лет адмиральского стажа (который начисляется только после закрепления адмирала)<br />
	2 уровень - 12 побед + 9 лет адмиральского стажа<br />
	3 уровень - 19 побед + 12 лет адмиральского стажа<br />
	4 уровень - 27 побед + 15 лет адмиральского стажа<br />
	5 уровень - 35 побед + 18 лет адмиральского стажа<br />
	6 уровень - 40 побед + 21 год адмиральского стажа<br />
	7 уровень - 44 победы + 24 года адмиральского стажа<br />
	8 уровень - 48 побед + 27 лет адмиральского стажа<br />
	9 уровень - 52 победы + 30 лет адмиральского стажа<br />
- добавил трейт счетчика побед адмиралам. Отсчет будет начинаться после первой победы, чтобы до первой победы была возможность объединения флота.<br />
- добавил счетчик поражений генералов и адмиралов. (У адмиралов отсчет будет начинаться после первой победы, чтобы до первого поражения была возможность объединения флота.)<br />
- добавил новые трейты "пасхалки на пиратскую тематику" для адмиралов. После получения 5 побед адмиралом он при любом бое (победа или поражение) имеет очень маленький шанс получить трейты: "Деревянная нога" ; "Рука крюк" ; "Повязка на глазу". После получения 12 побед адмиралом он при следующих победах имеет очень маленький шанс получить трейты: "Черная борода" ; "Рыжая борода" ; "Синяя борода". Адмирал может получить только один какой то из этих трейтов за весь период своего существования. <br />
<b>--------добавление тригеров для оригинальных трейтов:</b>
- в файле export_descr_character_traits.txt был добавлен трейт Feck_NR, аналог трейта Feck только предназначенный не для римской культуры. Также был добавлен триггер selfperpetuating17_NR для этого трейта. 
- в файле export_descr_character_traits.txt были добавлены триггеры при битве: WonDefeat_t_k01 ; WonDefeat_t_k02 ; WonDefeat_t_k03 ; WonDefeat_t_k04 ; WonDefeat_t_k05 ; WonDefeat_t_k06 ; WonDefeat_t_k07 ; WonDefeat_t_k08 ; WonDefeat_t_k09 ; WonDefeat_t_k10 ; WonDefeat_t_k11 ; WonDefeat_t_k12 ; WonDefeat_t_k13 ; WonDefeat_t_k14 ; WonDefeat_t_k15 ; WonDefeat_t_k16 ; WonDefeat_t_k17 ; WonDefeat_t_k18 ; WonDefeat_t_k19 ; WonDefeat_t_k20 ; WonDefeat_t_k21 ; WonDefeat_t_k22 ; WonDefeat_t_k23 ; WonDefeat_t_k24 ; WonDefeat_t_k25 ; WonDefeat_t_k26 ; WonDefeat_t_k27 ; WonDefeat_t_k28 ; WonDefeat_t_k29 ; WonDefeat_t_k30 ; WonDefeat_t_k31 ; WonDefeat_t_k32 ; WonDefeat_t_k33 ; WonDefeat_t_k34 ; WonDefeat_t_k35 ; WonDefeat_t_k36.
- в файле export_descr_character_traits.txt были добавлены триггеры при существовании храма:  temple_of_love_t_k01 ; temple_of_love_t_k02 ; temple_of_fertility_t_k01 ; temple_of_leadership_t_k01 ; temple_of_fun_t_k01 ; temple_of_healing_t_k01 ; temple_of_healing_t_k02 ; temple_of_healing_t_k03 ; temple_of_healing_t_k04 ; temple_of_law_t_k01 ; temple_of_governors_t_k01 ; temple_of_one_god_t_k01 ; temple_of_battle_t_k01 ; temple_of_violence_t_k01 ; temple_of_violence_t_k02.
 (
   - В храме Любви теперь генерал сможет уменьшить трейт "Гнев" (Anger);
   - В храме Любви теперь генерал сможет уменьшить трейт "Кровавый" (Bloodthirsty);
   - В храме Плодородия теперь генерал сможет уменьшить трейт "Миньон" (Arse);
   - В храме Предводительства теперь генерал сможет уменьшить трейт "Плохо следящий за дисциплиной" (BadDisciplinarian);
   - В храме Развлечений теперь генерал сможет уменьшить трейт "Мрачный" (BlackBileHumour);
   - В храме Исцеления теперь генерал сможет уменьшить трейт "Сумасшедший" (Deranged);
   - В храме Исцеления теперь генерал сможет уменьшить трейт "Пьяница" (Drink);
   - В храме Исцеления теперь генерал сможет уменьшить трейт "Слюнявый идиот" (Inbred);
   - В храме Исцеления теперь генерал сможет уменьшить трейт "Ухающий" (Insane);
   - В храме Закона теперь генерал сможет уменьшить трейт "Жадный до денег" (Embezzler);
   - В храме Правителей теперь генерал сможет уменьшить трейт "Расточительный" (ExpensiveTastes);
   - В храме Одного Бога теперь генерал сможет уменьшить трейт "Игрок" (Gambling);
   - В храме Битвы теперь генерал сможет уменьшить трейт "Ненавидящий кровь" (Haemophobic);
   - В храме Жестокости теперь генерал сможет уменьшить трейт "Распущенный" (Lewd);
   - В храме Жестокости теперь генерал сможет уменьшить трейт "Аморальный тип" (Perverted);
 )
- в файле export_descr_character_traits.txt были добавлены триггеры при миссии агентов:  AgentsMission_t_k01 .
- в файле export_descr_character_traits.txt были добавлены триггеры при ночных сражениях:  NightBattle_t_k01 ; NightBattle_t_k02 ; NightBattle_t_k03 ; NightBattle_t_k04 ; NightBattle_t_k05 ; NightBattle_t_k06.
- в файле export_descr_character_traits.txt были добавлены триггеры при совершеннолетии:  dads_InspiringSpeaker ; dads_Intelligent1 ; dads_Intelligent2 ; dads_Intelligent3 ; ComesOfAge_t_k01 ; ComesOfAge_t_k02.
- в файле export_descr_character_traits.txt были добавлены триггеры при учебе: Learn_t_k01 ; Learn_t_k02 ; Learn_t_k03.
- в файле export_descr_character_traits.txt были добавлены триггеры при строительстве построек: BuildingCompleted_t_k01 ; BuildingCompleted_t_k02 ; BuildingCompleted_t_k03 ; BuildingCompleted_t_k04 ; BuildingCompleted_t_k05 ; BuildingCompleted_t_k06 ; BuildingCompleted_t_k07 ; BuildingCompleted_t_k08 ; BuildingCompleted_t_k09 ; BuildingCompleted_t_k10 ; BuildingCompleted_t_k11 ; BuildingCompleted_t_k12 ; BuildingCompleted_t_k13 ; BuildingCompleted_t_k14 ; BuildingCompleted_t_k15 ; BuildingCompleted_t_k16 ; BuildingCompleted_t_k17 ; BuildingCompleted_t_k18 ; BuildingCompleted_t_k19 ; BuildingCompleted_t_k20.
- в файле export_descr_character_traits.txt были добавлены триггеры при строительстве храмов: BuildingTempleCompleted_t_k01 ; BuildingTempleCompleted_t_k02 ; BuildingTempleCompleted_t_k03 ; BuildingTempleCompleted_t_k04 ; BuildingTempleCompleted_t_k05 ; BuildingTempleCompleted_t_k06 ; BuildingTempleCompleted_t_k07 ; BuildingTempleCompleted_t_k08 ; BuildingTempleCompleted_t_k09 ; BuildingTempleCompleted_t_k10 ; BuildingTempleCompleted_t_k11 ; BuildingTempleCompleted_t_k12 ; BuildingTempleCompleted_t_k13 ; BuildingTempleCompleted_t_k14 ; BuildingTempleCompleted_t_k15 ; BuildingTempleCompleted_t_k16 ; BuildingTempleCompleted_t_k17 ; BuildingTempleCompleted_t_k18 ; BuildingTempleCompleted_t_k19 ; BuildingTempleCompleted_t_k20 ; BuildingTempleCompleted_t_k21 ; BuildingTempleCompleted_t_k22 ; BuildingTempleCompleted_t_k23 ; BuildingTempleCompleted_t_k24 ; BuildingTempleCompleted_t_k25 ; BuildingTempleCompleted_t_k26 ; BuildingTempleCompleted_t_k27 ; BuildingTempleCompleted_t_k28 ; BuildingTempleCompleted_t_k29 ; BuildingTempleCompleted_t_k30 ; BuildingTempleCompleted_t_k31 ; BuildingTempleCompleted_t_k32 ; BuildingTempleCompleted_t_k33 ; BuildingTempleCompleted_t_k34 ; BuildingTempleCompleted_t_k35 ; BuildingTempleCompleted_t_k36 ; BuildingTempleCompleted_t_k37 ; BuildingTempleCompleted_t_k38 ; BuildingTempleCompleted_t_k39 ; BuildingTempleCompleted_t_k40 ; BuildingTempleCompleted_t_k41 ; BuildingTempleCompleted_t_k42 ; BuildingTempleCompleted_t_k43 ; BuildingTempleCompleted_t_k44 ; BuildingTempleCompleted_t_k45 ; BuildingTempleCompleted_t_k46 ; BuildingTempleCompleted_t_k47 ; BuildingTempleCompleted_t_k48 ; BuildingTempleCompleted_t_k49 ; BuildingTempleCompleted_t_k50 ; BuildingTempleCompleted_t_k51 ; BuildingTempleCompleted_t_k52 ; BuildingTempleCompleted_t_k53 ; BuildingTempleCompleted_t_k54 ; BuildingTempleCompleted_t_k55 ; BuildingTempleCompleted_t_k56 ; BuildingTempleCompleted_t_k57 ; BuildingTempleCompleted_t_k58 ; BuildingTempleCompleted_t_k59 ; BuildingTempleCompleted_t_k60.
- в файле export_descr_character_traits.txt были добавлены триггеры при дипломатической миссии: DiplomacyMission_t_k01 ; DiplomacyMission_t_k02 ; DiplomacyMission_t_k03 ; DiplomacyMission_t_k04 ; DiplomacyMission_t_k05 ; DiplomacyMission_t_k06 ; DiplomacyMission_t_k07 ; DiplomacyMission_t_k08 ; DiplomacyMission_t_k09 ; DiplomacyMission_t_k10 ; DiplomacyMission_t_k11 ; DiplomacyMission_t_k12 ; DiplomacyMission_t_k13 ; DiplomacyMission_t_k14 ; DiplomacyMission_t_k15 ; DiplomacyMission_t_k16 ; DiplomacyMission_t_k17 ; DiplomacyMission_t_k18 ; DiplomacyMission_t_k19 ; DiplomacyMission_t_k20 ; DiplomacyMission_t_k21 ; DiplomacyMission_t_k22.
- в файле export_descr_character_traits.txt были добавлены триггеры при найме:  GovernorTrained_t_k01 ; GovernorTrained_t_k02 ; GovernorTrained_t_k03 ; GovernorTrained_t_k04 ; GovernorTrained_t_k05 ; GovernorTrained_t_k06.
- в файле export_descr_character_traits.txt были добавлены триггеры для торговли:  GovernorTrader_t_k01 ; GovernorTrader_t_k02 ; GovernorTrader_t_k03 ; GovernorTrader_t_k04 ; GovernorTrader_t_k05 ; GovernorTrader_t_k06.
- в файле export_descr_character_traits.txt были добавлены триггеры для семьи: Family_t_k01 ; Family_t_k02 ; Family_t_k03 ; Family_t_k04 ; Family_t_k05 ; Family_t_k06 ; Family_t_k07 ; Family_t_k08 ; Family_t_k09 ; Family_t_k10 ; Family_t_k11 ; Family_t_k12 ; Family_t_k13 ; Family_t_k14 ; Family_t_k15 ; Family_t_k16 ; Family_t_k17 ; Family_t_k18 ; Family_t_k19 ; Family_t_k20 ; Family_t_k21 ; Family_t_k22 ; Family_t_k23 ; Family_t_k24 ; Family_t_k25 ; Family_t_k26.
- в файле export_descr_character_traits.txt были добавлены триггеры для увеличения имеющихся у генерала трейтов: selfperpetuating49 ; selfperpetuating50 ; selfperpetuating51 ; selfperpetuating52
- в файле export_descr_character_traits.txt были добавлены триггеры при губернаторстве с различной лояльностью и налогами : GovernorLoyalTax_t_k01 ; GovernorLoyalTax_t_k02 ; GovernorLoyalTax_t_k03 ; GovernorLoyalTax_t_k04 ; GovernorLoyalTax_t_k05 ; GovernorLoyalTax_t_k06 ; GovernorLoyalTax_t_k07 ; GovernorLoyalTax_t_k08.
- в файле export_descr_character_traits.txt были добавлены триггеры на дисциплину:  Disciplina_t_k01 ; Disciplina_t_k02 ; Disciplina_t_k03 ; Disciplina_t_k04 ; Disciplina_t_k05 ; Disciplina_t_k06 ; Disciplina_t_k07 ; Disciplina_t_k08 ; Disciplina_t_k09 ; Disciplina_t_k10 ; Disciplina_t_k11 ; Disciplina_t_k12 ; Disciplina_t_k13 ; Disciplina_t_k14 ; Disciplina_t_k15 ; Disciplina_t_k16 ; Disciplina_t_k17.
- в файле export_descr_character_traits.txt были добавлены триггеры на страх и ненависть к культуре: HateFear_t_k01 ; HateFear_t_k02 ; HateFear_t_k03 ; HateFear_t_k04 ; HateFear_t_k05 ; HateFear_t_k06 ; HateFear_t_k07 ; HateFear_t_k08 ; HateFear_t_k09 ; HateFear_t_k10 ; HateFear_t_k11 ; HateFear_t_k12 ; HateFear_t_k13 ; HateFear_t_k14 ; HateFear_t_k15 ; HateFear_t_k16 ; HateFear_t_k17.<br />


<b>Исправления к Egermejster от kotLeon:</b>
- исправлены тригеры рождения персонажа в знаменитом городе - теперь трейты присваиваются, но только в конце хода. То есть новый генерал который появился (при совершеннолетии, свадьбе или усыновлении) должен завершить свой первый ход в городе иначе трейт рождения в знаменитом городе присвоен не будет.
- добавил тригер для страта трейтов NoteRange и AmountWin0. Теперь ненужно прописывать эти трейты в файле descr_strat.txt.
- трейт счетчика количества побед был полностью переделан. Раньше некоторые уровни в трейтах счетчика дублировались, теперь каждый уровень уникальный. Довёл максимум счетчика до 81 победы.
- трейты карьеры рима были объеденины в один трейт "Roman_career" а (Декурион, Центурион, Примипил, Префект, Трибун) стали уровнями этого трейта. Плюс еще были добавлены 4 уровня к карьере. Всего теперь будет 9 уровней карьеры, а также теперь для получения звания можно использовать губернаторский стаж (просто его нужно будет больше чем военного). Условия появления званий:<br />
	1 уровень (Рим - Декурион) - 5 побед<br />
	2 уровень (Рим - Центурион) - 12 побед<br />
	3 уровень (Рим - Примипил) - 19 побед + 10 лет военной службы или 15 лет губернаторского стажа<br />
	4 уровень (Рим - Префект) - 27 побед + 15 лет военной службы или 20 лет губернаторского стажа<br />
	5 уровень (Рим - Трибун) - 35 побед + 20 лет военной службы или 25 лет губернаторского стажа<br />
	6 уровень - 40 побед + 23 года военной службы или 29 лет губернаторского стажа<br />
	7 уровень - 44 победы + 26 лет военной службы или 33 года губернаторского стажа<br />
	8 уровень - 48 побед + 29 лет военной службы или 37 лет губернаторского стажа<br />
	9 уровень - 52 победы + 32 года военной службы или 41 год губернаторского стажа<br />
Военный стаж и губернаторский стаж учитываются одновременно, к примеру если для получения 3 уровня карьеры использовался военный стаж 10 лет, а потом генерал стал губернатором, то после достижения 15 лет губернаторского стажа генерал получит 4 уровень карьеры, если конечно были получены победы в  удовлетворяющем количестве.
- бонусы от званий карьеры были существенно изменены, полностью убраны плюсы к командованию вместо них были добавлены плюсы к влиянию.
- трейты "Губернаторской системы" и "Военной службы" были полностью переделаны. Раньше уровни в трейтах дублировались, и на 8, 16, 24 годах зависали 3 хода, а на 9 и 17 годах пролетали за один ход, также на некоторых уровнях было несоответствие описания и реально установленных эффектов. Теперь каждый уровень уникальный, а зависаний и проскальзываний годов нет. Также довёл максимум "Губернаторской системы" и "Военной службы" до 45 лет. Бонусы остались почти что те же самые, просто теперь растянуто их появление на более длинный срок.
- система обучения была разделена на 3 этапа, 1 этап - при постройке Академии, 2 этап - при постройке Скриптория, 3 этап - при постройке Ludus Magna. Бонусы остались те же что и были, только с разделением по этапам.
- трейт NoLearn (неспособность к обучению) работал некорректно, после того как он появлялся у персонажа, то на следующий ход исчезал когда начиналось обучение. Теперь если персонажу "посчастливиться" словить этот трейт то это навсегда. Уменьшил вероятность появления до 1% с 12% для персонажей не варварской культуры, а также увеличил  вероятность появления до 20% для персонажей варварской культуры. Добавил возможность появленя этого трейта при найме агентов, с такими же шансами как и у генералов.
- в файле export_descr_character_traits.txt ошибка в названии уровня у трейта Triumth_julii. В файле прописан Triumth_1_west а должно быть Triumth_1_julii. Исправил.
- для трейтов "Претендует на Триумф" и "Триумфатор" добавил текстовое оповещение о появлении трейтов и эпитет "Триумфатор" для персонажа.
- в файле export_VnVs.txt тейт "Вырос в Сиракузах" был прописан с ошибками - поправил его.
- в файле export_descr_ancillaries.txt триггеры 3_Governor_of_Hispania ; 3_eg_Governor_of_Hispania ; 3_num_Governor_of_Hispania ; 3_p_Governor_of_Hispania ; 3_j_Governor_of_Hispania ; 3_b_Governor_of_Hispania ; 3_s_Governor_of_Hispania ; 3_sel_Governor_of_Hispania ; 3_po_Governor_of_Hispania ; 3_m_Governor_of_Hispania ; 3_greek_Governor_of_Hispania ; 3_thr_Governor_of_Hispania ; 3_arm_Governor_of_Hispania с ошибками, вместо испанских городов проставлены британские. Исправил на испанские.
- в файле export_descr_ancillaries.txt триггеры 1_Governor_of_Germany ; 1_eg_Governor_of_Germany ; 1_num_Governor_of_Germany ; 1_p_Governor_of_Germany ; 1_j_Governor_of_Germany ; 1_b_Governor_of_Germany ; 1_s_Governor_of_Germany ; 1_sel_Governor_of_Germany ; 1_po_Governor_of_Germany ; 1_m_Governor_of_Germany ; 1_greek_Governor_of_Germany ; 1_thr_Governor_of_Germany ; 1_arm_Governor_of_Germany с ошибками, проставлены лишние условия проверки атрибутов. Исправил, убрал лишние условия.
- У Trait AmountWin1-9 , AmountWin10-18 , AmountWin10-18 , CommandSettlement1-9 , CommandSettlement9-17 , CommandSettlement17-25 , CommandArmy1-9 , CommandArmy10-18 , CommandArmy17-25 убрал тире из имени и заменил на нижнее подчеркивание: AmountWin1_9 , AmountWin10_18 , AmountWin10_18 , CommandSettlement1_9 , CommandSettlement9_17 , CommandSettlement17_25 , CommandArmy1_9 , CommandArmy10_18 , CommandArmy17_25
- в файле export_descr_character_traits.txt изменил имена триггеров у которых одинаковые имена с трейтами. Было: NoLearn ; LuernAcademy ; Learn_Diplomat ; Learn_Spy ; Learn_Assassin. Стало: NoLearn_t1 ; LuernAcademy_t1 ; Learn_Diplomat_t1 ; Learn_Spy_t1 ; Learn_Assassin_t1.
- в файле export_descr_character_traits.txt добавил триггер NoLearn_t2 в котором присваивается трейт NoLearn нанимаемым агентам.<br />


<b>Исправления к оригиналу от kotLeon:</b>
- У ancillary evil_mother-in-law убрал тире из имени и заменил на нижнее подчеркивание: evil_mother_in_law 
- У ancillary aristarchus_of_samos заменил эффект с "полководца на море" на "+ к пунктам перемещения", так как эффект "покловодец на море" бессмысленный у генералов.
- в файле export_descr_ancillaries.txt добавил триггеры для появления жрецов храмов в Испании и Нумидии (в оригинале у них отсутствуют жрецы)
- в файле export_descr_ancillaries.txt добавил триггер для появления Хирурга у генерала и адмирала после победы при потерях более 30%.
- в файле export_descr_ancillaries.txt добавил триггер для появления Ворожеи у генерала после победы при потерях более 30%.
- в файле export_descr_ancillaries.txt изменил триггер trigger_Navigator, у Condition RemainingMPPercentage изменилось значение с "= 0" на "<= 1". Так как у Condition RemainingMPPercentage не может быть нулевых значений.
- в файле export_descr_ancillaries.txt выровнял ExcludedAncillaries, чтобы если у одного ancillary присутствовал запрет на другого, то другому ancillary также нужен запрет на первого.
 ( 
   - ancillary evil_mother_in_law добавил заперты на problem_mother и elderly_spinster_aunt, так как у problem_mother и elderly_spinster_aunt в оригинале есть запрет на evil_mother_in_law;
   - ancillary playwright добавил заперты на biographer и poet, так как у biographer и poet в оригинале есть запрет на playwright;
   - ancillary comedian добавил заперт на poet, так как у poet в оригинале есть запрет на comedian;
   - ancillary herbalist добавил заперты на chirugeon и  wise_woman, так как у chirugeon и  wise_woman в оригинале есть запрет на herbalist;
   - ancillary doctor добавил заперт на wise_woman, так как у wise_woman в оригинале есть запрет на doctor;
   - ancillary chirugeon добавил заперт на wise_woman, так как у wise_woman в оригинале есть запрет на chirugeon;
   - ancillary master_of_assassins добавил заперты на cook, gourmands_chef и wine_steward, так как у cook, gourmands_chef и wine_steward в оригинале есть запрет на master_of_assassins;
   - ancillary catamite добавил заперт на courtesan, так как у courtesan в оригинале есть запрет на catamite;
   - ancillary elder_senator добавил заперты на senatorial_horse и tribune_of_the_plebs, так как у senatorial_horse и tribune_of_the_plebs в оригинале есть запрет на elder_senator. А также у ancillary elder_senator убрал запрет на mentor, так как у elder_senator уже достигнут предел в 3 запрета.;
   - ancillary honest_man добавил заперты на crooked_judge и crooked_judge2, так как у crooked_judge и crooked_judge2 в оригинале есть запрет на honest_man;
   - ancillary judge добавил заперт на crooked_judge2, так как у crooked_judge2 в оригинале есть запрет на judge;
   - ancillary over_protective_nanny добавил заперт на evil_mother_in_law, так как у evil_mother_in_law в оригинале есть запрет на over_protective_nanny;
   - ancillary biographer добавил заперт на historian, так как у historian в оригинале есть запрет на biographer;
   - ancillary idiot добавил заперт на idiot_savant, так как у idiot_savant в оригинале есть запрет на idiot;
   - ancillary exotic_slave добавил заперт на barbarian_slave, так как у barbarian_slave в оригинале есть запрет на exotic_slave;
   - у ancillary pet_monkey убрал заперты на pet_lion и pet_hunting_dog, так как pet_lion и pet_hunting_dog появляются у генералов, а не у агентов;
   - у ancillary pet_white_cat убрал заперты на pet_lion и pet_hunting_dog, так как pet_lion и pet_hunting_dog появляются у генералов, а не у агентов;
   - у ancillary librarian убрал заперты на actor и comedian, так как у actor и comedian возможно превышение лимита на 3 запрета;
   - ancillary aged_retainer добавил заперт на mentor, так как у mentor в оригинале есть запрет на aged_retainer. А также у ancillary aged_retainer убрал запрет на evil_mother_in_law, так как у evil_mother_in_law уже достигнут предел в 3 запрета.
   - ancillary architect добавил заперт на sculptor, так как у sculptor в оригинале есть запрет на architect;
   - ancillary surveyor добавил заперт на sculptor, так как у sculptor в оригинале есть запрет на surveyor;
   - ancillary senatorial_horse добавил заперт на trusty_steed, так как у trusty_steed в оригинале есть запрет на senatorial_horse;
   - ancillary drinking_companion добавил заперт на tutor, так как у tutor в оригинале есть запрет на drinking_companion;
   - ancillary pontifex добавил заперт на wilderness_prophet, так как у wilderness_prophet в оригинале есть запрет на pontifex;
   - у ancillary ariston_of_cyrene убрал заперты на comedian и playwright, так как у comedian и playwright возможно превышение лимита на 3 запрета;
   - у ancillary callimachus_of_cyrene убрал заперты на actor и playwright, так как у actor и playwright возможно превышение лимита на 3 запрета;
   - у ancillary quintus_lutatius_catulus убрал заперты на elder_senator и honest_man, так как у elder_senator и honest_man возможно превышение лимита на 3 запрета;
   - у ancillary gaius_valerius_catullus убрал заперты на elder_senator и honest_man, так как у elder_senator и honest_man возможно превышение лимита на 3 запрета;
   - у ancillary chrysippus убрал заперты на actor и comedian, так как у actor и comedian возможно превышение лимита на 3 запрета;
   - у ancillary iunius_pennus убрал заперты на crooked_judge и tribune_of_the_plebs, так как у crooked_judge и tribune_of_the_plebs возможно превышение лимита на 3 запрета;
   - у ancillary m_porcius_cato убрал заперты на biographer и comedian, так как у biographer и comedian возможно превышение лимита на 3 запрета;
   - у ancillary polybius_of_megalopolis убрал заперт на biographer, так как у biographer возможно превышение лимита на 3 запрета;
 )
- в файле export_descr_ancillaries.txt в триггере trigger_cook убрал условие IsGeneral, чтобы повар появлялся не только у генералов.
- в файле export_descr_ancillaries.txt добавил триггер trigger_foodtaster_NG для появления ancillary foodtaster при покушении не на генералов.
- У Trait Irredeemably_Foul-mouthed убрал тире из имени и заменил на нижнее подчеркивание: Irredeemably_Foul_mouthed 
- У Trait Won't_Take_No_For_An_Answer убрал апостроф из имени: Wont_Take_No_For_An_Answer
- У Trait Into_The_Breach! убрал восклицательный знак  из имени: Into_The_Breach
- У Trait None_Shall_Pass! убрал восклицательный знак  из имени: None_Shall_Pass
- У Trait Tub-Thumper убрал тире из имени и заменил на нижнее подчеркивание: Tub_Thumper 
- У Trait Counter-Spy убрал тире из имени и заменил на нижнее подчеркивание: Counter_Spy 
- У Trait Counter-Espionage убрал тире из имени и заменил на нижнее подчеркивание: Counter_Espionage
- У Trait Immune_to_Death? убрал вопросительный знак  из имени: Immune_to_Death
- У Trait Ham-fisted_Murderer убрал тире из имени и заменил на нижнее подчеркивание: Ham_fisted_Murderer
- У Trait Rods-And-Axes убрал тире из имени и заменил на нижнее подчеркивание: Rods_And_Axes
- У Trait Cuckold's_Cuckold убрал апостроф из имени: Cuckolds_Cuckold
- У Trait Even-handed убрал тире из имени и заменил на нижнее подчеркивание: Even_handed
- У Trait Wrong-headed убрал тире из имени и заменил на нижнее подчеркивание: Wrong_headed
- У Trait Hero-Worships_Gladiators убрал тире из имени и заменил на нижнее подчеркивание: Hero_Worships_Gladiators
- У Trait Open-handed убрал тире из имени и заменил на нижнее подчеркивание: Open_handed
- У Trait Tight-fisted убрал тире из имени и заменил на нижнее подчеркивание: Tight_fisted
- У Trait Loose-lipped убрал тире из имени и заменил на нижнее подчеркивание: Loose_lipped
- У Trait Close-mouthed убрал тире из имени и заменил на нижнее подчеркивание: Close_mouthed
- У Trait Despises_Trouser-wearers убрал тире из имени и заменил на нижнее подчеркивание: Despises_Trouser_wearers
- У Trait Hates_Clever-clever_Greeks убрал тире из имени и заменил на нижнее подчеркивание: Hates_Clever_clever_Greeks
- У Trait Swivel-Eyed убрал тире из имени и заменил на нижнее подчеркивание: Swivel_Eyed
- У Trait Thin-Skulled убрал тире из имени и заменил на нижнее подчеркивание: Thin_Skulled
- У Trait Weak-chinned убрал тире из имени и заменил на нижнее подчеркивание: Weak_chinned
- У Trait Over-Optimistic убрал тире из имени и заменил на нижнее подчеркивание: Over_Optimistic
- У Trait Given_to_Ill-Health убрал тире из имени и заменил на нижнее подчеркивание: Given_to_Ill_Health
- У Trait Lily-Livered убрал тире из имени и заменил на нижнее подчеркивание: Lily_Livered
- У Trait Over-Cautious_Attacker убрал тире из имени и заменил на нижнее подчеркивание: Over_Cautious_Attacker
- изменил имена уровней Trait которые совпадали с именами самих трейтов: 
 (
 - Имя Brave поменял на Brave_lvl; 
 - Имя Energetic поменял на Energetic_lvl; 
 - Имя Berserker поменял на Berserker_lvl; 
 - Имя Warlord поменял на Warlord_lvl; 
 - Имя Rabblerouser поменял на Rabblerouser_lvl; 
 - Имя Stoic поменял на Stoic_lvl; 
 - Имя Austere поменял на Austere_lvl; 
 - Имя Trusting поменял на Trusting_lvl; 
 - Имя Liar поменял на Liar_lvl; 
 - Имя Embezzler поменял на Embezzler_lvl; 
 - Имя Disloyal поменял на Disloyal_lvl; 
 - Имя Loyal поменял на Loyal_lvl; 
 - Имя Cuckold поменял на Cuckold_lvl; 
 - Имя Just поменял на Just_lvl; 
 - Имя Unjust поменял на Unjust_lvl; 
 - Имя Generous поменял на Generous_lvl; 
 - Имя Talkative поменял на Talkative_lvl; 
 - Имя Handsome поменял на Handsome_lvl; 
 - Имя Ugly поменял на Ugly_lvl; 
 - Имя Fertile поменял на Fertile_lvl; 
 - Имя Infertile поменял на Infertile_lvl; 
 - Имя Superstitious поменял на Superstitious_lvl; 
 - Имя Pragmatic поменял на Pragmatic_lvl; 
 - Имя Cheapskate поменял на Cheapskate_lvl; 
 - Имя Hypochondriac поменял на Hypochondriac_lvl; 
 - Имя Sane поменял на Sane_lvl; 
 - Имя Deranged поменял на Deranged_lvl; 
 - Имя Bloodthirsty поменял на Bloodthirsty_lvl; 
 - Имя Anger поменял на Anger_lvl; 
 - Имя Prim поменял на Prim_lvl; 
 - Имя Miserly поменял на Miserly_lvl; 
 - Имя Upright поменял на Upright_lvl; 
 - Имя Pious поменял на Pious_lvl; 
 - Имя Sacrilegious поменял на Sacrilegious_lvl; 
 - Имя Lewd поменял на Lewd_lvl; 
 - Имя Despoiler поменял на Despoiler_lvl; 
 - Имя Divorced поменял на Divorced_lvl; 
 )
- в файле export_descr_character_traits.txt изменил имена триггеров у которых одинаковые имена с трейтами. Было: notAedile ; notCensor ; notConsul ; notPontifexMaximus ; notPraetor ; notQuaestor ; factionleader. Стало: notAedile_t ; notCensor_t ; notConsul_t ; notPontifexMaximus_t ; notPraetor_t ; notQuaestor_t ; factionleader_t.
- в файле export_descr_character_traits.txt изменил имя триггера у которого одинаковое имя с именем события. Было: LesserGeneralOfferedForAdoption. Стало: LesserGeneralOfferedForAdoption1.
- в файле export_descr_character_traits.txt изменил триггер harsh_lifestyle3, у Condition RemainingMPPercentage изменилось значение с "= 0" на "<= 1". Так как у Condition RemainingMPPercentage не может быть нулевых значений.
- в файле export_descr_character_traits.txt выровнял AntiTraits, чтобы если у одного Trait присутствовал Anti на другого, то другому Trait также нужен Anti на первого.
 ( 
   - трейту Sane добавил Anti на Bloodthirsty, так как у Bloodthirsty в оригинале есть Anti на Sane;
   - трейту Aesthetic добавил Anti на Cheapskate, так как у Cheapskate в оригинале есть Anti на Aesthetic;
   - трейту Cuckold добавил Anti на Divorced и WellConnectedWife, так как у Divorced и WellConnectedWife в оригинале есть Anti на Cuckold;
   - трейту FaithfulWife добавил Anti на Divorced, так как у Divorced в оригинале есть Anti на FaithfulWife;
   - трейту WellConnectedWife добавил Anti на Divorced, так как у Divorced в оригинале есть Anti на WellConnectedWife;
   - трейту Factionheir добавил Anti на Factionleader, так как у Factionleader в оригинале есть Anti на Factionheir;
   - трейту RhetoricSkill добавил Anti на Feck, так как у Feck в оригинале есть Anti на RhetoricSkill;
   - трейту Inbred добавил Anti на Fertile, так как у Fertile в оригинале есть Anti на Inbred;
   - трейту Prim добавил Anti на Girls, так как у Girls в оригинале есть Anti на Prim;
   - трейту GoodAttacker добавил Anti на GloriousFool и IndecisiveAttacker, так как у GloriousFool и IndecisiveAttacker в оригинале есть Anti на GoodAttacker;
   - трейту GoodDefender добавил Anti на GloriousFool, так как у GloriousFool в оригинале есть Anti на GoodDefender;
   - трейту GoodRiskyAttacker добавил Anti на GloriousFool и IndecisiveAttacker, так как у GloriousFool и IndecisiveAttacker в оригинале есть Anti на GoodRiskyAttacker;
   - трейту GoodRiskyDefender добавил Anti на GloriousFool, так как у GloriousFool в оригинале есть Anti на GoodRiskyDefender;
   - трейту NonAuthoritarian добавил Anti на HarshRuler, так как у HarshRuler в оригинале есть Anti на NonAuthoritarian;
   - трейту AuthoritarianRomanVirtue добавил Anti на KindRuler, так как у KindRuler в оригинале есть Anti на AuthoritarianRomanVirtue;
   - трейту Authoritarian добавил Anti на KindRuler, так как у KindRuler в оригинале есть Anti на Authoritarian;
   - трейту Feck добавил Anti на Prim, так как у Prim в оригинале есть Anti на Feck. А также убрал Anti на SmoothTalker, так как SmoothTalker трейт для дипломата а не генерала;
   - трейту Girls добавил Anti на WellConnectedWife, так как у WellConnectedWife в оригинале есть Anti на Girls;
   - у трейта SmoothTalker убрал Anti на Feck, так как Feck трейт для генерала а не дипломата;
   - трейту GamesFanRomanVice добавил Anti на Haemophobic;
   - трейту Haemophobic добавил Anti на GamesFanRomanVice;
   - трейту PublicFaith добавил Anti на Sacrilegious;
   - трейту Sacrilegious добавил Anti на PublicFaith;
   - трейту Pious добавил Anti на PublicAtheism;
   - трейту PublicAtheism добавил Anti на Pious и ReligiousMania;
   - трейту ReligiousMania добавил Anti на PublicAtheism;
   - трейту HarshJustice добавил Anti на KindRuler и NonAuthoritarian;
   - трейту KindRuler добавил Anti на HarshJustice;
   - трейту NonAuthoritarian добавил Anti на HarshJustice;
   - трейту HarshRuler добавил Anti на Just и LenientJustice;
   - трейту Just добавил Anti на HarshRuler;
   - трейту Authoritarian добавил Anti на LenientJustice;
   - трейту AuthoritarianRomanVirtue добавил Anti на LenientJustice;
   - трейту Cheapskate добавил Anti на Generous;
   - трейту Generous добавил Anti на Cheapskate и Austere;
   - трейту ExpensiveTastes добавил Anti на Miserly;
   - трейту Miserly добавил Anti на ExpensiveTastes и Aesthetic;
   - трейту Aesthetic добавил Anti на Miserly;
   - трейту Austere добавил Anti на Generous;
   - трейту BadBuilder добавил Anti на ArchitectSkill;
   - трейту ArchitectSkill добавил Anti на BadBuilder;
   - трейту Gambling добавил Anti на GamesHaterRomanVice и RacesHaterRomanVice;
   - трейту GamesHaterRomanVice добавил Anti на Gambling;
   - трейту RacesHaterRomanVice добавил Anti на Gambling;
   - трейту Disciplinarian добавил Anti на Slothful;
   - трейту Slothful добавил Anti на Disciplinarian;
   - у трейта LostEagle убрал Anti на RegainedEagle;
   - у трейта RegainedEagle убрал Anti на LostEagle;
 ) 
- в файле export_descr_character_traits.txt были изменены определения Characters трейтов GoodConspirator и BadConspirator с spy, assassin на all. Так как в Characters реально учитывается только первый параметр, а все остальные дальше игнорируются обработчиком.
- в файле export_descr_character_traits.txt были изменены определения Characters трейтов Disloyal и Loyal с family на all. Чтобы трейт появлялся и у дипломатов.
- в файле export_descr_character_traits.txt было изменено определение Characters трейта SmoothTalker с family на diplomat. Так как трейт SmoothTalker для дипломата а не генерала.
- в файле export_descr_character_traits.txt были удалены NoGoingBackLevel трейтов: Generous ; Miserly ; PublicAtheism ; PublicFaith ; ReligiousMania ; Pious ; Sacrilegious.
- в файле export_descr_character_traits.txt было изменено определение NoGoingBackLevel трейтов: GoodTrader на 3 ; BadTrader на 3 ; HarshJustice на 3 ; HarshRuler на 3.
- в файле export_descr_character_traits.txt были удалены ExcludeCultures трейтов: InspiringSpeaker ; BoringSpeaker ; Pious.
- в файле export_descr_character_traits.txt было изменено определение Threshold трейтов: для первого уровня Generous; для трех уровней BadFarmer; для трех уровней BadTrader; для трех уровней Cuckold; для трех уровней WellConnectedWife.
- в файле export_descr_character_traits.txt из триггера random_birth27 было удалено присвоение трейта GoodConspirator. Так как трейт GoodConspirator предназначен для агентов типа шпион и ассассин, но никак не для генерала. Также в триггер было добавлено присвоение трейта Pragmatic.
- в файле export_descr_character_traits.txt из триггера random_birth35 было удалено присвоение трейта ForeignTastesRomanVice. Так как трейт ForeignTastesRomanVice предназначен для дипломата, но никак не для генерала. Также в триггер было добавлено присвоение трейта PlainRomanVirtue.
- в файле export_descr_character_traits.txt из триггера temple_of_healing_vnv_trigger было удалено присвоение трейта Hypochondriac. Так как условия срабатывания триггера не подходят свойствам трейта.
- в файле export_descr_character_traits.txt из триггера temple_of_law_vnv_trigger было удалено присвоение трейта HarshJustice, и добавлено присвоение трейта Just.
- в файле export_descr_character_traits.txt триггеру spying_target было добавлено присвоение трейта Xenophobia.
- в файле export_descr_character_traits.txt триггерам с проверкой наличия храма было добавлено присвоение трейта PublicFaith. Измененные триггеры: temple_of_fun_vnv_trigger ; temple_of_love_vnv_trigger ; temple_of_law_vnv_trigger ; temple_of_battle_vnv_trigger ; temple_of_battleforge_vnv_trigger ; temple_of_farming_vnv_trigger ; temple_of_fertility_vnv_trigger ; temple_of_forge_vnv_trigger ; temple_of_governors_vnv_trigger ; temple_of_healing_vnv_trigger ; temple_of_horse_vnv_trigger ; temple_of_hunting_vnv_trigger ; temple_of_justice_vnv_trigger ; temple_of_leadership_vnv_trigger ; emple_of_one_god_vnv_trigger ; temple_of_trade_vnv_trigger ; temple_of_victory_vnv_trigger ; temple_of_violence_vnv_trigger ; temple_of_viking_vnv_trigger ; temple_of_horse_2_vnv_trigger.
- в файле export_descr_character_traits.txt из триггера temple_of_justice_vnv_trigger было удалено присвоение трейта Just.
- в файле export_descr_character_traits.txt триггер dads_SmoothTalker был удален. Так как трейт SmoothTalker предназначен для дипломата, но никак не для генерала.
- в файле export_descr_character_traits.txt триггер selfperpetuating24 был удален. Так как для трейта Lewd было создано несколько более подходящих триггеров.
- в файле export_descr_character_traits.txt для трейта Feck были добавлены ExcludeCultures : carthaginian, eastern, egyptian, greek, barbarian. Так как трейт Feck предназначен для культуры roman.
- в файле export_descr_character_traits.txt для триггеров на трейт Feck были добавлены появления трейта Feck_NR. Изменены триггеры : sitting_around_camo_vnv_trigger ; dads_prim ; random_birth12. 
- в файле export_descr_character_traits.txt для трейта Exheir был добавлен триггер ExheirIsFactionLeader. Нужен в ситуации когда лидер фракции и наследник погибают в одной и той же битве, и лидером фракции становится ранее отвергнутый в наследовании.
- в файле export_descr_character_traits.txt были изменены условия срабатывания триггеров на назначение сенатских должностей : AedileFirstTime ; CensorFirstTime ; ConsulFirstTime ; PontifexMaximusFirstTime ; PraetorFirstTime ; QuaestorFirstTime. В условия была добавлена проверка на то что это первое срабатывание. Чтобы при повторном назначении на одну и ту же должность корректно отображалось в трейтах.
- в файле export_descr_character_traits.txt были изменены условия срабатывания триггеров : selfperpetuating1 ; selfperpetuating3 ; selfperpetuating6 ; selfperpetuating7 ; selfperpetuating38 ; selfperpetuating42 ; selfperpetuating43 ; selfperpetuating44 ; selfperpetuating47. В условия была добавлена проверка на то что персонаж завершил ход в городе. Чтобы трейты из триггеров не срабатывали для персонажей вне города.
- в файле export_descr_character_traits.txt были изменены условия срабатывания триггеров : governing6 ; governing10. В условия была добавлена проверка на существование определенного строения. Чтобы трейты из триггеров не срабатывали при завершении любой постройки. Также были увеличены шансы появления трейтов в этих триггерах.
- в файле export_descr_character_traits.txt были изменены условия срабатывания триггеров на достижение совершеннолетия : dads_politics_skilled ; dads_prim ; dad_loves_games ; dad_loves_races ; dad_hates_games ; dad_generous ; dad_mean ; dad_likes_girls ; dads_perverted ; dads_PublicAtheism ; dads_Xenophilia ; dads_Xenophobia ; random_birth3 ; random_birth4 ; random_birth8 ; random_birth9 ; random_birth10 ; random_birth11 ; random_birth12 ; random_birth13 ; random_birth14 ; random_birth15 ; random_birth16 ; random_birth17 ; random_birth18 ; random_birth19 ; random_birth20 ; random_birth21 ; random_birth22 ; random_birth23 ; random_birth24 ; random_birth25 ; random_birth26 ; random_birth27 ; random_birth29 ; random_birth30 ; random_birth31 ; random_birth32 ; random_birth33 ; random_birth34 ; random_birth35 ; random_birth38 ; random_birth39 ; random_birth40. В условиях были увеличены получаемые очки к уровню трейта. Чтобы при достижении совершеннолетия и успешном срабатывании условий у генерала сразу появлялся уровень трейта, а не 1 очко от уровня.
- в файле export_descr_character_traits.txt были изменены условия срабатывания триггеров при усыновлении : V0250a_Worthy_Of_Adoption_2_VnV_Trigger. В условиях были увеличены получаемые очки к уровню трейта. Чтобы при усыновлении и успешном срабатывании условий у генерала сразу появлялся уровень трейта, а не 1 очко от уровня.
- в файле export_descr_character_traits.txt были изменены условия срабатывания триггеров после принятия предложения о браке : V0260a_Worthy_Of_Marriage_2_VnV_Trigger ; family8 ; family9 ; family10. В условиях были увеличены получаемые очки к уровню трейта. Чтобы при принятии предложения о браке и успешном срабатывании условий у генерала сразу появлялся уровень трейта, а не 1 очко от уровня.
- в файле export_descr_character_traits.txt были изменены условия срабатывания триггеров при приянтии в семью за военные заслуги : LesserGeneralOfferedForAdoption2. В условиях были увеличены получаемые очки к уровню трейта. Чтобы при приянтии в семью за военные заслуги и успешном срабатывании условий у генерала сразу появлялся уровень трейта, а не 1 очко от уровня.
- в файле export_descr_character_traits.txt были изменены условия срабатывания триггеров на найм агентов : spyinit1. В условиях были увеличены получаемые очки к уровню трейта. Чтобы при найме агентов и успешном срабатывании условий у агента сразу появлялся уровень трейта, а не 1 очко от уровня.
- в файле export_descr_character_traits.txt были изменены триггеры : family1 (шансы появления трейта Corrupt) ; family2 (увеличены очки трейтов Gambling и Girls) ; family15 (шансы появления трейта GoodTrader) ; governing7 (увеличены очки трейта GoodMiner) ; governing11 (увеличены очки трейта Girls) ; family3 (шансы появления трейта IanR).
- в файле export_descr_character_traits.txt был изменен триггер : random_birth37. Было удалено появление трейта PoeticSkill, так как трейт в тригере появлялся дважды. Заместь удаленного было поставлено появление трейта NaturalPhilosophySkill.
- в файле export_descr_character_traits.txt был изменен триггер : random_birth39. Было удалено появление трейтов DeceiverVirtue и NaturalPhilosophySkill, так как трейты не появлялись в любом случае из за блока по типу культуры. Заместь удаленных было поставлено появление трейта ReligiousMania.
- в файле export_descr_character_traits.txt был изменен триггер : admiral1 для трейта Sailor. Был изменен диапазон по шансу на победу с BattleOdds < 2.25 на BattleOdds < 1.55. Т.е. трейт теперь получить будет немного сложнее.
- изменены параметры свиты "Госпожа". Добавлены к существующему +1 к управлению дополнительно еще +1 к влиянию и 10% увеличение налоговых сборов.
- изменены параметры свиты "Сборщик налогов". К существующим 5% добавлено +10% к увеличению налоговых сборов.
- изменены параметры свиты "Навигатор". Убрано +1 к командованию на море и добавлено +15% к передвижению.
- изменены параметры свиты "Жрец Нептуна". Добавлено +10% к передвижению.
