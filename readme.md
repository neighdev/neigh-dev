# Running
To run this site in docker run 
`docker run -p 4000:4000 -v "/absolute/path/to/repo/neigh-dev:/site" bretfisher/jekyll-serve`

To build this site using docker run
`docker run -p 4000:4000 -v "/absolute/path/to/repo/neigh-dev:/site" bretfisher/jekyll-serve bash -c 'bundle install && bundle exec jekyll build'`