<h2><img src="https://emojis.slackmojis.com/emojis/images/1698659368/72825/pepe-wave.gif?1698659368" width="40"/> Waddup! Im Rom!</h2>
<img align='right' src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNGMzeWoxdjYwenp0bGNqaDhxdDlmaGdkODYwM2dydmxkY3lvZjFjZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/du3J3cXyzhj75IOgvA/giphy.gif" width="230">

```swift
class RomTheSheep: IosDeveloper, Spaniard, Italian, Maker, Moder, GraphicDesigner {

  init() {
    name: String = "Rom the sheep"
    guard let actualYear = Calendar.current.dateComponents([.year], from: Date()).year else {
      return
    }
    age: Int = actualYear - 1996
    interests: [Hobby] = [
      .videogame,
      .books,
      .manga,
      .anime,
      .coding // duh
    ]
    languages: [Language] = [
      .swift,
      .javascript,
      .python,
      .java,
      .kotlin,
      .typescript,
      .html,
      .angular,
      .sass
    ]
    languageSpoken: [String] = ['es_SP', 'en_UK', 'it_IT']
    misc: [String] = [
      "Firebase",
      "web scrapping",
      "Data analysis with pandas/scipy",
      ""
    ]
  }

  func sayHi(guest: String) {
    print("Hi! wellcome to my humble github! make yourself confortable")
  }
}
```
