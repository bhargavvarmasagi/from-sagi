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

---
## Favorite Quotes
>"Picking one, teaches. Picking both, confuses."

>"The key to having more opportunities in life is to give yourself enough opportunities to get curious."

>"Listening to someone without judgement or prescription is the most precious gift you can give someone."

-- *Ankur Warikoo*

---
## Code Fencing
To guarantee that only one instance of a class is created, establish a singleton class structure in Dart. This can be used for state management, performance optimization, and property updates.
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
Link to Snippet <https://shared.code.pieces.app/?compressed=eyJiYXNlIjoiaHR0cHM6Ly9kYXJ0LnBpZWNlcy5jbG91ZCIsInNoYXJlIjoiZGM4MWMxYzEtNmFhZS00MDRkLTg4NjAtNWJkMTliMDNlYWQ0IiwiYXNzZXQiOiI0N2UwY2VkNi1iMjNkLTRmMDAtYWVmNS0wOGZlOWQ0N2JjNTUiLCJuYW1lIjoiUGllY2VzIFRlYW0iLCJ0aXRsZSI6IlNpbmdsZXRvbiIsImRlc2NyaXB0aW9uIjoiQ3JlYXRlcyBzaW5nbGV0b24gY2xhc3Mgc3RydWN0dXJlIGluIERhcnQgdG8gZW5zdXJlIG9ubHkgb25lIGluc3RhbmNlIG9mIGEgY2xhc3MgaXMgY3JlYXRlZC4gVGhpcyBjYW4gYmUgdXNlZCB0byB1cGRhdGUgcHJvcGVydGllcywgZW5oYW5jZSBwZXJmb3JtYW5jZSwgYW5kIG1hbmFnZSBzdGF0ZSBGcm9tIFRoZSBQaWVjZXMgRGFydCBDb2xsZWN0aW9uLiIsInVzZXIiOnsic2NoZW1hIjp7Im1pZ3JhdGlvbiI6MCwic2VtYW50aWMiOiJNQUpPUl8wX01JTk9SXzBfUEFUQ0hfMSJ9LCJwaWN0dXJlIjoiaHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2laVlNGZW1sS2lkcTVKclJSZVllUGkyckZHRG9aZXhWYW9TbDRvPXM5Ni1jIiwiZW1haWwiOiJkYXJ0LmNvbGxlY3Rpb25AcGllY2VzLmFwcCIsImNyZWF0ZWQiOnsidmFsdWUiOiIyMDIyLTA2LTIzVDE3OjI3OjIzLjk5MloiLCJyZWFkYWJsZSI6ImFib3V0IGEgeWVhciBhZ28ifSwidXBkYXRlZCI6eyJ2YWx1ZSI6IjIwMjItMDYtMjNUMTc6Mjc6MjQuNzgwWiIsInJlYWRhYmxlIjoiYWJvdXQgYSB5ZWFyIGFnbyJ9LCJpZCI6Ijg4NzAyZGEzLTY2MTAtNDBjYi1iZWJkLTM4MGQ4MmFjNmUzNCIsIm5hbWUiOiJQaWVjZXMgVGVhbSIsImFlc3RoZXRpY3MiOnsidGhlbWUiOnsiZGFyayI6dHJ1ZX0sImZvbnQiOnsic2l6ZSI6MTZ9fSwiYWxsb2NhdGlvbiI6eyJzY2hlbWEiOnsibWlncmF0aW9uIjowLCJzZW1hbnRpYyI6Ik1BSk9SXzBfTUlOT1JfMF9QQVRDSF8xIn0sImlkIjoiODg3MDJkYTMtNjYxMC00MGNiLWJlYmQtMzgwZDgyYWM2ZTM0IiwidXNlciI6Ijg4NzAyZGEzLTY2MTAtNDBjYi1iZWJkLTM4MGQ4MmFjNmUzNCIsInVybHMiOnsiYmFzZSI6eyJzdGF0dXMiOiJSVU5OSU5HIiwidXJsIjoiaHR0cHM6Ly91c2VyLTg4NzAyZGEzLTY2MTAtNDBjYi1iZWJkLTM4MGQ4MmFjNmUzNC1maGNtYmhla2xxLXVjLmEucnVuLmFwcCJ9LCJpZCI6eyJzdGF0dXMiOiJSVU5OSU5HIiwidXJsIjoiaHR0cHM6Ly84ODcwMmRhMy02NjEwLTQwY2ItYmViZC0zODBkODJhYzZlMzQucGllY2VzLmNsb3VkIn0sInZhbml0eSI6eyJzdGF0dXMiOiJSVU5OSU5HIiwidXJsIjoiaHR0cHM6Ly9kYXJ0LnBpZWNlcy5jbG91ZCJ9fSwic3RhdHVzIjp7ImNsb3VkIjoiUlVOTklORyJ9LCJwcm9qZWN0IjoicnVudGltZS11c2VyLWNsb3VkLWdyb3VwLTAiLCJ1cGRhdGVkIjp7InZhbHVlIjoiMjAyMi0wNi0yM1QxNzoyNzo1MS4yMTE1MzZaIiwicmVhZGFibGUiOiJhYm91dCBhIHllYXIgYWdvIn0sInZlcnNpb24iOiIzLjEuMCJ9fX0=&user=88702da3-6610-40cb-bebd-380d82ac6e34>


