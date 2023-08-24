data <- data.frame(
  Age = c(25, 30, 22, 35, 40),
  Income = c(50000, 75000, 60000, 90000, 120000)
)

decimal_scaling <- function(data) {
  scaled_data <- data / 10 ^ (ceiling(log10(max(data))))
  return(scaled_data)
}

scaled_data <- decimal_scaling(data)

print("Original Data:")
print(data)

print("Scaled Data:")
print(scaled_data)
