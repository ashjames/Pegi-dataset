# PEGI Game Ratings Dataset 

## 1999 to 2018-02-04

Dataset contains `28,757` rows of [PEGI](http://www.pegi.info/) game ratings from  from 1999 to February 04, 2018.

Example data:

```json
[
    {
        "Release-date": "2018-02-02",
        "Rating": "18",
        "Title": "Mafia III The Complete Edition",
        "URL": null,
        "Company": "Take2 Interactive Software Europe ltd",
        "Contains": [
            "Game contains bad language",
            "Game refers to or depicts the use of drugs",
            "Game depicts nudity and/or sexual behaviour or sexual references",
            "Game contains depictions of violence"
        ],
        "Platform": "PC",
        "Genre": "Action"
    }
]   
```

## 1999 to 2019-01-12

Dataset contains `30,183` rows.

Update: Website recently changed. `Genre` has been removed from the website listings.

Example data:

```json
[
    {
        "Title": "Borderlands 2 VR",
        "Title Description": "Borderlands 2 VR is a port of the much-acclaimed first-person shooter Borderlands 2 into a single-player VR experience. Players will fight off bandits in immersive gunfights with real-world aiming, punch...",
        "Descriptor Image URL": [
            "https://pegi.info/themes/pegi/public-images/violence.png",
            "https://pegi.info/themes/pegi/public-images/bad_language.png"
        ],
        "Rating": 18,
        "Rating Image URL": "https://pegi.info/themes/pegi/public-images/pegi/pegi18.png",
        "Platform": [
            "PlayStation 4"
        ],
        "Release Date": "2018-12-14 00:00:00",
        "Publisher": "Take2 Interactive Software Europe ltd",
        "Publisher URL": null,
        "Consumer Advice": "This game is rated PEGI 18 which restricts availability to ADULTS ONLY and is not suitable for anyone below this age. This rating has been given due to gross violence towards human characters and the use of sexual expletives.",
        "Descriptor": [
            "Bad language",
            "Violence"
        ]
    }
]
```