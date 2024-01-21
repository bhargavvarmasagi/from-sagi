# Venkata Srinivasa Bhargav Varma Sagi
Atomic habits is my favorite book. It helps people to follow good habits and break bad ones. After reading this book, I started following some good habits. It was written by James Clear. It is a self-help book.

[Bhargav Image](./bhargav_mumbai.jpg)

---
## Suggestions
This table provides some suggestions regarding book/song/video.
| Name | Reason to like | Author/Writer/Singer |
| ------ | ------ | ------ |
| Atomic Habits | Inspiring | James Clear |
| Kun Faya Kun | Great Tune | A.R.Rahman |
| Nee Singam Dhan | Visuals | A.R.Rahman |
| Salaar Trailer | Prabhas | Prasanth Neel |
| Animal Trailer | Fights | Sandeep Reddy Vanga |

---
## Favorite Quotes
>"Picking one, teaches. Picking both, confuses."

>"The key to having more opportunities in life is to give yourself enough opportunities to get curious."

>"Listening to someone without judgement or prescription is the most precious gift you can give someone."

-- *Ankur Warikoo*

---
## Code Fencing
This is a singleton class strucuture to ensure only one instance of class is created. It can be used to update properties.
```
class SingletonClass {
  static final SingletonClass _instance = SingletonClass._internal();

  factory SingletonClass() {
    return _instance;
  }

  SingletonClass._internal();

  String property1 = 'Default Property 1';
  String property2 = 'Default Property 2';
}
/// Example consuming the singleton class and accessing/manipulating properties
/// To evaluate the difference between a normal class and a singleton class, comment
/// out the factory constructor and _instance in SingletonClass and re-run.
void main() {
  /// Properties before
  String property1Before = SingletonClass().property1;
  String property2Before = SingletonClass().property2;

  print('property1Before: $property1Before'); // Default Property 1
  print('property2Before: $property2Before'); // Default Property 2

  /// Updating the properties
  SingletonClass().property1 = 'Updated Property 1';
  SingletonClass().property2 = 'Updated Property 2';

  /// Properties after
  print('property1After: ${SingletonClass().property1}'); // Updated Property 1
  print('property2After: ${SingletonClass().property2}'); // Updated Property 2
}
```
Link to Snippet <https://code.pieces.app/collections/dart>


