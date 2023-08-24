library(rpart)
library(rpart.plot)

my_data <- data.frame(
  Age = c(25, 30, 22, 28, 35),
  Income = c(50000, 60000, 45000, 55000, 70000),
  Education = c("High School", "Bachelor", "High School", "Master", "PhD"),
  Loan_Approval = c("No", "Yes", "No", "Yes", "Yes")
)

X <- my_data[, c("Age", "Income", "Education")]
Y <- my_data$Loan_Approval

tree_model <- rpart(Loan_Approval ~ Age + Income + Education, data = my_data, method = "class")

rpart.plot(tree_model, box.palette = "blue", shadow.col = "gray", nn = TRUE)
