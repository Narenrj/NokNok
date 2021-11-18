Goal:

Write a program in Java to count words in web page content.
Inputs:
1. List of URLs (select your own URLs for testing) provided in a text file, e.g. urls.txt
2. List of words (select your own words for testing) provided in a text file, e.g. words.txt
Outputs:
1. For each URL, print:
a. the top 3 words on the given list
b. the number of occurrences of each word
List the words sorted by the number of occurrences in descending order.
2. For each word on the given list, print the total number of occurrences across all the
specified URLs. List the words sorted by the total number in descending order

External Libraries Used:
Jsoup: Jsoup is a Java library for working with real-world HTML. Scrape and parse HTML from a URL, file, or string
Can be downloaded from: https://jsoup.org/download

How To Run the Project:
Method 1: Using IDE
* Unzip the Package 
* Open it using any IDE such as IntelliJ IDEA or Eclipse as it is a normal JAVA project.
* Identify the Main class containing the main method.
* Modify the text files URLs.txt(list of URLS to be validated against) and Words.txt(list of words to be searched on the given web pages) as per your needs.
* Execute the main method
* Returns the count of words in a web page.

Method 2: Using Command Prompt / Terminal
* A Java Version 17 is required.
* Two text files are required to read the list of URLs and the Words.(Under Sample files Folder)
* These files should be named URLs.txt and Words.txt under C:/
* Download the jar file provided.
* Open the terminal at the same location of the .jar file 
* Run the following command java -jar NokNok_CodingChallenge.jar


References:
1) https://jsoup.org/
2) https://stackabuse.com/how-to-sort-a-hashmap-by-value-in-java/



