
# Multiverse Java Self-Study Project

A Java recreation of a previous full-stack project/api, completed while participating in the Multiverse program


## Self-Study Plan

- Learn Java by utilizing PluralSight and YouTube lessons and tutorials
- Design/Outline project by end of 8/1
- 
- Verify CRUD functionality across project


## Lessons Links

[YouTube Playlist](https://youtube.com/playlist?list=PLtgniFeQ_KZvK-sHoQ21kjPzHrGGdmViA) - Scroll to the bottom to see the Java related lessons and tutorials

[PluralSight Channel](https://app.pluralsight.com/channels/details/c591aeb5-e7c6-44ad-959a-0a88d1ff24de)

[O'Reilly e-book](https://www.barnesandnoble.com/w/learning-java-marc-loy/1135637237?ean=9781492056270) - I have yet to start reading, but I'm sure it will come in handy in the coming weeks
## Project Features

**CRUD Functionality:** 
 - Browse all lists and individual Pokemon
 - Create/Delete lists
 - Add/Remove Pokemon to/from lists
 

**Utilize External API:**
 - Pull Pokemon data and images from PokeAPI
## API Reference

### POST

 - Create NEW List

```http
  POST /api/create/list
```

### GET

 - Catch ALL Pokemon

```http
  GET /api/pokemon
```
 - Catch Pokemon by PokeAPI ID

```http
  GET /api/pokemon/${pokedex}
```

 - Catch ALL Lists

```http
  GET /api/lists
```

 - Catch List by ID

```http
  GET /api/lists/${id}
```

 - Catch Pokemon from List

```http
  GET /api/lists/${id}/all-pokemon
```

### PUT

 - Delete Pokemon from List

```http
  PUT /api/edit/${id}/pokemon/${pokedex}/delete
```

 - Rename List

```http
  PUT /api/edit/${id}/change-name
```

### DELETE

 - Delete List

```http
  PUT /api/edit/${id}/delete
```
### Acknowledgements

 - [Readme Editor](https://readme.so/editor) - Simplified the README creation process
 - [PokeAPI](https://pokeapi.co/) - Complete Pokemon database
 - [Programming with Mosh](https://www.youtube.com/c/programmingwithmosh) - Fantastic content creator on YouTube, really helped me out

#
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://studiobebop.games)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/haley-tobias-019a84132/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/mrsallhershots)

