install.packages("ggplot2")
library(ggplot2)

data <- data.frame(
  Group = rep(c("Group A", "Group B", "Group C"), each = 20),
  Value = c(rnorm(20, mean = 10, sd = 2),
            rnorm(20, mean = 15, sd = 3),
            rnorm(20, mean = 8, sd = 1.5))
)

ggplot(data, aes(x = Group, y = Value)) +
  geom_boxplot(fill = "lightblue", color = "blue") +
  labs(title = "Box Plot Example", x = "Group", y = "Value")
