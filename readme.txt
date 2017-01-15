#Clone github "go-messanger" project:
https://github.com/usmanismail/go-messenger

# Install golang (GO-Lang)
docker run --rm -it \
-v $PWD:/go/src/github.com/[USERNAME]/[PROJECT]/[SUB-CDIRECTORY]/ \
-e SOURCE_PATH=github.com/[USERNAME]/[PROJECT]/[SUB-CDIRECTORY]/ \
usman/go-builder:1.4


