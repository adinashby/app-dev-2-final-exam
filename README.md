# Application Development 2 - Final Exam

This template repository is the starter project for App. Dev. 2 Final Exam. Written in Flutter/Dart.

### Question(s)

1. You are given a restful API: https://jsonplaceholder.typicode.com/users

The sample data looks like the below:

```
 [
  {
    "id": 1,
    "name": "Leanne Graham",
    "username": "Bret",
    "email": "Sincere@april.biz",
    "address": {
      "street": "Kulas Light",
      "suite": "Apt. 556",
      "city": "Gwenborough",
      "zipcode": "92998-3874",
      "geo": {
        "lat": "-37.3159",
        "lng": "81.1496"
      }
    },
    "phone": "1-770-736-8031 x56442",
    "website": "hildegard.org",
    "company": {
      "name": "Romaguera-Crona",
      "catchPhrase": "Multi-layered client-server neural-net",
      "bs": "harness real-time e-markets"
    }
  },
  {
    "id": 2,
    "name": "Ervin Howell",
    "username": "Antonette",
    "email": "Shanna@melissa.tv",
    "address": {
      "street": "Victor Plains",
      "suite": "Suite 879",
      "city": "Wisokyburgh",
      "zipcode": "90566-7771",
      "geo": {
        "lat": "-43.9509",
        "lng": "-34.4618"
      }
    },
    "phone": "010-692-6593 x09125",
    "website": "anastasia.net",
    "company": {
      "name": "Deckow-Crist",
      "catchPhrase": "Proactive didactic contingency",
      "bs": "synergize scalable supply-chains"
    }
  },
]
```

Now, the task is to **use API calls to fetch the entire JSON data and display using ListView.** Each child item should contain a name, email id, phone number, address, and company details. The desired emulator output is given below. Though it displays for one user, you have to fetch all the users.

![](Q1_1.png)

For the second part, add a button to the main page, on top or the bottom of the page so that when you click on it, it will navigate to currency converter page. It should be able to convert currencies between USD, CAD, GBP. You can show the result as an alert or in a label. Use the rates below:

USD to CAD -> 1.35
CAD to USD -> 0.73

USD to GBP -> 0.79
GBP to USD -> 1.25

CAD to GBP -> 0.58
GBP to CAD -> 1.71

The page should look like below:

![](Q1_2.png)
