# Repro

1. Run `now` and visit `<deployed URL>/api/endpoint` to see that the endpoint works as expected.
2. Run `now dev` and visit `localhost:3000/api/endpoint` to see that the endpoint doesn't work as expected. There is a 404 instead.

# Notes

1. Based on the [now gatsby example](https://github.com/zeit/now-examples/tree/master/gatsby)
2. `now` version: 15.7.0
3. Removing the static builds builder from `now.json` fixes the issue.
