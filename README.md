<p align="center">
  <h1 align="center">Train Route</h1>
</p>

<p align="center">
<img loading="lazy" src="http://img.shields.io/static/v1?label=Status&message=Finished&color=yellow&style=for-the-badge"/>
<img loading="lazy" src="http://img.shields.io/static/v1?label=License&message=MIT&color=yellow&style=for-the-badge"/>
<img loading="lazy" src="http://img.shields.io/static/v1?label=Release%20Date&message=June&color=yellow&style=for-the-badge"/>
</p>

# Index 

* [Project Description](#project-description)
* [Features and Application Demo](#features-and-application-demon)
* [Technologies used](#technologies-used)

# Project Description
<p>
  This project consists of an application that calculates train routes between Ibernian cities. The system uses two files: a binary file containing the names of the origin and destination cities, along with the distance between them, and another file containing the names of cities and their coordinates (X, Y) on the map.
</p>

  # :hammer: Features and Application Demo
- `Feature 1`: Reading and Storing City Data
  - The city file is read, and its records are stored in a binary search tree.
  - Each node in the city tree contains a city record, along with an initially empty Simple List to store the accessible paths from that city.

- `Feature 2`: Reading and Storing Path Data
  - The path file is read sequentially.
  - Each path record is stored at the end of the linked list stored in the node of the originating city in the city tree.
  
- `Feature 3`: Train Route Calculation
  - The system can calculate train routes between Hibernian cities based on the data provided in the files.

# Technologies used
- `C#`
- `Binary Three`
- `Linked List`

# authors

| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/114159027?v=4" width=115><br><sub>Eduarda Paiva</sub>](https://github.com/PaivaEduarda) | [<img loading="lazy" src="https://avatars.githubusercontent.com/u/114162946?v=4" width=115><br><sub>Eloisa Paixão</sub>](https://github.com/eloisapaixao) | 
| :---: | :---: |






