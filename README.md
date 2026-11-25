# exposing-repository-token-javascript-client
This example demonstrates a critical security risk where a simulated Bitbucket repository access token is accidentally embedded directly into client-side JavaScript. When served to a browser, this sensitive token becomes easily discoverable by anyone using developer tools. It highlights the danger of mismanaging tokens in Bitbucket Pipelines builds
