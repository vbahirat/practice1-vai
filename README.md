# practice1-vai
I am Vai.
I am a continous improving engineer
I am the President of the Indian Students' Association
I use a schedule planner to plan my work


Hello, I am Michael.
This is my code in case you need it: 

```{r}
data <- read.csv("gapminder-5060.csv")
data<-data[(data$country=="United States"),]
ggplot(data = data, aes(x = lifeExp, y = gdpPercap)) +
  geom_point()
```
