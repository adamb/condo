# condo

Simple site to list condo info.

Add photos

Ran this to compress the images:

% for file in *.jpeg; do magick "$file" -resize 1080x1080 -quality 75 -strip "compressed_$file"; done

