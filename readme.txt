Настройки и перечень плагинов, необходимых для работы создания сайтов под ключ.

Как использовать настройки:
1. Установите редактор Sublime Text 3.
2. Закройте редактор.
3. Скачайте архив с репозитория, разархивируйте его на жесткий диск компьютера
4. Переместите каталог Sublime Text 3 в каталог Roaming 
c:\Users\Username\AppData\Roaming  

Перечень плагинов Sublime Text 3.

1 Package Control - управления плагинами Sublime Text 3: https://packagecontrol.io/installation
2 Agila Theme - как по мне довольно удобная и тема с использованием контрасных цветов, имеет опции для настройки темы:  https://packagecontrol.io/packages/Agila%20Theme
3 AlignTab - добавляет в контекстное меню возможности выравнивания по нескольким регулярным выражениям.
4 AutoFileName - автозаполнение путей в процессе подключения медийных файлов к проекту
5 BracketHighlighter - подсвечивает строки с открывающей и закрывающей скобками/тегами
6 Emmet - плагин для быстрого написания html и css путем введения простых сокращений и разворячивания в сложный код после нажатия кнопки Tab
7 Sublimerge Pro  3 - позволяет вам увидеть различия между двумя и даже тремя файлами в SublimeText.
8 Goto-CSS-Declaration - при клике на класс или айдишник, курсор сразу перебрасывается на место, где этот класс(айди) объявлен
9 Color Highlighter - подсвечивает все вариации цветов, которые встречаются в коде: HEX, RGB, RGBA и цвета по именам (green, red).
10 SideBarEnhancement — множество дополнительных функций контекстного меню в сайдбаре.
11 BufferScroll - при повторном открытии документа устанавливает курсор на том месте, на котором было завершена работа.
12 CSSComb - комбинирует CSS свойства в определенном порядке
13 CSS Format -  для преобразования CSS, SASS, SCSS, LESS код в расширенный, компактный или сжатый формат. 
14 Minifier - максимально минифицирует css-код.
15 CSS Unminifier - преобразует минифицированный css-код в обычный читаемый код. 
16 CCS3 - дополнения для подсветки синтаксиса CCS v.3.
17 SCSS - дополнения для подсветки синтаксиса SCSS-препроцессора.
18 HTML5 - имеет подсветку синтаксиса html5.
19 JQUERY - помогает писать jqury функции, имеет подсветку синтаксиса jquery.
20 Wordpress - помогает писать wordpress функции, имеет подсветку синтаксиса wordpress функций.  
21 Terminal - терминал в ST3 для использования консольных команд.
22 Hover Image Preview - при наведении на подлюченные медиафайлы к рабочему проекту появляется всплывашка с миниатюрой файла.
23 Gist — синхронизирует GitHub Gist с ST3, позволяет создавать Gists, поддтягивает из сервиса необходимые Gists для ускорения разрабоки проектов. Use Settings:
{	"token": "сгенерировать на GitHab"
}
24. GitGutter - для отслеживания изменения файлов при размещении проектов в репозитории GitHab. Use Settings:
{
  "debounce_delay": 100000,
}

User Settings ST3:

{
	"color_scheme": "Packages/Agila Theme/Agila Cobalt.tmTheme",
	"font_options":
	[
		"gray_antialias"
	],
	"font_size": 10,
	"highlight_line": true,
	"ignored_packages":
	[
		"Vintage"
	],
	"indent_guide_options":
	[
		"draw_normal",
		"draw_active"
	],
	"line_padding_bottom": 3,
	"line_padding_top": 3,
	"overlay_scroll_bars": "enabled",
	"save_on_focus_lost": true,
	"theme": "Agila Cobalt.sublime-theme",
	"theme_agila_active_tab_entry_yellow": true,
	"theme_agila_auto_complete_yellow": true,
	"theme_agila_compact_sidebar": true,
	"theme_agila_compact_tab": true,
	"theme_agila_horizontal_scrollbar_lightblue": true,
	"theme_agila_horizontal_scrollbar_thinner": true,
	"theme_agila_modified_tab_marker_yellow": true,
	"theme_agila_sidebar_font_small": true,
	"theme_agila_sidebar_heading_lightblue": true,
	"theme_agila_sidebar_light_icons": true,
	"theme_agila_sidebar_mini": true,
	"theme_agila_sidebar_selected_entry_lightblue": true,
	"theme_agila_vertical_scrollbar_lightblue": true,
	"theme_agila_vertical_scrollbar_thinner": true,
	"trim_automatic_white_space": true,
	"trim_trailing_white_space_on_save": true,
	"word_wrap": true
}