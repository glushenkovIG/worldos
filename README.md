# WorldOS

<p align="center">
  <strong>An integrated operating system for the world, life, and social interactions</strong>
</p>

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#architecture">Architecture</a> •
  <a href="#getting-started">Getting Started</a> •
  <a href="#contributing">Contributing</a> •
  <a href="#license">License</a> •
  <a href="#meta-prompts">Meta-Prompts</a>
</p>

## Overview

WorldOS is a conceptual framework for understanding and building systems that integrate digital technology with human experience at multiple layers. The project aims to create a comprehensive ecosystem that bridges the gap between technological rationality and human complexity.

## Architecture

WorldOS is structured in four interconnected layers:

### 1. World OS - Memory Layer
The foundational layer that stores and organizes all data about the world - physical, digital, and conceptual. This serves as the unified knowledge graph and data repository that other layers build upon.

**Key Components:**
- Universal knowledge graph mapping relationships between entities
- Sensor and IoT device integration for real-time data collection
- Comprehensive API for data querying and updates

### 2. Life OS - Interface for Living Creatures
The personal layer that provides tools and interfaces for individuals to navigate and interact with the world effectively.

**Key Components:**
- Personalized assistants tailored to individual needs and goals
- Tools for managing health, productivity, and personal growth
- User-friendly interfaces for interacting with the World OS memory layer
- Automatic cataloging of people, texts, and events encountered in daily life
- Comprehensive storage of authors, co-authors, and reviewers from all consumed content
- Storage of both raw prompts and synthesized data to preserve information lineage

### 3. Social OS - Social Automation Layer
Facilitates and optimizes social interactions and relationships between individuals and groups.

**Key Components:**
- Collaboration and communication platforms
- Social network and relationship management tools
- Conflict resolution and cooperation mechanisms
- Automatic tracking and organization of social relationships and interactions
- Mapping of all social verticals and network connections
- JTBD (Jobs To Be Done) framework integration for capturing social context and purpose

### 4. Hypersocial - Human-AI Translation Layer
Bridges the gap between human irrationality and AI rationality, enabling AI to understand the complexity of human behavior.

**Key Components:**
- Models of human psychology and behavior
- Frameworks for interpreting cultural and social norms
- World as arena: understanding territories, order/chaos, hierarchies
- Dopamine systems and human motivation modeling

## Example Implementations

### Academic and Media Content Tracking

WorldOS provides structured methods for tracking and interconnecting people, content, and social relationships. Below are examples of how the system captures and organizes this information:

#### Example 1: Academic Paper Acknowledgments

```json
{
  "content_type": "academic_paper",
  "title": "AI as Normal Technology",
  "publication_date": "2025-04-14",
  "url": "https://knightcolumbia.org/content/ai-as-normal-technology",
  "permalink": "https://perma.cc/HVN8-QGQY",
  "publisher": "Knight First Amendment Institute",
  "authors": [
    {
      "name": "Arvind Narayanan",
      "role": "primary_author",
      "affiliation": "Princeton University",
      "position": "Professor of Computer Science",
      "other_roles": ["Knight Institute Visiting Senior Research Scientist (2022-2023)"]
    },
    {
      "name": "Sayash Kapoor",
      "role": "primary_author",
      "affiliations": [
        "Mozilla",
        "Princeton University Center for Human Values",
        "Princeton University Center for Information Technology Policy"
      ],
      "positions": [
        "Senior Fellow",
        "Laurance S. Rockefeller Fellow",
        "Computer Science Ph.D. Candidate"
      ]
    }
  ],
  "reviewers": [
    {
      "name": "Gillian Hadfield",
      "role": "detailed_reviewer",
      "comment_stage": "during_and_after_workshop"
    },
    {
      "name": "Seth Lazar",
      "role": "detailed_reviewer",
      "comment_stage": "during_and_after_workshop"
    },
    {
      "name": "Anonymous Peer Reviewer",
      "role": "detailed_reviewer",
      "comment_stage": "during_and_after_workshop"
    }
  ],
  "workshop_participants": [
    {"name": "Alex Abdo", "organization": "Knight First Amendment Institute"},
    {"name": "Borhane Blili-Hamelin"},
    {"name": "Kevin Feng"},
    {"name": "Henry Farrell"},
    {"name": "Katy Glenn-Bass"},
    {"name": "Atoosa Kasirzadeh"},
    {"name": "Sydney Levine"},
    {"name": "Nik Marda"},
    {"name": "Deirdre Mulligan"},
    {"name": "Daniel Susskind"}
  ],
  "additional_feedback": [
    {"name": "Shazeda Ahmed"},
    {"name": "Dean Ball"},
    {"name": "Nicholas Carlini"},
    {"name": "Alan Chan"},
    {"name": "Ajeya Cotra"},
    {"name": "Justin Curl"},
    {"name": "Jeffrey Ding"},
    {"name": "Benjamin Edelman"},
    {"name": "Jobst Heitzig"},
    {"name": "Noam Kolt"},
    {"name": "Mihir Kshirsagar"},
    {"name": "Timothy B. Lee"},
    {"name": "Steve Newman"},
    {"name": "David Robinson"},
    {"name": "Matthew Salganik"},
    {"name": "Zachary Siegel"},
    {"name": "Ollie Stephenson"},
    {"name": "Zach Vertin"}
  ],
  "editorial_support": [
    {"name": "Shira Minsk", "role": "editorial_support"},
    {"name": "Mandy Soulsby-Bodart", "role": "editorial_support"}
  ],
  "organizational_feedback": [
    {"organization": "MINT lab", "institution": "Australian National University"},
    {"organization": "Limits to Prediction course", "institution": "Princeton University"}
  ],
  "social_network_analysis": {
    "primary_institutions": ["Princeton University", "Mozilla", "Knight Institute"],
    "collaboration_clusters": [
      {"cluster": "AI Ethics", "members": ["Arvind Narayanan", "Sayash Kapoor", "Gillian Hadfield"]},
      {"cluster": "Information Technology Policy", "members": ["Arvind Narayanan", "Sayash Kapoor", "Deirdre Mulligan"]}
    ]
  }
}
```

