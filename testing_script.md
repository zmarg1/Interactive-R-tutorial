#Let's use another shopping list vector again
grocery_vector <- c(14, -5, 2, -12, 24, 100, 3, 400, 14, 14, 2, 20)

# Try out other functions like median(), min, max

unique(grocery_vector)

median(), min(), max(), sd(), sort(), sum(), unique()

#Run the following code
ggplot(gapminder_2007,mapping = aes(x=gdpPercap,y=lifeExp)) +
    scale_x_log2() +
    geom_point()+
    geom_smooth(method = lm)