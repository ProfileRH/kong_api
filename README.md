# kong_api
Provide a simple access to [kong](https://getkong.org) api

## What is kong ?

from the official website :
"Kong is a scalable, open source API Layer (also known as a API Gateway, or API Middleware).
Kong runs in front of any RESTful API and is extended through Plugins,
which provide extra functionalities and services beyond the core platform."

## Features
The package provide simple access to action as :
- List apis ([doc](https://getkong.org/docs/0.4.x/admin-api/#list-apis))
- Get one api ([doc](https://getkong.org/docs/0.4.x/admin-api/#retrieve-api))
- Add api ([doc](https://getkong.org/docs/0.4.x/admin-api/#add-api)) : will automatically manage if you have already register the api
- Get status ([doc](https://getkong.org/docs/0.4.x/admin-api/#retrieve-node-status))
- Get node info ([doc](https://getkong.org/docs/0.4.x/admin-api/#retrieve-node-informations))
- ...

More coming soon.

## Authors
- Kevin PLATEL <platel.kevin@gmail.com>
