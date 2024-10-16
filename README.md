# site
IoTA dev board web site

## Testing
```sh
# Start node.js-based "serve" with nice logs
npx serve

# or use Linux built-in but more limited Python server
python3 -m http.server
```

## Resizing images
```sh
# Resize and make the image exact size with crop
convert <source> -resize 353x326^ -gravity Center -crop 353x326+0+0 +repage <destination>
```