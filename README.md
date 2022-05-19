# Тестовое задание в контексте вакансии программист-прикладной математик

Горизонтальный пористый пласт постоянного сечения длиной <img src="https://render.githubusercontent.com/render/math?math=10"> метров в начальный момент времени полностью насыщен произвольной несжимаемой жидкостью. Все грани пласта кроме правой и левой непроницаемы для жидкости. Через правую границу пласта <img src="https://render.githubusercontent.com/render/math?math=10"> метров противоположно оси <img src="https://render.githubusercontent.com/render/math?math=x"> начинает закачиваться другая несжимаемая жидкость (вода), несмешивающаяся с жидкостью исходно насыщающей пласт, таким образом, что величина водонасыщенности <img src="https://render.githubusercontent.com/render/math?math=S">  (т.е. доля объема пор, занимаемых водой) на правой границе пласта в момент времени <img src="https://render.githubusercontent.com/render/math?math=t=0"> мгновенно увеличивается до <img src="https://render.githubusercontent.com/render/math?math=S=1"> и в дальнейшем поддерживается постоянной. Через левую границу пласта <img src="https://render.githubusercontent.com/render/math?math=x=0"> жидкость свободно вытесняется влево.

Определить, как зависит  <img src="https://render.githubusercontent.com/render/math?math=S"> до левой границы пласта в момент времени <img src="https://render.githubusercontent.com/render/math?math=t=4"> часа, если зависимость скорости фильтрации  исходно насыщающей пласт жидкости (<img src="https://render.githubusercontent.com/render/math?math=i=1">) и закачиваемой жидкости (<img src="https://render.githubusercontent.com/render/math?math=i=2">) от давления <img src="https://render.githubusercontent.com/render/math?math=p"> описывается линейным законом фильтрации: (<img src="https://render.githubusercontent.com/render/math?math=u_i=-{\frac{k_i}{\mu_i}}{\nabla} p" />), где <img src="https://render.githubusercontent.com/render/math?math=m=0.3" /> — коэффициент пористости, и  – коэффициенты относительной фазовой проницаемости и динамической вязкости соответственно. Принять, что отношение коэффициентов <img src="https://render.githubusercontent.com/render/math?math=k_1/k_2" /> равно отношению насыщенностей жидкостей, а динамическая вязкость для исходно насыщающей пласт жидкости в два раза больше, чем для закачиваемой жидкости. Суммарная скорость фильтрации двух жидкостей <img src="https://render.githubusercontent.com/render/math?math=u_1%2bu_2" /> постоянна и равна <img src="https://render.githubusercontent.com/render/math?math={0.1 \space \text{мм}/\text{с}}" />. Принять, что при совместном течении в пористом пласте нескольких несмешивающихся и несжимаемых жидкостей величина насыщенности <img src="https://render.githubusercontent.com/render/math?math=S_i" /> для каждой жидкости связана со скоростью фильтрации следующим соотношением: <img src="https://render.githubusercontent.com/render/math?math=m \frac{\partial S_i}{\partial t} = - \text{div} \space u_i" />. Результат необходимо представить в виде отчета, включающего как запись исходной математической постановки выше сформулированной задачи в форме начально-краевой задачи для системы дифференциальных уравнений, так и выкладки, описывающие процесс сведения решения данной системы дифференциальных уравнений к одному (итоговому) обыкновенному дифференциальному уравнению. Отчет должен быть представлен в одном из форматов: электронный файл формата doc/docx/pdf, содержащий скан-копии (фотографии) ответа (рукописей).

Итоговое обыкновенное дифференциальное уравнение допускается решать как аналитическими, так и численными методами.

Необходимо написать вычислительную программу для нахождения величины водонасыщенности <img src="https://render.githubusercontent.com/render/math?math=S" /> в сечении, отстоящем на расстоянии <img src="https://render.githubusercontent.com/render/math?math=x" /> от левой грани пласта, где <img src="https://render.githubusercontent.com/render/math?math=0<x<10" /> метров. Программа должна реализовывать метод Ньютона для решения системы нелинейных алгебраических уравнений.
