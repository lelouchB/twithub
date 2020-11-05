
  # TwitHub

  Looks like your project hasn't been initialized yet! Don't worry, this is easy.

  ## Installing

  1. Deploy the TwitHub schema and admin to TakeShape (free account required) by clicking this button:<br />
    <a href="//app.takeshape.io/add-to-takeshape?repo=https://github.com/lelouchB/twithub/tree/master/.takeshape/pattern"><img alt="Deploy To TakeShape" src="https://images.takeshape.io/2cccc825-70be-431c-9ba0-10ab38ecd3a7/dev/8e2f7bda-0e08-4ede-a546-6df59be6a8bb/Deploy%20to%20TakeShape%402x.png?auto=format%2Ccompress" width="205" height="38"></a>
  2. In your new `TwitHub` TakeShape project click on the name `TwitHub` in the upper left, then click `API Keys` from the dropdown.
  3. Create an `<api-key>` with `CI` permissions, **save it somewhere safe**.
  4. Copy the `<project-id>` from any TakeShape URL (it looks like this `b9b1f9b0-313e-45d7-a92d-42dbbdec5dd0`)
  5. Go to [this repo's GitHub secrets](https://github.com/lelouchB/twithub/settings/secrets) and create two secrets:<br />
    - `TS_PROJECT_ID` = `<project-id>`<br />
    - `TS_AUTH_TOKEN` = `<api-key>`
  6. Run the `TwitHub >> README.md` workflow for the first time.<br />
    - Click the `Run workflow` button on [this page](https://github.com/lelouchB/twithub/actions?query=workflow%3A%22TwitHub+>>+README.md%22)<br />
    - Note: The  workflow file that generated these instructions will be automatically removed by a scheduled cleanup operation.
  7. That's it! Twit away by adding Twit content in TakeShape.

