# Reddit Answers Scraper

![Reddit Answers Scraper](https://i.ibb.co/wr4Whp9h/reddit-answers-cover.png)

This actor is designed to scrape structured answers from Reddit Answers, Reddit's AI-powered Q&A feature that aggregates community knowledge from across subreddits. Simply provide your questions, and get back comprehensive, organized answers with sources, related posts, and suggested topics—all in a clean, structured format.

<p align="center">
  <img src="https://apify-image-uploads-prod.s3.us-east-1.amazonaws.com/DevbkY3adMTBuoECt-actor-AU5vAy3MwkDIMg4KW-AxAg5ngsp3-Icon_%283%29.jpeg" alt="Reddit Answers Scraper" style="height: 60px; margin-right: 15px;" /><a href="https://apify.com/lexis-solutions/reddit-answers-scraper" target="_blank">
    <img src="https://img.shields.io/badge/Try%20it%20on-Apify-0066FF?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNDA4IiBoZWlnaHQ9IjQwOCIgdmlld0JveD0iMCAwIDQwOCA0MDgiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjxnIGNsaXAtcGF0aD0idXJsKCNjbGlwMF8zNDFfNDE1NykiPgo8cGF0aCBkPSJNMjE4LjY5NSAxMDRIMzAwLjk3QzMwMi42NDMgMTA0IDMwNCAxMDUuMzU3IDMwNCAxMDcuMDNWMjMyLjc2NkMzMDQgMjM1Ljc3OCAzMDAuMDgzIDIzNi45NDUgMjk4LjQzNCAyMzQuNDI1TDIxNi4xNTkgMTA4LjY5QzIxNC44NDEgMTA2LjY3NCAyMTYuMjg3IDEwNCAyMTguNjk1IDEwNFoiIGZpbGw9IndoaXRlIi8+CjxwYXRoIGQ9Ik0xODkuMzA1IDEwNEgxMDcuMDNDMTA1LjM1NyAxMDQgMTA0IDEwNS4zNTcgMTA0IDEwNy4wM1YyMzIuNzY2QzEwNCAyMzUuNzc4IDEwNy45MTcgMjM2Ljk0NSAxMDkuNTY2IDIzNC40MjVMMTkxLjg0IDEwOC42OUMxOTMuMTU5IDEwNi42NzQgMTkxLjcxMyAxMDQgMTg5LjMwNSAxMDRaIiBmaWxsPSJ3aGl0ZSIvPgo8cGF0aCBkPSJNMjAyLjU5MSAyMDQuNjY4TDEwOS4xMjcgMjk4LjgzNUMxMDcuMjI5IDMwMC43NDcgMTA4LjU4MyAzMDQgMTExLjI3OCAzMDRIMjk2LjhDMjk5LjQ4MyAzMDQgMzAwLjg0MiAzMDAuNzcgMjk4Ljk2NyAyOTguODUyTDIwNi45MDggMjA0LjY4NUMyMDUuNzI2IDIwMy40NzUgMjAzLjc4MiAyMDMuNDY4IDIwMi41OTEgMjA0LjY2OFoiIGZpbGw9IndoaXRlIi8+CjwvZz4KPGRlZnM+CjxjbGlwUGF0aCBpZD0iY2xpcDBfMzQxXzQxNTciPgo8cmVjdCB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEwNCAxMDQpIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==&logoColor=white" alt="Try it on Apify" style="border-radius: 12px; height: 60px;" />
  </a>
</p>


Watch our video tutorial on how to use Reddit Answers Scraper:

[Video tutorial](https://www.youtube.com/watch?v=lelpAtLNjoc 'Video tutorial on how to use Reddit Answers Scraper')

---


## 📊 Actor Stats

| Stat | Value |
|------|-------|
| **Version** | `0.1.4` |
| **Last Update** | Dec 1, 2025 |

---



## 💻 Integration Examples

This repository includes example code showing how to integrate the `reddit-answers-scraper` actor into your projects.

You can find example implementations in the [`examples/`](./examples) folder:
- **TypeScript/JavaScript**: See [`examples/typescript/`](./examples/typescript) for a complete TypeScript example
- **Python**: See [`examples/python/`](./examples/python) for a complete Python example

Each example includes:
- Ready-to-use code templates
- Setup instructions
- Documentation links

---


## 🚀 Key Features

- ✅ Extracts **AI-generated answers** organized by topic sections
- ✅ Retrieves **source subreddits** and **related Reddit posts** with full metadata
- ✅ Captures **related topics** for deeper exploration
- ✅ Supports **multiple questions** in a single run
- ✅ Full proxy support for stable and geo-aware scraping

---

## 👤 Who Is This Actor For?

This actor is perfect for:

- 📊 **Market researchers** gathering community opinions and insights
- 🧠 **Content creators** researching trending topics and discussions
- 💬 **Social media analysts** tracking Reddit conversations and sentiment
- 🔍 **SEO professionals** finding popular questions and user-generated content
- 📚 **Knowledge base builders** aggregating community wisdom from Reddit
- 🤖 **AI/ML practitioners** collecting training data from real user discussions

---

## ❓ Why Is This Actor Important?

Reddit Answers is a relatively new feature that synthesizes information from multiple subreddits and posts to answer user questions. The content is dynamically streamed and rendered, making it difficult to access programmatically. This actor:

- Waits for the complete answer to be streamed before extraction
- Extracts clean and structured data including sections, sources, and related content
- Saves you hours of manual research and data collection
- Provides access to curated community knowledge at scale

---

## Tech Notes

- It is recommended to set the actor memory to at least 4GB to avoid performance issues.

- It is recommended to set the actor's proxy type to residential.

---

## Input Schema

Here's an example input you can pass to the actor:

```json
{
  "questions": [
    "tips to improve water pressure",
    "how many planets are in our solar system?",
    "what is the best programming language for beginners?"
  ],
  "proxyConfiguration": {
    "useApifyProxy": true,
    "apifyProxyGroups": ["RESIDENTIAL"]
  }
}
```

### Input Parameters

- **questions** (required): An array of questions you want answers for. Each question will be submitted to Reddit Answers.
- **proxyConfiguration** (required): Proxy settings for the scraper. Useful for avoiding rate limits and geo-restrictions.

---

## Output Schema

```json
{
  "url": "https://www.reddit.com/answers/c3f081c9-0b70-4e90-a729-ff7aa8ff8c8b/?q=best+disney+movies+of+all+time&source=ANSWERS",
  "question": "best disney movies of all time",
  "sources": [
    "https://www.reddit.com/r/DisneyMovies",
    "https://www.reddit.com/r/movies",
    "https://www.reddit.com/r/FavoriteMedia"
  ],
  "sections": [
    {
      "heading": "Classic and Nostalgic Favorites",
      "content": [
        "The Lion King (1994): Universally praised for its stunning animation, powerful storytelling, and iconic soundtrack. \"The Lion King is the greatest Disney movie of all time.\"        Beauty and the Beast (1991): Celebrated for its enchanting story, memorable characters, and beautiful music. \"Beauty and the Beast\"        Aladdin (1992): Known for its vibrant animation, thrilling adventure, and the unforgettable performance by Robin Williams as the Genie. \"Aladdin. Because Robin Williams.\"        The Little Mermaid (1989): A beloved musical with charming characters and a captivating underwater world. \"The Little Mermaid\"        Sleeping Beauty (1959): Admired for its artistic backgrounds and stunning animation. \"Sleeping Beauty is a masterwork of artistry.\""
      ],
      "items": [
        {
          "itemContent": "The Lion King (1994): Universally praised for its stunning animation, powerful storytelling, and iconic soundtrack. \"The Lion King is the greatest Disney movie of all time.\"",
          "sourceContent": [
            {
              "content": "\"The Lion King is the greatest Disney movie of all time.\"",
              "url": "https://www.reddit.com/r/movies/comments/1d6we4j/comment/mnjdqxb/"
            }
          ]
        },
        {
          "itemContent": "Beauty and the Beast (1991): Celebrated for its enchanting story, memorable characters, and beautiful music. \"Beauty and the Beast\"",
          "sourceContent": [
            {
              "content": "\"Beauty and the Beast\"",
              "url": "https://www.reddit.com/r/DisneyMovies/comments/1o3j6l5/comment/nivhsf5/"
            }
          ]
        },
        {
          "itemContent": "Aladdin (1992): Known for its vibrant animation, thrilling adventure, and the unforgettable performance by Robin Williams as the Genie. \"Aladdin. Because Robin Williams.\"",
          "sourceContent": [
            {
              "content": "\"Aladdin. Because Robin Williams.\"",
              "url": "https://www.reddit.com/r/AskReddit/comments/1nrh8v9/comment/ngef5bo/"
            }
          ]
        },
        {
          "itemContent": "The Little Mermaid (1989): A beloved musical with charming characters and a captivating underwater world. \"The Little Mermaid\"",
          "sourceContent": [
            {
              "content": "\"The Little Mermaid\"",
              "url": "https://www.reddit.com/r/movies/comments/1d6we4j/comment/l6vbkt7/"
            }
          ]
        },
        {
          "itemContent": "Sleeping Beauty (1959): Admired for its artistic backgrounds and stunning animation. \"Sleeping Beauty is a masterwork of artistry.\"",
          "sourceContent": [
            {
              "content": "\"Sleeping Beauty is a masterwork of artistry.\"",
              "url": "https://www.reddit.com/r/disney/comments/1ienw9j/comment/ma9t2y8/"
            }
          ]
        }
      ]
    },
    {
      "heading": "Modern and Popular Choices",
      "content": [
        "Frozen (2013): A global phenomenon with catchy songs and a strong message. \"Frozen. It makes me tear up every time.\"        Moana (2016): Praised for its strong female lead, cultural richness, and exceptional soundtrack. \"Moana. The soundtrack alone is legendary.\"        Tangled (2010): Noted for its beautiful animation and engaging storyline. \"Tangled's one of the most visually beautiful movies ever.\"        Zootopia (2016): Appreciated for its clever storytelling and relevant social themes. \"Zootopia\"    Encanto (2021): Celebrated for its vibrant cultural representation and catchy tunes. \"Encanto\""
      ],
      "items": [
        {
          "itemContent": "Frozen (2013): A global phenomenon with catchy songs and a strong message. \"Frozen. It makes me tear up every time.\"",
          "sourceContent": [
            {
              "content": "\"Frozen. It makes me tear up every time.\"",
              "url": "https://www.reddit.com/r/AskReddit/comments/1nrh8v9/comment/ngefuu5/"
            }
          ]
        },
        {
          "itemContent": "Moana (2016): Praised for its strong female lead, cultural richness, and exceptional soundtrack. \"Moana. The soundtrack alone is legendary.\"",
          "sourceContent": [
            {
              "content": "\"Moana. The soundtrack alone is legendary.\"",
              "url": "https://www.reddit.com/r/AskReddit/comments/1nrh8v9/comment/ngegsgp/"
            }
          ]
        },
        {
          "itemContent": "Tangled (2010): Noted for its beautiful animation and engaging storyline. \"Tangled's one of the most visually beautiful movies ever.\"",
          "sourceContent": [
            {
              "content": "\"Tangled's one of the most visually beautiful movies ever.\"",
              "url": "https://www.reddit.com/r/disney/comments/1ienw9j/comment/ma9r7wm/"
            }
          ]
        },
        {
          "itemContent": "Zootopia (2016): Appreciated for its clever storytelling and relevant social themes. \"Zootopia\"",
          "sourceContent": []
        },
        {
          "itemContent": "Encanto (2021): Celebrated for its vibrant cultural representation and catchy tunes. \"Encanto\"",
          "sourceContent": []
        }
      ]
    },
    {
      "heading": "Underrated Gems",
      "content": [
        "The Emperor's New Groove (2000): Known for its hilarious script and unique animation style. \"The Emperor's New Groove\"        Treasure Planet (2002): A sci-fi adaptation of \"Treasure Island\" with stunning visuals. \"Treasure Planet\"        The Hunchback of Notre Dame (1996): Praised for its deep themes and artistic animation. \"The Hunchback of Notre Dame\"        Lilo & Stitch (2002): Loved for its heartwarming story and unique characters. \"Lilo and Stitch\"    The Great Mouse Detective (1986): A charming take on Sherlock Holmes with delightful animation. \"The Great Mouse Detective\""
      ],
      "items": [
        {
          "itemContent": "The Emperor's New Groove (2000): Known for its hilarious script and unique animation style. \"The Emperor's New Groove\"",
          "sourceContent": [
            {
              "content": "\"The Emperor's New Groove\"",
              "url": "https://www.reddit.com/r/DisneyMovies/comments/1o3j6l5/comment/nivopdc/"
            }
          ]
        },
        {
          "itemContent": "Treasure Planet (2002): A sci-fi adaptation of \"Treasure Island\" with stunning visuals. \"Treasure Planet\"",
          "sourceContent": [
            {
              "content": "\"Treasure Planet\"",
              "url": "https://www.reddit.com/r/movies/comments/1ewyi8c/comment/lj2e7kw/"
            }
          ]
        },
        {
          "itemContent": "The Hunchback of Notre Dame (1996): Praised for its deep themes and artistic animation. \"The Hunchback of Notre Dame\"",
          "sourceContent": [
            {
              "content": "\"The Hunchback of Notre Dame\"",
              "url": "https://www.reddit.com/r/movies/comments/16te275/comment/k2ek4t2/"
            }
          ]
        },
        {
          "itemContent": "Lilo & Stitch (2002): Loved for its heartwarming story and unique characters. \"Lilo and Stitch\"",
          "sourceContent": []
        },
        {
          "itemContent": "The Great Mouse Detective (1986): A charming take on Sherlock Holmes with delightful animation. \"The Great Mouse Detective\"",
          "sourceContent": []
        }
      ]
    }
  ],
  "relatedPosts": [
    {
      "rank": "1",
      "title": "Top Five Disney Films.",
      "subreddit": "movies",
      "url": "https://www.reddit.com/r/movies/comments/1d6we4j/top_five_disney_films/",
      "upvotes": 8,
      "comments": 73,
      "domain": "self.movies",
      "promoted": false,
      "score": 8
    },
    {
      "rank": "2",
      "title": "Favorite Disney Movie of All Time",
      "subreddit": "DisneyMovies",
      "url": "https://www.reddit.com/r/DisneyMovies/comments/1o3j6l5/favorite_disney_movie_of_all_time/",
      "upvotes": 108,
      "comments": 260,
      "domain": "i.redd.it",
      "promoted": false,
      "score": 108
    },
    {
      "rank": "3",
      "title": "Best Disney movie of all time and why?",
      "subreddit": "AskReddit",
      "url": "https://www.reddit.com/r/AskReddit/comments/1nrh8v9/best_disney_movie_of_all_time_and_why/",
      "upvotes": 4,
      "comments": 32,
      "domain": "self.AskReddit",
      "promoted": false,
      "score": 4
    },
    {
      "rank": "4",
      "title": "What’s the best looking Disney film?",
      "subreddit": "disney",
      "url": "https://www.reddit.com/r/disney/comments/1ienw9j/whats_the_best_looking_disney_film/",
      "upvotes": 4,
      "comments": 999,
      "domain": "reddit.com",
      "promoted": false,
      "score": 4379
    },
    {
      "rank": "5",
      "title": "I didn't grow up with Disney films so I watched 72 of them to catch myself up",
      "subreddit": "movies",
      "url": "https://www.reddit.com/r/movies/comments/1ewyi8c/i_didnt_grow_up_with_disney_films_so_i_watched_72/",
      "upvotes": 15,
      "comments": 3,
      "domain": "self.movies",
      "promoted": false,
      "score": 15255
    },
    {
      "rank": "6",
      "title": "What is the best made Disney movie?",
      "subreddit": "movies",
      "url": "https://www.reddit.com/r/movies/comments/16te275/what_is_the_best_made_disney_movie/",
      "upvotes": 7,
      "comments": 143,
      "domain": "self.movies",
      "promoted": false,
      "score": 7
    },
    {
      "rank": "7",
      "title": "My Top 10 Favorite Disney Movies",
      "subreddit": "disney",
      "url": "https://www.reddit.com/r/disney/comments/1kwnwwl/my_top_10_favorite_disney_movies/",
      "upvotes": 110,
      "comments": 41,
      "domain": "reddit.com",
      "promoted": false,
      "score": 110
    },
    {
      "rank": "8",
      "title": "What are your Top-5 Disney movies?",
      "subreddit": "DisneyMovies",
      "url": "https://www.reddit.com/r/DisneyMovies/comments/1l7jjaa/what_are_your_top5_disney_movies/",
      "upvotes": 53,
      "comments": 100,
      "domain": "reddit.com",
      "promoted": false,
      "score": 53
    },
    {
      "rank": "9",
      "title": "Favorite Disney Movie of All Time",
      "subreddit": "Letterboxd",
      "url": "https://www.reddit.com/r/Letterboxd/comments/1nefc1p/favorite_disney_movie_of_all_time/",
      "upvotes": 51,
      "comments": 112,
      "domain": "i.redd.it",
      "promoted": false,
      "score": 51
    },
    {
      "rank": "10",
      "title": "I Ranked All of the Disney Movies I Seen",
      "subreddit": "FavoriteMedia",
      "url": "https://www.reddit.com/r/FavoriteMedia/comments/p3a99x/i_ranked_all_of_the_disney_movies_i_seen/",
      "upvotes": 47,
      "comments": 21,
      "domain": "i.redd.it",
      "promoted": false,
      "score": 47
    },
    {
      "rank": "11",
      "title": "What are your top 10-20 favorite Disney movies? (Including Pixar, not including Marvel or LucasFilm)",
      "subreddit": "FavoriteMedia",
      "url": "https://www.reddit.com/r/FavoriteMedia/comments/1l646df/what_are_your_top_1020_favorite_disney_movies/",
      "upvotes": 40,
      "comments": 35,
      "domain": "i.redd.it",
      "promoted": false,
      "score": 40
    },
    {
      "rank": "12",
      "title": "Disney animated films ranked!",
      "subreddit": "Letterboxd",
      "url": "https://www.reddit.com/r/Letterboxd/comments/1kzzo37/disney_animated_films_ranked/",
      "upvotes": 29,
      "comments": 123,
      "domain": "reddit.com",
      "promoted": false,
      "score": 29
    }
  ],
  "relatedTopics": [
    "top animated Disney films",
    "Disney movies with best soundtracks",
    "most underrated Disney classics"
  ]
}
```

### Output Fields

- **url**: The Reddit Answers page URL for the question
- **question**: The question that was asked
- **sources**: Array of subreddit URLs that contributed to the answer
- **sections**: Organized answer sections with headings and content
- **relatedPosts**: Array of relevant Reddit posts with metadata (rank, title, subreddit, upvotes, comments, etc.)
- **relatedTopics**: Suggested related questions for further exploration

---

## 💡 Use Cases

### 1. Market Research

Gather authentic community opinions on products, services, or topics by asking questions and analyzing the structured responses and related discussions.

### 2. Content Creation

Discover what questions people are asking and what answers resonate with communities. Use the insights to create targeted content.

### 3. Competitive Intelligence

Ask questions about competitors, industries, or products to see what the Reddit community is saying.

### 4. SEO & Content Strategy

Identify popular questions and related topics to inform your content strategy and target long-tail keywords.

### 5. Training Data Collection

Collect high-quality Q&A pairs with source attribution for training language models or building knowledge bases.

---

👀 p.s.

Got feedback or need an extension?

Lexis Solutions is a [certified Apify Partner](https://apify.com/partners/find). We can help you with custom solutions or data extraction projects.

Contact us over [Email](mailto:scraping@lexis.solutions) or [LinkedIn](https://www.linkedin.com/company/lexis-solutions)

## Support Our Work 💝

If you're happy with our work and scrapers, you're welcome to leave us a company review [here](https://apify.com/partners/find/lexis-solutions/review) and leave a review for the scrapers you're subscribed to. It will take you less than a minute but it will mean a lot to us!

Image Credit: https://www.reddit.com
