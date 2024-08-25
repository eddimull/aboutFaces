# About Faces

A hugo static site for Laurie. To get it running locally, execute `docker compose up`.

To deploy, push to the main branch and the github action should take care of the rest.

- logs into github
- pulls down the repo
- runs a hugo build, which builds out the public directory
- stores the public the directory in an artifact
- submits the artifact as the github page
