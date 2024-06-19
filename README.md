# Bachelor-s_Thesis_Barentz
The Pure Regular Expression (Regex) approach in both Python notebooks could be considered as follows:
1. Load the input data: a large collection of PDF documents with unsystematic product descriptions and no uniformity in layout and naming conventions.
2. Extracting the complete PDF file information to plain text using PyPDF2.
3. Applying the regular expression algorithm to identify specific patterns for information we are looking for, namely, those 9 mandatory attributes. Extract the specific information from the plain text and eventually store the extracted information in the structured NM relational data model.

Performance Evaluation of the Regex Algorithm:
- The advantages of using regular expressions included high accuracy, short runtime, and ease of understanding.
- Disadvantages included low scalability, requiring constant updates for new formats, and limited flexibility for different languages.

Future Recommendations of Regex approach:
Regex has been proven to be a very good and accurate base of information extraction technique, but perhaps, its strength will be optimized when integrated with other NLP algorithms, such as Bag of Words (BoW), and NLTK (Language detection).
