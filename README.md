# The Ultimate Star Wars Planet Dataset
This repository contains datasets extracted from Wikidata related to the planets of the Star Wars galaxy. The datasets include entities, their properties, and associated labels and descriptions. The data is serialized in multiple formats to facilitate easy access and integration into various applications.
This repository is part of the **Holonet Galactic Encyclopedia** project, which aims to provide a comprehensive and interactive map of the Star Wars universe. You can explore the project at [Holonet Galactic Encyclopedia](https://holonetgalacticmap-frontend.vercel.app/).

## Datasets
The datasets are available in the following formats:
- **N-Triples**: A line-based, plain text format for encoding an RDF graph.
- **Turtle**: A compact and readable RDF format that supports prefixes and compact notation.

## Files
- `star_wars_planets_dataset.nt`: N-Triples format of the dataset.
- `star_wars_planets_dataset.ttl`: Turtle format of the dataset.

## Data Extraction
The data was extracted using a SPARQL `CONSTRUCT` query on the Wikidata Query Service. The query retrieves entities related to the Star Wars franchise, along with their properties, labels, and descriptions. The query also includes a one-hop neighborhood of related entities.

## Usage
You can use these datasets for various applications, such as:
- **Training AI Models**: Utilize the structured data to train AI models to generate new planets or predict features within the Star Wars universe.
- **Building Knowledge Graphs**: Create knowledge graphs for educational purposes or practice, allowing users to explore and learn about the relationships between Star Wars entities.
- **Analyzing Relationships**: Examine the connections between different entities in the Star Wars universe to gain insights into planetary systems, and more.
- **Integrating Structured Data**: Seamlessly integrate Star Wars data into applications that require structured data, enhancing user experiences with rich, interconnected information.

## Cite this Work
Chabot, Y. (2025). Holonet Galactic Encyclopedia. Retrieved from https://holonetgalacticmap-frontend.vercel.app/

## License
The datasets are licensed under the [Creative Commons Attribution-ShareAlike License](https://creativecommons.org/licenses/by-sa/3.0/). Please attribute Wikidata as the source of the data and include a link to the license.

## Contributing
If you would like to contribute to this project, visit https://holonetgalacticmap-frontend.vercel.app/contribute

## Contact
For any questions or suggestions, please open an issue or contact the repository maintainer.
