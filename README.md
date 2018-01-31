# gitlesson-biol812-week4
Learning github in class

## Let's make another header
Maybe this is where we'd say how to install our software

Maybe add a disclaimer that its a work in progress, etc.

```{r}
library(ggplot2)
library(abd)
ggplot(DEET, aes(x=dose,y=bites)) +
  geom_point() +
  geom_smooth(method=lm, se=FALSE, colour="black") +
 theme(panel.background = element_rect(fill="white"),
        panel.border = element_rect(colour = "black", fill=NA)) 
```
