# docker-tailwindcss
You can use tailwindcss from docker.

This docker image uses bun.sh and installed these packages.
- tailwindcss@latest
- @tailwindcss/forms
- @tailwindcss/typography

# Example
```
docker run --rm -v "$PWD:/app" peccu/tailwindcss -i input.css -o output.css --minify
```

