// Task 2.17: Group names by their first letter.
let names = ["Asha", "Arun", "Bala", "Bhuvana", "Kiran", "Kavya"]
var groupedNames: [Character: [String]] = [:]

for name in names {
    guard let firstLetter = name.first else { continue }
    groupedNames[firstLetter, default: []].append(name)
}

for letter in groupedNames.keys.sorted() {
    print("\(letter): \(groupedNames[letter]!.sorted())")
}
