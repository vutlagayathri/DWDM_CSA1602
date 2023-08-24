library(randomForest)
data(iris)

set.seed(123) 
train_indices <- sample(1:nrow(iris), 0.7*nrow(iris)) # 70% for training
train_data <- iris[train_indices, ]
test_data <- iris[-train_indices, ]

rf_model <- randomForest(Species ~ ., data = train_data)

predictions <- predict(rf_model, test_data)

confusion_matrix <- table(predictions, test_data$Species)
print(confusion_matrix)

accuracy <- sum(diag(confusion_matrix)) / sum(confusion_matrix)
cat("Accuracy:", accuracy)
