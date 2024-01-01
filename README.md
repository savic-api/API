# Slavic Mythology Deities

## Project Description
This repository is dedicated to a comprehensive collection of Slavic mythology deities, showcasing a unique blend of ancient folklore with modern representation. It includes detailed JSON structures for each deity, encompassing various attributes such as domains, symbols, and elements. The aim is to provide an accessible resource for enthusiasts, scholars, and developers interested in Slavic mythology and its adaptation in contemporary mediums.

## Model Descriptions

### Overview
The models (JSON structures) in this repository represent 30 Slavic deities, each with a unique identifier (`id`), name (`name`), description (`description`), and a set of attributes. These attributes cover various aspects of each deity, including their domains, symbols, associated elements, and other relevant concepts.

### Structure
Each deity is represented in a JSON object with the following structure:

```json
{
  "id": "Unique Identifier",
  "name": "Deity Name",
  "description": "Brief Description",
  "attributes": {
    "Domains": ["List", "Of", "Domains"],
    "Symbols": ["List", "Of", "Symbols"],
    "Element": "Associated Element",
    "Associated Concepts": ["List", "Of", "Concepts"]
  },
  "image": "Link to Image Representation"
}
```

Example
```json
{
  "id": "001",
  "name": "Perun",
  "description": "Slavic god of thunder and lightning.",
  "attributes": {
    "Domains": ["Thunder", "Lightning", "War", "Law"],
    "Symbols": ["Axe", "Thunderbolt"],
    "Element": "Air",
    "Associated Concepts": ["Strength", "Protection"]
  },
  "image": "http://example.com/perun.jpg"
}
```
## Repository Contents
/deities: This directory contains individual JSON files for each deity.
deities.json: A consolidated file containing JSON structures for all 30 deities.
README.md: Provides an overview and instructions for the repository.
Usage
This repository can be used as a reference for developing applications, educational content, or artistic projects related to Slavic mythology. The JSON format ensures easy integration into web applications, databases, and other digital platforms.

## Contributions
Contributions to this repository are welcome. Whether it's adding more information to existing deity profiles, suggesting new deities, or correcting any inaccuracies, feel free to create a pull request or open an issue.

##  License
Will be later
