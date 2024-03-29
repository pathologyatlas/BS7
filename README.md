







```
r language BS7, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis nekrotizan sialometaplazi, SCC sonrası radyoterapi , echo = (language == "TR")
## BS7 - nekrotizan sialometaplazi, SCC sonrası radyoterapi {#sec-BS7 }
```


```
asis necrotising sialometaplasia, radiotherapy after SCC , echo = (language == "EN")
## BS7 - necrotising sialometaplasia, radiotherapy after SCC {#sec-BS7 }
```






```
r BS7 screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS7-HE_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS7/HE.html",
  file = "./screenshots/BS7-HE_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link







```
asis, echo = (language == "TR")

**nekrotizan sialometaplazi, SCC sonrası radyoterapi**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS7-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS7/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS7/HE.html)
```

```
asis, echo = (language == "EN")

**necrotising sialometaplasia, radiotherapy after SCC**

[![Click for Full Screen WSI](./screenshots/BS7-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS7/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS7/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS7/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS7/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```






:::::
