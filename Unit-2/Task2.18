// Task 2.18: Shopping cart using a price dictionary and an array of bought items.
let prices: [String: Double] = [
    "Notebook": 50.0,
    "Pen": 10.0,
    "Bag": 750.0,
    "Bottle": 120.0
]
let itemsBought = ["Notebook", "Pen", "Pen", "Bottle"]
var total = 0.0

for item in itemsBought {
    if let price = prices[item] {
        total += price
        print("\(item): ₹\(String(format: "%.2f", price))")
    } else {
        print("Price not found for \(item)")
    }
}

print("Total bill: ₹\(String(format: "%.2f", total))")
