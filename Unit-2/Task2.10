// Task 2.10: Remove duplicates while keeping original order.
let numbers = [3, 1, 3, 2, 1, 4, 2]
var uniqueNumbers: [Int] = []
var seen = Set<Int>()

for number in numbers {
    if !seen.contains(number) {
        seen.insert(number)
        uniqueNumbers.append(number)
    }
}

print("Original:", numbers)
print("Without duplicates:", uniqueNumbers)
