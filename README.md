# hn-api
A simple microservice to parse GitHub Trending page to JSON.

## Request
```http
GET https://gh-api.now.sh
```

## Response
An array of following JSON:
```json
{
  "repo": {
    "rawName": "phobal / ivideo",
    "owner": "phobal",
    "name": "ivideo",
    "link": "/phobal/ivideo",
    "description": "一个可以观看国内主流视频平台所有视频的客户端（Mac、Windows、Linux） A client that can watch video of domestic(China) mainstream video platform"
  },
  "stars": {
    "count": 7603,
    "link": "/phobal/ivideo/stargazers"
  },
  "forks": {
    "count": 2087,
    "link": "/phobal/ivideo/network"
  },
  "todayStars": 142,
  "language": {
    "is": "JavaScript",
    "color": "#f1e05a"
  }
}
```

## License
The project is under MIT License.
