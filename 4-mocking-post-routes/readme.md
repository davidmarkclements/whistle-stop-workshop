# Mocking POST Routes

https://shorturl.at/myBQ4


# [Phase 1](./1)

* Modify `static/index.html`

**Diff:** https://github.com/davidmarkclements/whistle-stop-workshop/commit/00ba4ee3b5ea4583453876ccb88ed344096516d2

# [Phase 2](./2)

* Modify `static/app.js`

**Diff:** https://github.com/davidmarkclements/whistle-stop-workshop/commit/75723081e97cdc1197204e3a8062d94fe68ff5cf

# [Phase 3](./3)

* Create the local `data-utils` Fastify plugin

**Diff:** https://github.com/davidmarkclements/whistle-stop-workshop/commit/ec49efb02f14c2231e8ad5cf7ce2c958bcc28559

# [Phase 4](./4)

* Add the `/confectionery` POST route
* Add the  `/electronics` POST route

**Diff:** https://github.com/davidmarkclements/whistle-stop-workshop/commit/31dc7e1ab5f5df613a926bd1c8476595ebcd5403

# Check

* Locally serve the static folder
* In another terminal, run the server 
* Navigate to http://localhost:5050
* Select the "Electronics" category
* Fill out all three fields and click "Add"
* Note that a new item is added
* Refresh the page, select "Electronics" - note how the added item is still there
* Check the server log output, there should be a POST request to `/electronics`

