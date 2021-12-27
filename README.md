# PingPong

Create two apis, named `foo` and `bar`. `bar` API will provide an enpoint as following:

**Request:**

```json
POST /ping
{
	"times": 2,
}
```

**Response:**

```json
{
  "pongs": ["pong", "pong"]
}
```

Send `POST /ping` request from `foo` API to `bar` API.

Add consumer tests to `foo` and provider test to `bar` API.
