install.packages("corrplot")
library(corrplot)

data <- data.frame(
  Age = c(25, 30, 22, 28, 35),
  Income = c(50000, 60000, 45000, 55000, 70000),
  Score = c(85, 90, 70, 80, 95)
)

correlation_matrix <- cor(data)

print(correlation_matrix)

corrplot(correlation_matrix, method = "color")
