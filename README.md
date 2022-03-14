# LOGS_P

# 20220314 How to share HTML Pages (the Web Fundamental Principle is Broken)

Pasting the HTML with image tags won't get them uploaded to a wiki page.
Need to find a one step process for uploading my local HTML pages with images in one step.

how to migrate html into github wiki...

Found

https://docs.github.com/en/communities/documenting-your-project-with-wikis/adding-or-editing-wiki-pages

https://docs.github.com/en/communities/documenting-your-project-with-wikis/adding-or-editing-wiki-pages#adding-or-editing-wiki-pages-locally

# Step1: Clones the wiki locally
$ git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.wiki.git

the wiki page appears as "Home.md" but is essentially my INDEX.HTM verbatum content.

# Step2:
Added the images to the local git

Note: my images are relative to the HTML page, thus they don't specify any path.

# Step3:
Use Sync from VSCode

It worked.
