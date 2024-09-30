# Wikipedia Web Crawler and Search Engine

This project implements a simple web crawler to crawl Wikipedia pages, starting from the **List of Pharaohs**. It builds an **inverted index** of visited pages and ranks pages based on their **cosine similarity** with a user-provided query.

## Features
- **Web Crawler**: Crawls Wikipedia starting from the [List of Pharaohs](https://en.wikipedia.org/wiki/List_of_pharaohs) page.
- **Inverted Index**: Builds an inverted index for all visited pages.
- **Cosine Similarity**: Computes the cosine similarity between each page and a user-provided query.
- **Ranking**: Ranks and displays the top k (default 10) pages based on the cosine similarity score.

## Prerequisites
- **Java 8 or higher**.
- **JSoup**: A Java library for HTML parsing.
  - You can include JSoup by adding the following dependency to your `pom.xml` if using Maven:
    ```xml
    <dependency>
      <groupId>org.jsoup</groupId>
      <artifactId>jsoup</artifactId>
      <version>1.14.3</version>
    </dependency>
    ```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/wikipedia-crawler.git
   cd wikipedia-crawler
