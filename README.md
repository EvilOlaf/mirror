<h3 align=center><a href="#build-tools"><img src="https://raw.githubusercontent.com/armbian/build/master/.github/armbian-logo.png" alt="Armbian logo" width="144"></a><br>mirror sync</h3>
<p align=right>&nbsp;</p>

## Mirroring Armbian?

We are providing rsync service for stable images (dl), repository (apt), beta (beta) and archive (archive) at:

    rsync -av rsync://rsync.armbian.com/

Alternatively you can sync most valuable date from one of our mirror that provides rsync and is much faster: 

    rsync -av rsync://mirrors.dotsrc.org/armbian-dl
    rsync -av rsync://mirrors.dotsrc.org/armbian-apt

Space needs: 500Gb (images), 100Gb (packages) and (optional) 3TB for archives

1. Setup HTTP and HTTPS hostname
2. Setup cron to sync every 2-4 hours
3. [Inform us](https://www.armbian.com/#contact)


## Images (dl.armbian.com)

|URL &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  |City &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |Flag|Country|
|:--|:--|:--:|--:|
|http://armbian.chi.auroradev.org/dl/|West Chicago|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://armbian.hosthatch.com/dl/||<img width=24 src=>||
|http://armbian.lv.auroradev.org/dl/|Las Vegas|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://armbian.site-meganet.com/dl/|Roubaix|<img width=24 src=https://cdn.ipwhois.io/flags/fr.svg>|France|
|http://armbian.systemonachip.net/dl/|Vienna|<img width=24 src=https://cdn.ipwhois.io/flags/at.svg>|Austria|
|http://au.sbcmirror.org/armbian/dl/|Sydney|<img width=24 src=https://cdn.ipwhois.io/flags/au.svg>|Australia|
|http://fastmirror.pp.ua/armbian-dl/|Kyiv|<img width=24 src=https://cdn.ipwhois.io/flags/ua.svg>|Ukraine|
|http://fi.mirror.armbian.de/dl/|Helsinki|<img width=24 src=https://cdn.ipwhois.io/flags/fi.svg>|Finland|
|http://imola.armbian.com/dl/|Ljubljana|<img width=24 src=https://cdn.ipwhois.io/flags/si.svg>|Slovenia|
|http://k-space.ee.armbian.com/dl/|Tallinn|<img width=24 src=https://cdn.ipwhois.io/flags/ee.svg>|Estonia|
|http://mirror-eu-de1.armbian.airframes.io/dl/|Nuremberg|<img width=24 src=https://cdn.ipwhois.io/flags/de.svg>|Germany|
|http://mirror-us-stl1.armbian.airframes.io/dl/|St. Louis|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://mirror.vinehost.net/armbian/dl/|Olney|<img width=24 src=https://cdn.ipwhois.io/flags/gb.svg>|United Kingdom|
|http://mirror.yandex.ru/mirrors/armbian/dl/|Moscow|<img width=24 src=https://cdn.ipwhois.io/flags/ru.svg>|Russia|
|http://mirrors.dotsrc.org/armbian-dl/|Copenhagen|<img width=24 src=https://cdn.ipwhois.io/flags/dk.svg>|Denmark|
|http://mirrors.jevincanders.net/armbian/dl/|West Seneca|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://mirrors.netix.net/armbian/dl/|Sofia|<img width=24 src=https://cdn.ipwhois.io/flags/bg.svg>|Bulgaria|
|http://sg.sbcmirror.org/armbian/dl/|Singapore|<img width=24 src=https://cdn.ipwhois.io/flags/sg.svg>|Singapore|
|http://stpete-mirror.armbian.com/dl/|Saint Petersburg|<img width=24 src=https://cdn.ipwhois.io/flags/ru.svg>|Russia|
|http://xogium.performanceservers.nl/dl/|Amsterdam|<img width=24 src=https://cdn.ipwhois.io/flags/nl.svg>|Netherlands|


## Packages (apt.armbian.com)

|URL &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  |City &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |Flag|Country|
|:--|:--|:--:|--:|
|http://armbian.site-meganet.com/apt/|Roubaix|<img width=24 src=https://cdn.ipwhois.io/flags/fr.svg>|France|
|http://au.sbcmirror.org/armbian/apt/|Sydney|<img width=24 src=https://cdn.ipwhois.io/flags/au.svg>|Australia|
|http://fi.mirror.armbian.de/apt/|Helsinki|<img width=24 src=https://cdn.ipwhois.io/flags/fi.svg>|Finland|
|http://imola.armbian.com/apt/|Ljubljana|<img width=24 src=https://cdn.ipwhois.io/flags/si.svg>|Slovenia|
|http://k-space.ee.armbian.com/apt/|Tallinn|<img width=24 src=https://cdn.ipwhois.io/flags/ee.svg>|Estonia|
|http://mirror-eu-de1.armbian.airframes.io/apt/|Nuremberg|<img width=24 src=https://cdn.ipwhois.io/flags/de.svg>|Germany|
|http://mirror-us-stl1.armbian.airframes.io/apt/|St. Louis|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://mirror.iscas.ac.cn/armbian/|Haidian|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirror.sjtu.edu.cn/armbian/|Shanghai|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirror.vinehost.net/armbian/apt/|Olney|<img width=24 src=https://cdn.ipwhois.io/flags/gb.svg>|United Kingdom|
|http://mirrors.bfsu.edu.cn/armbian/|Xicheng|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.dotsrc.org/armbian-apt/|Copenhagen|<img width=24 src=https://cdn.ipwhois.io/flags/dk.svg>|Denmark|
|http://mirrors.jevincanders.net/armbian/apt/|West Seneca|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://mirrors.netix.net/armbian/apt/|Sofia|<img width=24 src=https://cdn.ipwhois.io/flags/bg.svg>|Bulgaria|
|http://mirrors.tuna.tsinghua.edu.cn/armbian/|Haidian|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.ustc.edu.cn/armbian/|Hefei|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://sg.sbcmirror.org/armbian/apt/|Singapore|<img width=24 src=https://cdn.ipwhois.io/flags/sg.svg>|Singapore|
|http://stpete-mirror.armbian.com/apt/|Saint Petersburg|<img width=24 src=https://cdn.ipwhois.io/flags/ru.svg>|Russia|


## Archive (archive.armbian.com)

|URL &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  |City &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |Flag|Country|
|:--|:--|:--:|--:|
|http://armbian.hosthatch.com/archive/|Amsterdam|<img width=24 src=https://cdn.ipwhois.io/flags/nl.svg>|Netherlands|
|http://armbian.lv.auroradev.org/archive/|Las Vegas|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://armbian.systemonachip.net/archive/|Vienna|<img width=24 src=https://cdn.ipwhois.io/flags/at.svg>|Austria|
|http://armbian.tnahosting.net/archive/|Chicago|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://fi.mirror.armbian.de/archive/|Helsinki|<img width=24 src=https://cdn.ipwhois.io/flags/fi.svg>|Finland|
|http://imola.armbian.com/archive/|Ljubljana|<img width=24 src=https://cdn.ipwhois.io/flags/si.svg>|Slovenia|
|http://k-space.ee.armbian.com/archive/|Tallinn|<img width=24 src=https://cdn.ipwhois.io/flags/ee.svg>|Estonia|
|http://mirror.yandex.ru/mirrors/armbian/archive/|Moscow|<img width=24 src=https://cdn.ipwhois.io/flags/ru.svg>|Russia|
|http://stpete-mirror.armbian.com/archive/|Saint Petersburg|<img width=24 src=https://cdn.ipwhois.io/flags/ru.svg>|Russia|
|http://xogium.performanceservers.nl/archive/|Amsterdam|<img width=24 src=https://cdn.ipwhois.io/flags/nl.svg>|Netherlands|


## Beta (beta.armbian.com)

|URL &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  |City &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |Flag|Country|
|:--|:--|:--:|--:|
|https://armbian.site-meganet.com/beta/|Roubaix|<img width=24 src=https://cdn.ipwhois.io/flags/fr.svg>|France|
|https://fi.mirror.armbian.de/beta/|Helsinki|<img width=24 src=https://cdn.ipwhois.io/flags/fi.svg>|Finland|
|https://hetzner-mirror.armbian.com/beta/|Falkenstein|<img width=24 src=https://cdn.ipwhois.io/flags/de.svg>|Germany|
|https://k-space.ee.armbian.com/beta/|Tallinn|<img width=24 src=https://cdn.ipwhois.io/flags/ee.svg>|Estonia|
|https://mirror.dogmantech.com/beta/|Grand Rapids|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|https://stpete-mirror.armbian.com/beta/|Saint Petersburg|<img width=24 src=https://cdn.ipwhois.io/flags/ru.svg>|Russia|


## Cache (cache.armbian.com)

|URL &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  |City &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |Flag|Country|
|:--|:--|:--:|--:|
|https://armbian.tnahosting.net/cache/|Chicago|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|https://fi.mirror.armbian.de/cache/|Helsinki|<img width=24 src=https://cdn.ipwhois.io/flags/fi.svg>|Finland|
|https://mirror-eu-de1.armbian.airframes.io/cache/|Nuremberg|<img width=24 src=https://cdn.ipwhois.io/flags/de.svg>|Germany|
|https://mirror-us-phx1.armbian.airframes.io/cache/|Phoenix|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|https://mirror-us-sea1.armbian.airframes.io/cache/|Seattle|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|https://mirror-us-sea2.armbian.airframes.io/cache/|Seattle|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|https://mirror-us-stl1.armbian.airframes.io/cache/|St. Louis|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|https://mirrors.aliyun.com/armbian-cache/|Hangzhou|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|https://stpete-mirror.armbian.com/cache/|Saint Petersburg|<img width=24 src=https://cdn.ipwhois.io/flags/ru.svg>|Russia|

