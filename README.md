# Bootstrap-Navbar-1v
Learn how to make a responsive navbar using HTML CSS And Bootstrap 5 in a step-by-step tutorial for beginners.

To Do List:

1)Take - offcanvasnav

2)Delete - nav.bg-body-tertiary - add - navbar-expand-lg

3)Delete nav>form //видаляємо "пошук" з меню

4)Delete nav>li.dropdown //видаляємо випадаючий пункт меню

5)a{Link} rename a{About}

6)a{about} & a{Home} add .mx-lg-2

7)+a{Services Portfolio Contacts}

8)+nav>.container>a.login-button{Login} //додаємо кнопку "логін"

9)remove - nav>.container>button.navbar-toggler //переносимо бургер іконку з середини вкінець після "логін"

10)a.navbar-brand + .me-auto = a.navbar-brand.me-auto //чомусь прижимає "логін" до бургера, до цього були рівномірно по всій ширині

11).offcanvas-body>ul.navbar-nav.justify-content-end -> change to -> ul.navbar-nav.justify-content-center //меню переносимо на центр замість прижимання вкінець

12).offcanvas-header>h5.offcanvas-title{Offcanvas} -> h5.offcanvas-title{Logo} //перейменовуємо Offcanvas на Logo в випадаючому меню
offcanvasnav

13)+style.css

14).login-button{bcgc##009970+c#fff+fs14+p8-20} + {border-radius: 50px; tdn+transition-3-backgroundcolor} //стилі для "логін" і в наступному кроці для його ховеру

15).login-button:hover {bcgc#00b383}

16).navbar-toggler{ border: none; fs1.24r} //прибираємо обводку з бургер іконки та її ховеру і збільшуємо бургер іконку

17).navbar-toggler:hover {outline: none; box-shadow: none;}

18)inspect button.btn-close //в інспект знаходимо іконку закривання випадаючого меню

19).btn-close:focus {outline: none; box-shadow: none;}

20).nav-link {c#666777+fw500+position: relative;} //стилі для пунктів меню та при наведенні в наступному кроці

21).nav-link:hover, .active {c#000}

22)//стилізація ховеру пунктів меню.. там багато.. @media (min-width: 991px)..

23).navbar-brand {color: var(--brand)+fsz24+fw500+transition: 0.3s color;} //стилі для лого бренду

24)+section.hero-section //додаємо першу секцію і фон для неї

25).hero-section {background: url("./hero-bg.jpg") no-repeat center; + background-size: cover; +  w100%+h100vh}

26).hero-section::before {background-color: rgba(0, 0, 0, 0.6); + content: ""; + position: absolute; +t0+l0+r0+b0} //через псевдоелемент додаємо затемнення для фону секції

27).navbar {h80+m20+p.5r + border-radius: 16px;} //стилізація навігації

28)button.navbar-toggler + .pe-0 = button.navbar-toggler.pe-0 //видаляємо відступи у іконки меню

29)+section.hero-section //

30)div.container.d-flex.align-items-center.justify-content-center.fs-1.text-white.flex-column //

31).hero-section .container {h100hv+z1+psr} //

32).hero-title {fsz1.5r} + .hero-description {fsz1.3r}

33)nav>.container-fluid -> nav>.container

34)//додав відео-кнопку
