build:
    hugo -s dist/

clean:
    rm -rf dist/

post:
    hugo new post/$(POST_NAME).md
    echo 'title: "$(POST_TITLE)"' >> content/post/$(POST_NAME).md
## The "build" step uses the Hugo static site generator to generate the website from the markdown and configuration files in the "dist" directory.

The "clean" step uses the "rm" command to remove the entire "dist" directory and all its contents.

The "post" step uses the Hugo command "hugo new" to create a new markdown file with the filename specified by the "POST_NAME" environment variable in the "content/post" directory. It then uses the "echo" command to add the title specified by the "POST_TITLE" environment variable to the top of the new markdown file.
##
