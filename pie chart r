data <- data.frame(
  category = c("Banana", "Milk", "Bread", "Diapers"),
  value = c(30, 20, 15, 35)
)

pie(data$value, labels = data$category, main = "Pie Chart")

library(ggplot2)

ggplot(data, aes(x = "", y = value, fill = category)) +
  geom_bar(stat = "identity", width = 1) +
  coord_polar("y", start = 0) +
  theme_void() +
  labs(title = "Pie Chart")
