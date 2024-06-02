## The dataset:
```js

  games = [
    {
      "title": "The Legend of Zelda: Breath of the Wild 2",
      "publisher": "Nintendo",
      "release_date": "2022",
      "platform": ["Nintendo Switch"],
      "size_gb": 15.6
    },
    {
      "title": "Cyberpunk 2077",
      "publisher": "CD Projekt",
      "release_date": "2020",
      "platform": ["PC", "PS4", "Xbox One"],
      "size_gb": 70.2
    },
    {
      "title": "Red Dead Redemption 2",
      "publisher": "Rockstar Games",
      "release_date": "2018",
      "platform": ["PC", "PS4", "Xbox One"],
      "size_gb": 99.4
    },
    {
      "title": "The Witcher 3: Wild Hunt",
      "publisher": "CD Projekt",
      "release_date": "2015",
      "platform": ["PC", "PS4", "Xbox One"],
      "size_gb": 42.5
    },
    {
      "title": "Grand Theft Auto V",
      "publisher": "Rockstar Games",
      "release_date": "2013",
      "platform": ["PC", "PS4", "Xbox One"],
      "size_gb": 86.3
    },
    {
      "title": "God of War (2018)",
      "publisher": "Sony Interactive Entertainment",
      "release_date": "2018",
      "platform": ["PS4"],
      "size_gb": 44.0
    },
    {
      "title": "Halo Infinite",
      "publisher": "Xbox Game Studios",
      "release_date": "2021",
      "platform": ["Xbox Series X/S", "PC"],
      "size_gb": 64.8
    },
    {
      "title": "Call of Duty: Warzone",
      "publisher": "Activision",
      "release_date": "2020",
      "platform": ["PC", "PS4", "Xbox One"],
      "size_gb": 130.7
    },
    {
      "title": "Assassin's Creed Valhalla",
      "publisher": "Ubisoft",
      "release_date": "2020",
      "platform": ["PC", "PS4", "Xbox One", "PS5", "Xbox Series X/S"],
      "size_gb": 71.2
    },
    {
      "title": "Final Fantasy VII Remake",
      "publisher": "Square Enix",
      "release_date": "2020",
      "platform": ["PS4", "PS5"],
      "size_gb": 85.3
    },
    {
      "title": "Marvel's Spider-Man: Miles Morales",
      "publisher": "Sony Interactive Entertainment",
      "release_date": "2020",
      "platform": ["PS4", "PS5"],
      "size_gb": 50.1
    },
    {
      "title": "Death Stranding",
      "publisher": "Sony Interactive Entertainment (PS4), 505 Games (PC)",
      "release_date": "2019 (PS4), 2020 (PC)",
      "platform": ["PS4", "PC"],
      "size_gb": 61.8
    },
    {
      "title": "Gears 5",
      "publisher": "Xbox Game Studios",
      "release_date": "2019",
      "platform": ["Xbox One", "PC"],
      "size_gb": 71.5
    },
    {
      "title": "DOOM Eternal",
      "publisher": "Bethesda Softworks",
      "release_date": "2020",
      "platform": ["PC", "PS4", "Xbox One", "Nintendo Switch"],
      "size_gb": 61.0
    },
    {
      "title": "Fortnite",
      "publisher": "Epic Games",
      "release_date": "2017",
      "platform": ["PC", "PS4", "Xbox One", "Nintendo Switch", "iOS", "Android"],
      "size_gb": 40.9
    },
    {
      "title": "Overwatch",
      "publisher": "Blizzard Entertainment",
      "release_date": "2016",
      "platform": ["PC", "PS4", "Xbox One"],
      "size_gb": 30.2
    },
    {
      "title": "Apex Legends",
      "publisher": "Electronic Arts",
      "release_date": "2019",
      "platform": ["PC", "PS4", "Xbox One"],
      "size_gb": 32.7
    },
    {
      "title": "Minecraft",
      "publisher": "Mojang Studios",
      "release_date": "2011",
      "platform": ["PC", "PS4", "Xbox One", "Nintendo Switch", "iOS", "Android"],
      "size_gb": 1.6
    },
    {
      "title": "Super Smash Bros. Ultimate",
      "publisher": "Nintendo",
      "release_date": "2018",
      "platform": ["Nintendo Switch"],
      "size_gb": 16.8
    },
    {
      "title": "FIFA 22",
      "publisher": "Electronic Arts",
      "release_date": "2021",
      "platform": ["PC", "PS4", "PS5", "Xbox One", "Xbox Series X/S"],
      "size_gb": 50.5
    },
    {
      "title": "NBA 2K22",
      "publisher": "2K Sports",
      "release_date": "2021",
      "platform": ["PC", "PS4", "PS5", "Xbox One", "Xbox Series X/S"],
      "size_gb": 102.3
    },
    {
      "title": "Forza Horizon 5",
      "publisher": "Xbox Game Studios",
      "release_date": "2021",
      "platform": ["Xbox One", "PC"],
      "size_gb": 103.8
    }
  ]
```
### About the Dataset


This dataset contains information about a selection of 22 popular video games, including their titles, publishers, release dates, platforms, and file sizes. Each game entry consists of the following properties:

- **Title**: The name of the game.
- **Publisher**: The company responsible for publishing the game.
- **Release Date**: The year the game was released.
- **Platform**: A list of platforms on which the game is available (e.g., PC, PS4, Xbox One, etc.).
- **Size (GB)**: The file size of the game in gigabytes.

# Now the questions:

1. `Every` Method:
    - Are all games released after the year 2010?
    - Do all games have a size greater than 50 GB?
    - Are all games available on at least two platforms?
2. `Some` Method:
    - Does any game have a release date before the year 2000?
    - Are there any games with a size larger than the total size of all Nintendo Switch games combined?
    - Does at least one game have a publisher name longer than 15 characters?
3. `Filter` Method:
    - Which games have a size larger than the average size of all games?
    - Can you filter out all the games released on both Xbox One and PS4?
    - Find all the games published by companies whose names contain more than one word.
4. `Map` Method:
    - Create an array containing only the titles of the games, sorted alphabetically.
    - Generate an array of objects containing only the titles and publishers of the games, but with the titles in uppercase.
    - How would you convert the release dates of all the games to just the year, and then find the count of games released each year?

5. `Reduce` Method:
    - What is the total size in gigabytes of all the games published by Sony Interactive Entertainment?
    - Which publisher has the most games in the list, and how many games do they have?
    - Can you find the game with the largest size, and its title?
