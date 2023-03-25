1. Просмотрите историю коммитов в своём проекте и выберите три случайных коммита. Просмотрите изменения, которые были в них сделаны.


>![скрин 2](ScreenShorts/Screenshot_2.png)
>![скрин 6](ScreenShorts/Screenshot_6.png)
>![скрин 7](ScreenShorts/Screenshot_7.png)
>![скрин 8](ScreenShorts/Screenshot_8.png)




<br>
<br>
2. Верните эти изменения командой git revert последовательно, чтобы в итоге получилось тоже три коммита.
<br>
<br>

>![скрин 3](ScreenShorts/Screenshot_3.png)
>![скрин 4](ScreenShorts/Screenshot_4.png)
>![скрин 5](ScreenShorts/Screenshot_5.png)
> git log --oneline - (отобразятся эти 3 комита) - скрин забыл прикрепить

<br>
<br>
3. Попробуйте отменить эти три коммита:  

* последний — командами git reset --soft и git restore;
<br>
<br>

>![скрин 9](ScreenShorts/Screenshot_9.png)
>![скрин 10](ScreenShorts/Screenshot_10.png)
>![скрин 11](ScreenShorts/Screenshot_12.png)
>![скрин 13](ScreenShorts/Screenshot_13.png)

<br>


* предпоследний — командой git reset --mixed и git restore;
<br>
<br>

>![скрин 14](ScreenShorts/Screenshot_14.png)
>![скрин 15](ScreenShorts/Screenshot_15.png)
>![скрин 16](ScreenShorts/Screenshot_16.png)
>![скрин 17](ScreenShorts/Screenshot_17.png)

* первый — командой git reset --hard.
<br>
<br>

>![скрин 18](ScreenShorts/Screenshot_18.png)

