# GOT-Java-Program
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
<br><br>
Program using Java, which enables users to explore GOT character profiles, as well as find and edit the relationship between various characters. Additional information about regions and houses within the GOT Relam are available for exploration, along with linked video interviews discussing character storylines from the cast of the GOT TV show. This project was designed and developed in fulfilment of a BSc Computing Data Structures and Algorithms Module. <br><br>
[Link To App Video Demo](https://drive.google.com/file/d/1AxHnKkthmPr2UDTQNTfIwjEmrKmQlQLq/view?usp=sharing)


## Features
- Stores and reads character profiles by using read to memory code to read the input file, query the line length and then create a person object with the details given in line, to then store into an ArrayList.


- Sorting Code to compare whole names of two people, the code then reorders the list depending on the comparison results <br>
`NOTE: import java.util.Comparator used to implement comparator function`
- Finds relationships between characters, by creating temporary arrays and then processing the metadata (character relationships and gender) and then traverses through parents and children to find relationship been two characters, to return an output. <br>
`NOTE: Only operated on 1 characters at a time`
- [GraphViz](https://developers.google.com/maps/documentation/places/web-service/overview) used to iterate through ArrayList and append Graphviz prerequistes to file.

# Screenshots
<p align="left">
<img src="https://user-images.githubusercontent.com/91830271/135812584-d0f138c5-c3d5-4623-996f-9586f0307e00.jpg" width="45%" height ="250">
<img src="https://user-images.githubusercontent.com/91830271/135812598-481878fe-62fd-4fc9-a63b-3ce29232a3e8.jpg" width="45%" height ="250">
<img src="https://user-images.githubusercontent.com/91830271/135812612-28a6e1da-ffc0-4c41-b6be-d103af77c925.jpg" width="45%" height ="250">
<img src="https://user-images.githubusercontent.com/91830271/135812622-070dab6d-c6ff-47a4-a447-daccfeea79b3.jpg" width="45%" height ="250">
<img src="https://user-images.githubusercontent.com/91830271/135812627-d80f3f97-c31f-44a7-b744-4cbf3441d1f9.jpg" width="45%" height ="250">
<img src="https://user-images.githubusercontent.com/91830271/135812647-b9d9d479-35fa-47ca-b312-d459e7d6c0fd.jpg" width="45%" height ="250">
<img src="https://user-images.githubusercontent.com/91830271/135812655-f914aca0-50f9-4e97-a90a-0b38d19fdc4d.jpg" width="45%" height ="250">
<img src="https://user-images.githubusercontent.com/91830271/135812659-40e9cfa0-76cf-40d9-8f20-25cd09d28df5.jpg" width="45%" height ="250">
<img src="https://user-images.githubusercontent.com/91830271/135812676-ed50a6d5-4f34-45e7-b42d-9b7e24b5735c.jpg" width="45%" height ="250">
</p>
