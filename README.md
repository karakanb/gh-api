# hn-api
A simple microservice to parse GitHub Trending page to JSON.

## Request
```http
GET https://gh-api.now.sh
```

## Response
```json
[
  {
    "repo": {
      "rawName": "InterviewMap / InterviewMap",
      "owner": "InterviewMap",
      "name": "InterviewMap",
      "link": "/InterviewMap/InterviewMap",
      "description": "Build the best interview map. The current content includes JS, network, browser related, performance optimization, security, framework, Git, data structure, algorithm, etc."
    },
    "stars": {
      "count": 3897,
      "link": "/InterviewMap/InterviewMap/stargazers"
    },
    "forks": {
      "count": 382,
      "link": "/InterviewMap/InterviewMap/network"
    },
    "todayStars": 652
  },
  {
    "repo": {
      "rawName": "donnemartin / system-design-primer",
      "owner": "donnemartin",
      "name": "system-design-primer",
      "link": "/donnemartin/system-design-primer",
      "description": "Learn how to design large-scale systems. Prep for the system design interview. Includes Anki flashcards."
    },
    "stars": {
      "count": 35648,
      "link": "/donnemartin/system-design-primer/stargazers"
    },
    "forks": {
      "count": 4503,
      "link": "/donnemartin/system-design-primer/network"
    },
    "todayStars": 521
  }
]
```

## License
The project is under MIT License.
