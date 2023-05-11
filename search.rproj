library(gtrendsR)
library(ggplot2)

trends <- gtrends("noticias",geo="CL",time="today 1-m")

ggplot(data = trends$interest_over_time, aes(x = date, y = hits)) +
  geom_bar(stat="identity", fill="#008fd5") +
  labs(title = "Búsquedas más frecuentes en Chile", x = "Fecha", y = "Volumen de búsquedas")
  
  

