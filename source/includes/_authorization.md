## Authorization

```javascript
const { Client } = require('unb-api');
const client = new Client('API_TOKEN');
```

```python
import asyncio
from pybelieva import Client

async def main():
    client = Client("API_TOKEN")

asyncio.run(main())
```

```shell
# With curl, you pass the Authorization header with each request
curl "https://unbelievaboat.com/api/" -H "Authorization: API_TOKEN"
```


> Make sure to replace `API_TOKEN` with your API token.

All requests require the <code>Authorization</code> header to be set.  
Authorization type is not required, it's just the token.

### Bot Authorization
API tokens can be created for Discord bots which allows them to make requests on guilds they have been authorized on.

<button class="blurple" onclick="window.open('https://unbelievaboat.com/applications', '_blank')">
    Applications
</button>
