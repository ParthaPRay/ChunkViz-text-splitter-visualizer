# ChunkViz-text-splitter
This report contains the information about ChunkViz that allows to visulalize the text splitting for Langchain and LlamaIndex made by Greg Kamradt.

# About

ChunkViz v0.1 appears to be a tool designed to help understand and implement various text chunking or splitting strategies. Text chunking is a process where a larger body of text is divided into smaller, more manageable pieces, or 'chunks'. This is particularly useful in the context of language models, as they often have a limit to the amount of text they can process in a single pass (known as a 'context window').

The idea behind ChunkViz seems to be based on the understanding that language models can perform better when they are given less but more relevant information. Deciding what subset of data to use can be challenging, especially for a computer. Chunking is one common method to address this, by breaking down a large dataset into smaller segments according to a chosen strategy.

In the description, various aspects of ChunkViz are outlined:

* Character Splitter: This is likely a feature that allows you to divide the text into chunks based on the number of characters.

* Chunk Size and Overlap: These settings control the length of each text chunk and the amount of overlap between sequential chunks. Overlap can help maintain context across chunks.

* Color Coding: The tool seems to use different colors to represent different chunks, and overlapping text may be highlighted in a distinct color (like orange).

* Notes and Additional Features: It mentions text splitters and analytics used, and suggests that the tool is open-source and welcomes contributions.

* Implementation References: Links to LangChain and Llama Index for Python and JavaScript implementations of text splitters, indicating that these might be frameworks or libraries used in the tool.

* License and Author: It's under the MIT License and created by Greg Kamradt.

In essence, ChunkViz v0.1 is a utility for experimenting with and understanding different ways to divide text into chunks, which is critical for optimizing the performance of language models by feeding them the most relevant and manageable pieces of information.




# Software

Visualizer on Railway

https://chunkviz.up.railway.app/

![Screenshot 2024-01-04 142025](https://github.com/ParthaPRay/ChunkViz-text-splitter/assets/1689639/b6b365ae-f174-4398-ba9c-ead3ffc303ff)


# Code on Github


https://github.com/gkamradt/ChunkViz


References

1. https://python.langchain.com/docs/modules/data_connection/document_transformers/
