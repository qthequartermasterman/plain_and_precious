# Plain and Precious

> "It is a record like unto the engravings which are upon the plates of brass, save there are not so many; nevertheless, they contain the covenants of the Lord, which he hath made unto the house of Israel; wherefore, they are of great worth unto the Gentiles." --1 Nephi 13:23

## About

Holy Scripture is full of deep connections between various texts, hidden from the reader by a lack of context. This project aims to use technology to help the modern reader discover the plains and precious truths of the scriptures. 

This project primarily focuses on using Artificial Intelligence (specifically Large Language Models) to automatically discover connections between various texts. It strives to be like an automated scholar that the reader can use to inform their own study of the scriptures.

Of course, scripture is given by revelation, and thus is best received by revelation. This project is not meant to replace the Spirit, but rather to be a tool to help the reader discover new connections and insights, and inspire them to start asking deeper questions, which will lead to deeper revelation.

## Technical Components (WIP)

The project is in its infancy, and its design remains in flux. However, the following components are planned:

- [ ] Data Collection
- [ ] Vector Embedding Store (for look-up and RAG)
- [ ] Language Model Fine-tuning
- [ ] Language Model Querying
- [ ] Front end for querying and displaying connected texts
- [ ] Front end for chatting with a language model (finetuned on scripture and augmented with RAG)

We anticipate that each of the back-end components (Vector store, language model, and data collection) will be implemented as separate services deployed as Docker containers on a Kubernetes cluster. The front-end components will be deployed as a static site and/or a mobile app and/or a browser extension.

## Feature Roadmap

Before building the entire project, we plan on first building a Proof of Concept with a few key features. These include the following:
- [ ] Setting up a Vector Embedding Store
- [ ] Setting up a language model to create vector embeddings
- [ ] Setting up a small data collection pipeline that will scrape a few small sources (most likely just a few books from the Bible and Book of Mormon), process them, and store them in the vector embedding store
- [ ] Setting up a front-end that will allow the user to query the vector embedding store and display the results

After the Proof of Concept is built, we will build a Minimum Viable Product with all the features in [Technical Components](#technical-components-wip) implemented.

## Coding Standards
WIP

## Contributing

We welcome contributions to this project. Please see the [Contributing Guide](CONTRIBUTING.md) for more information.

## License

Plain and Precious is licensed under the [MIT License](LICENSE). See the LICENSE file for more details.


