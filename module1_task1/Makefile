clean:
	rm -fr ./dist
build:
	hugo > /dev/null 2>&1
post:
	hugo new post/$(POST_NAME).md
	echo 'title: "$(POST_TITLE)"' >> content/post/$(POST_NAME).md
