# Description

This github page houses our detailed blog write-up of how we built Prefixy.

## Pushing to prefixy.github.io:

- Clone this repo on your local machine.
- Any changes pushed to master will automatically show up on [prefixy.github.io](http://prefixy.github.io).

## Using jekyll

 - Navigate to `_/posts/2017-12-13-writeup.md`. This is where you can add content to the blog writeup.
 - Run the command `gem install jekyll` to get access to the jekyll binaries.
   - In the project directory, you can now run `bundle exec jekyll serve` in order to get a local server running on `localhost:4000`.
   - The server automatically watches for changes and regenerates automatically (but you still need to refresh the page manually).
 - Assets should be stored in `/assets/`. They can be accessed at `/assets/*`. Example useage is already in `_/posts/2017-12-13-writeup.md`.
