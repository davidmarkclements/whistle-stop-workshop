# Mocking GET Routes

Material: https://bit.ly/3GzIuwC

# Preparation

* Remove `server.js`

# [Phase 1](./1)

* Modify `static/index.html`

**Diff:** https://github.com/davidmarkclements/whistle-stop-workshop/commit/f4a0dd661b610314b8642fa88232ebba9599b468

# [Phase 2](./2)

* Modify `static/app.js`

**Diff:** https://github.com/davidmarkclements/whistle-stop-workshop/commit/85f68741d889260d5ea4210b22c0b5838b3ace17

# [Phase 3](./3)

* Create `mock-srv` folder
* Run `npm init fastify` inside `mock-srv`
* Install dependencies
* Install `fastify-cors`

**Diff:** https://github.com/davidmarkclements/whistle-stop-workshop/commit/988cbdc41d61010eb0d624e81f5541e6c358c899

# [Phase 4](./4)

* Register the `fastify-cors` plugin with Fastify

**Diff:** https://github.com/davidmarkclements/whistle-stop-workshop/commit/c37a38a8e0c76fbff5636eb1a2bfc6a70adea05d

# [Phase 5](./5)

* Create the `/confectionery` GET route
* Create the  `/electronics` GET route

**Diff:** https://github.com/davidmarkclements/whistle-stop-workshop/commit/f6c1ecfaba925f478a07d56b2269cb6ba89b681d


# Check

* Locally serve the static folder
* In another terminal, run the server 
* Navigate to http://localhost:5050
* Select the "Electronics" category
* Check the server logs to verify a GET request to `/electronics` was made
* Select the "Confectionery" category
* Check the server logs to verify a GET request to `/confectionery` was made