#### Example 2: Website with Multiple Contributors

```json
{
  "content_type": "website",
  "title": "AI 2027",
  "url": "ai-2027.com",
  "domain": "prediction_forecast",
  "contributors": [
    {"name": "Daniel Kokotajlo", "role": "contributor", "order": 1},
    {"name": "Scott Alexander", "role": "contributor", "order": 2},
    {"name": "Thomas Larsen", "role": "contributor", "order": 3},
    {"name": "Eli Lifland", "role": "contributor", "order": 4},
    {"name": "Romeo Dean", "role": "contributor", "order": 5},
    {"name": "Oliver Habryka", "role": "contributor", "order": 6},
    {"name": "Ruby Bloom", "role": "contributor", "order": 7},
    {"name": "Jacob Lagerros", "role": "contributor", "order": 8},
    {"name": "Ben Pace", "role": "contributor", "order": 9},
    {"name": "Raymond Arnold", "role": "contributor", "order": 10},
    {"name": "Rafe Kennedy", "role": "contributor", "order": 11},
    {"name": "Robert Mushkatblat", "role": "contributor", "order": 12}
  ],
  "sections": [
    {"name": "Summary", "path": "/summary"},
    {"name": "Research", "path": "/research"},
    {"name": "About", "path": "/about"}
  ],
  "social_network_analysis": {
    "related_entities": [
      {"name": "Scott Alexander", "affiliations": ["Astral Codex Ten", "LessWrong"]},
      {"name": "Eli Lifland", "affiliations": ["Quantified Uncertainty Research Institute"]},
      {"name": "Oliver Habryka", "affiliations": ["LessWrong", "Lightcone Infrastructure"]},
      {"name": "Ben Pace", "affiliations": ["LessWrong", "Lightcone Infrastructure"]},
      {"name": "Jacob Lagerros", "affiliations": ["EA Funds", "LessWrong"]},
      {"name": "Raymond Arnold", "affiliations": ["LessWrong"]}
    ],
    "community_clusters": [
      {"name": "Rationalist Community", "members": ["Scott Alexander", "Oliver Habryka", "Ben Pace", "Raymond Arnold"]},
      {"name": "AI Safety", "members": ["Daniel Kokotajlo", "Eli Lifland", "Jacob Lagerros"]}
    ],
    "conceptual_framework": "Multi-level game theory applied to AI prediction markets"
  }
}
```

These examples demonstrate how WorldOS captures not just basic metadata, but rich social structures, relationships, and interconnections between people and content. The system automatically tracks:

1. Primary content creators and their roles
2. Hierarchical relationships within contributor groups
3. Institutional affiliations and positions
4. Feedback and review processes
5. Social and professional connections between individuals
6. Conceptual frameworks and domains

This information becomes part of the unified knowledge graph, enabling users to navigate connections between people, content, and ideas across their entire ecosystem of interactions.

## Getting Started

_This section will be expanded as the project develops._

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).

## Meta-Prompts

Below are the original prompts that inspired and guided this project:

```
help me think about what world os will and should be

like shema is like this

world os -- memory layer

life os -- operating system (interface) for living creatures for the world

social os -- social aspect of life automation

hypersocial -- explaining irrational human world (world as arena of actions, as known and unknown territory, as order and chaos and hierarchy and dopamine system), to a rational orderly ai
