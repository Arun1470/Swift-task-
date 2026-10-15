// Task 2.14: Sort students by marks descending and print the top 3.
let marks = [
    "Asha": 92,
    "Ravi": 76,
    "Meena": 88,
    "Kiran": 64,
    "Divya": 95
]

let ranking = marks.sorted {
    if $0.value == $1.value {
        return $0.key < $1.key
    }
    return $0.value > $1.value
}

print("Top 3 students:")
for (name, mark) in ranking.prefix(3) {
    print("\(name): \(mark)")
}
