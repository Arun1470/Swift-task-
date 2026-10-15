// Task 2.13: Count word frequencies in a sentence.
let sentence = "to be or not to be"
let words = sentence.split(separator: " ").map(String.init)
var frequency: [String: Int] = [:]

for word in words {
    frequency[word, default: 0] += 1
}

for word in frequency.keys.sorted() {
    print("\(word): \(frequency[word]!)")
}
