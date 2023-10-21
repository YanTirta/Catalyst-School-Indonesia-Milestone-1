### Comparing Diamond Prices by Carat Across Different Cut Qualities {.tabset} 
#### Fair
ggplot(diamonds %>% filter(cut == 'Fair'), aes(x = carat)) +

  geom_point(aes(y = price, col = color)) +

  labs(x = '\nCarat',

       y = 'Price (USD $)\n',

       col = 'Color') +

  theme_bw()
