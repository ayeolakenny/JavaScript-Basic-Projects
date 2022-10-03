# Hacktoberfest 2022 - JavaScript Medium Programs

## Pokedex

### Description
This program is used to fetch the data of a pokemon from the PokeAPI and display it on the screen. It uses the axios library to fetch the data from the API.

### Image Example
![Pokedex](data:image/png;base64,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)

### Contributing
Please read the [CONTRIBUTING.md](../../CONTRIBUTING.md)

### Maintainer
- [Anamaya](https://www.linkedin.com/in/anamaya1729/)
- [Vaibhav](https://https://www.linkedin.com/in/vaibhava17/)

### License
**This project is licensed under the GNU GENERAL PUBLIC License - see the [LICENSE](../LICENSE) file for details**

### Happy Coding! :smile: