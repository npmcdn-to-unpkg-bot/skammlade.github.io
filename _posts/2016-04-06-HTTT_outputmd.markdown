---
layout: post
title: "Horsetooth Time Trial Series output md_doc.markdown"
date: 2016-5-31 
categories: cycling
---
![HTdams](https://raw.githubusercontent.com/skammlade/skammlade.github.io/master/images/dams_handlebar.jpg)
<br> 
<br> 
<br> 
Fort Collins, CO is home to a thriving grassroots racing scene. Your Group Ride hosts an annual time trial every Tuesday in April known as the [Horsetooth Time Trial Series](http://yourgroupride.com/index.php/local-races/horsetooth-time-trial-series). The hilly **14.35 mile** course runs along Horsetooth Reservoire and
Horsetooth Mountain Park climbing a total of **1,336 feet**. 
<br> 
<br>
<br>
<iframe style="width:100%;height:600px;" src="https://veloviewer.com/segments/1213731/embed2" frameborder="0" scrolling="no"></iframe>  
<br> 
<br> 
<br> 
I wanted to see how the racer turnout compared between men versus women so I plotted race data from 2011-2015. Last year had the greatest turnout for female cyclsts so far with **34 racers** representing **21.25%** of total racers.

![plot](https://raw.githubusercontent.com/skammlade/skammlade.github.io/master/images/plot.yeargender.jpg)
<br> 
    I pulled some temperature data from [WeatherUnderground](https://www.wunderground.com/cgi-bin/findweather/getForecast?query=pws:KCOFORTC71) for each date during the race time to see if that would explain the low attendance in 2013.
<br> 
<br>
<br>
<img align="left" src="https://raw.githubusercontent.com/skammlade/skammlade.github.io/master/images/plot.weather.jpg">
<br>

#### Top 5 times from each category to date:

##### Female Aero

    ##              Date  LName  FName     Time
    ## 381 07 April 2015 Callan Nicole 00:44:26
    ## 403 10 April 2012 Hassel  Diana 00:44:51
    ## 414   01 May 2012 Hassel  Diana 00:44:58
    ## 423 10 April 2012 Callan Nicole 00:45:08
    ## 441 17 April 2012 Callan Nicole 00:45:33

##### Female Eddy

    ##              Date         LName    FName     Time
    ## 439 10 April 2012   Archambault     Ilka 00:45:31
    ## 443 30 April 2013       Powelka    Jenny 00:45:36
    ## 474 28 April 2015      Kammlade     Sara 00:46:03
    ## 483 07 April 2015        Oleksy Isabella 00:46:12
    ## 515 07 April 2015 Witinok-huber  Rebecca 00:46:53

##### Female Kerkove

    ##              Date             LName  FName     Time
    ## 779 28 April 2015          Arbesman Kendra 00:56:08
    ## 793   16 May 2013              Swan Nicole 00:59:16
    ## 809 28 April 2015 Ledesma-Feliciano Carmen 01:13:01

##### Male Aero

    ##             Date   LName  FName     Time
    ## 77 17 April 2012 Agofast   Ivan 00:34:00
    ## 78 17 April 2012  Wilson Nathan 00:34:26
    ## 81 10 April 2012  Connor Trevor 00:36:24
    ## 83 17 April 2012  Tuttle     Ty 00:36:50
    ## 84 24 April 2012    Holt    Ian 00:37:02

##### Male Eddy

    ##              Date  LName   FName     Time
    ## 93  14 April 2015 Kacher    Nick 00:37:42
    ## 99  07 April 2015 Durrer  walter 00:38:13
    ## 101 15 April 2014 Weiler   Steve 00:38:17
    ## 104 10 April 2012   Jake  Keyser 00:38:22
    ## 106 14 April 2015    Fix Brannan 00:38:24

##### Male Kerkove

    ##              Date  LName  FName     Time
    ## 277 30 April 2013 Stefko Steven 00:42:32
    ## 284 28 April 2015 Stefko Steven 00:42:41
    ## 286 14 April 2015 Stefko Steven 00:42:42
    ## 315 25 April 2013 Stefko Steven 00:43:10
    ## 324   09 May 2013 Stefko Steven 00:43:18

You can play around with the [racedata](https://github.com/skammlade/projects/blob/master/HTTT/HTTT.csv)
yourself (pulled from [YGR googledocs](https://docs.google.com/spreadsheets/d/1dNnqC5YTzURecVyo8U4a_RAv-KwQoJtCwnjseIOjg1g/edit?pref=2&pli=1#gid=234516618)).
\*Note: the 2011 course differs from the 2012-2015 course and therefore
times were omitted.
